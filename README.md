# Docker Jenkins Slave
#### A jenkins slave for Docker Plugin

## Usage:
1. Build this Dockerfile on the docker host while setting a `tag` for the build.
2. On Jenkins, after you configure the Docker cloud, create an  
image(template), name it by the same `name` as the `tag` from before  
and give it a `label`.
3. On the Job configuration, set the `node` to be the `label` you set on step 2.

**You're done!**


## BSD-3 License

Copyright (c) 2016, Shaked Lokits
All rights reserved.

Redistribution and use in source and binary forms, with or without modification,  
are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice,  
this list of conditions and the following disclaimer.
2. Redistributions in binary form must reproduce the above copyright notice,  
this list of conditions and the following disclaimer in the documentation and/or  
other materials provided with the distribution.
3. Neither the name of the copyright holder nor the names of its contributors  
may be used to endorse or promote products derived from this software without  
specific prior written permission.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"  
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED  
WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE DISCLAIMED.  
IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT,  
INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES  
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;  
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY  
THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING  
NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE,  
EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
