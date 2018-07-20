# waveflow
The waveflow software project from Wave Computing provides a Tensorflow-compatible programming interface to run machine learning models on the Wave DPU.

waveflow enables existing Tensorflow model to run on Wave Computing DPU products with little or no modification. waveflow takes care of all the DPU details, so that users need not be concerned about any technical differences. This includes transparent support for Wave's Dynamic Fixed Point (DFX) arithmetic when machine learning models are run.

waveflow has a direct dependency on Google's Tensorflow framework. Accordingly, waveflow is designed to match with a specific, very recent release-class version of Tensorflow. While there may be a development branch of waveflow to match deverloper milestones of Tensorflow, the waveflow will always be paired with a stable release of Tensorflow.
