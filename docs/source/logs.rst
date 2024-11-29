Latest Logs From Latest Build
==============================

Generated On: 2024-11-29 01:38:58 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/leandg5/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-11-29_01:35:46] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-11-29_01:35:51] STEP 2: Create topics started

  [INFO 2024-11-29_01:36:09] STEP 2: Completed

  [INFO 2024-11-29_01:36:20] STEP 3: producing data started

  [INFO 2024-11-29_01:36:23] MQTT connection established...

  [INFO 2024-11-29_01:36:25] STEP 4: Preprocessing started

  [INFO 2024-11-29_01:36:28] STEP 4: Preprocessing started

  [INFO 2024-11-29_01:36:30] STEP 7: Visualization started

  [INFO 2024-11-29_01:36:36] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-11-29_01:36:50] STEP 9: Success starting Qdrant.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant

  [INFO 2024-11-29_01:36:55] STEP 9: Starting privateGPT

  [INFO 2024-11-29_01:36:58] STEP 8: Starting docker push for: leandg5/myfinalcybersecurityproject-389d-amd64

  [INFO 2024-11-29_01:37:37] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-11-29_01:37:49] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit 1d539f122746 leandg5/myfinalcybersecurityproject-389d-amd64 - message=0

  [INFO 2024-11-29_01:38:35] STEP 8: Successfully ran Docker push: docker push leandg5/myfinalcybersecurityproject-389d-amd64 - message=0

  [INFO 2024-11-29_01:38:57] STEP 10: Started to build the documentation

  [INFO 2024-11-29_01:38:59] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


