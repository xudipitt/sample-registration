# sample-registration

This sample code implements image registration according to the below paper with OpenCV:

An FFT-Based Technique for Translation Rotation, and Scale-Invariant Image Registration

B. Srinivasa Reddy and B. N. Chatterji

IEEE TRANSACTIONS ON IMAGE PROCESSING, VOL. 5 , NO. 8, AUGUST 1996

Attentively, I avoid scale problem in this paper.

just call the below function:

void registration(
	Mat& _ref,
	Mat& _src,
	double* angle,
	double* response
); 

It will translate "_ref" for fitting "_src".If you want to get angle or response, just pass the pointer.


