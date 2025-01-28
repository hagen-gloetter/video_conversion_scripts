# video_conversion_scripts
Convert videos from different sources and sizes

The main script **hg_convert_movie_to_720p.sh** converts *.mp4 *.wmv *.mov *.mkv from old apple devices or windows phones or whatever sources that have used *.mov or *wmv into a more common and compact 720p *mp4 stream.

Features: 
- The script is running multithreaded. You can define the number of parallel conversions by changing N=6 in the code.
- After conversion the source movie is moved to the "done" folder the derived video is moved to the folder "720p"
 
**convert_flv.sh** converts old flash movie files into a more common and compact 720p *mp4 stream

**convert_wmv.sh** converts old windows media files into a more common and compact 720p *mp4 stream (basically the same as script 1. but single threaded)
