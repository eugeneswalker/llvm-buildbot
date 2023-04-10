FROM esw123/ubuntu20.04-runner-x86_64:2023-04-01

RUN pip install --no-cache-dir --upgrade pip \
 && pip install --no-cache-dir 'buildbot[bundle]' \
 && rm -rf ~/.cache
