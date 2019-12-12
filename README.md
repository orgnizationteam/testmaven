test maven


local.properties中添加
maven.user=xxx                      //maven账号
maven.pw=xxx                        //maven账号密码
signing.keyId=xxx                   //密钥keyid
signing.password=xxx                //密钥密码
signing.secretKeyRingFile=xxx       //gpg密钥路径
bintray.user=xxx                    //bintray账号
bintray.repo=xxx                    //bintray创建仓库名称
bintray.apikey=xxx                  //bintray api key


上传maven
uploadArchives


上传jcenter
bintrayUpload

