  python neural_zoom.py -script neural_style.py -style_image examples/inputs/starry_night.jpg -content_image examples/inputs/starry_night.jpg -model_file models/vgg19-d01eb7cb.pth -backend cudnn -verbose -gpu 0 -starting_image examples/inputs/starry_night.jpg -crop 5

    python neural_zoom.py -script neural_style.py -style_image examples/inputs/starry_night.jpg -content_image examples/inputs/tubingen.jpg -model_file models/vgg19-d01eb7cb.pth -backend cudnn -verbose -gpu 0 -starting_image examples/inputs/tubingen.jpg -num_frames 300