# SFND 2D Feature Tracking Mid Term Project Writeup

This writeup provides details of the work corresponding to each rubic point.

### Data Buffer
| Task | Work |
| - | - |
| MP.1 Data Buffer Optimisation| `MidTermProject_Camera_Student.cpp` (lines 62-71) <br> Erased the beginning frame in databuffer when the it has more than 2 frames. |

### Keypoints
| Task | Work |
| - | - |
| MP.2 Keypoint Detection | `MidTermProject_Camera_Student.cpp` (lines 80-116) <br> Implemented selectable options for different types of detectors based on string. <br> `matching2D_Student.cpp` (lines 160-322) <br> Implemented Harris corner detector manually and modern detectors using opencv. | 
| MP.3 Keypoint Removal | `MidTermProject_Camera_Student.cpp` (lines 118 - 136) <br> Removed keypoints not contained in the pre-defined rectangle. |

### Descriptors
| Task | Work |
| - | - |
| MP.4 Keypoint Descriptors | `MidTermProject_Camera_Student.cpp` (lines 158-165) <br> Implemented selectable options for different types of descriptors based on string. <br> `matching2D_Student.cpp` (lines 48-117) <br> Implemented different descriptors using opencv.|
| MP.5 Descriptor Matching| `matching2D_Student.cpp` (lines 6-46) <br> Implemented FLANN matching and KNN search using opencv.  |
| MP.6 Descriptor Distance Ratio | `MidTermProject_Camera_Student.cpp` (lines 35-43) <br> Implemented matches filtering based on descriptor distance ratios. |

### Performance
| Task | Work |
| - | - |
| MP.7 Performance Evaluation 1 | `MidTermProject_Camera_Student.cpp` (lines ) <br> |
| MP.8 Performance Evaluation 2 | `MidTermProject_Camera_Student.cpp` (lines ) <br> |
| MP.9 Performance Evaluation 3 | `MidTermProject_Camera_Student.cpp` (lines ) <br> |
