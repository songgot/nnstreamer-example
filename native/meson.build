subdir('example_cam')
subdir('example_sink')
subdir ('example_early_exit')
subdir ('example_data_preprocessing_for_training')
if have_tensorflow
  subdir('example_object_detection_tensorflow')
endif

if have_tensorflow_lite
# TODO: Let's append the "example_repo_custom_easy" after sending SR to review.tizen.org
# subdir('example_repo_custom_easy')
# subdir('example_tensor_mux')
  subdir('example_face_detection_tflite')
  subdir('example_multi_model_tflite')
  subdir('example_rtmp_live_streaming')
  subdir('example_servo_tracking')
  subdir('example_image_classification_tflite')
  subdir('example_object_detection_tensorflow_lite')
  subdir('example_video_crop')
  subdir('example_object_detection_tensorflow_lite_appsrc')
  subdir('example_object_detection_tflite_2cam')
  subdir('example_decoder_image_labelling')
  subdir('example_filter_performance_profile')
  subdir('example_speech_command_tensorflow_lite')
  subdir('example_two_tensor_stream')
  subdir('example_text_classification')
  subdir('example_pose_estimation_tflite')
  subdir('example_gui_application')
  subdir('example_query_object_detection')
  subdir('example_low_light_image_enhancement')
endif

if nns_edge_dep.found()
  subdir('edgeAI_performance_benchmark')
if nntrainer_dep.found()
  subdir('example_training_offloading')
endif
endif

if have_caffe2
  subdir('example_image_classification_caffe2')
endif

if have_nnfw
  subdir('example_image_classification_nnfw')
endif
