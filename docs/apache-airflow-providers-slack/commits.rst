
 .. Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

 ..   http://www.apache.org/licenses/LICENSE-2.0

 .. Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.


Package apache-airflow-providers-slack
------------------------------------------------------

`Slack <https://slack.com/>`__


This is detailed commit list of changes for versions provider package: ``slack``.
For high-level changelog, see :doc:`package information including changelog <index>`.



4.2.0
.....

Latest change: 2022-01-27

================================================================================================  ===========  ==============================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  ==============================================================================
`0ac3b8c3d <https://github.com/apache/airflow/commit/0ac3b8c3dd749c59e60cf0169580b9e7c5049d9e>`_  2022-01-27   ``Return slack api call response in slack_hook (#21107)``
`602abe839 <https://github.com/apache/airflow/commit/602abe8394fafe7de54df7e73af56de848cdf617>`_  2022-01-20   ``Remove ':type' lines now sphinx-autoapi supports typehints (#20951)``
`f77417eb0 <https://github.com/apache/airflow/commit/f77417eb0d3f12e4849d80645325c02a48829278>`_  2021-12-31   ``Fix K8S changelog to be PyPI-compatible (#20614)``
`97496ba2b <https://github.com/apache/airflow/commit/97496ba2b41063fa24393c58c5c648a0cdb5a7f8>`_  2021-12-31   ``Update documentation for provider December 2021 release (#20523)``
`a47c58a78 <https://github.com/apache/airflow/commit/a47c58a78003a1aba22fe3ac6fe7a120807bfaa9>`_  2021-12-30   ``Update SlackWebhookHook docstring (#20061)``
`d56e7b56b <https://github.com/apache/airflow/commit/d56e7b56bb9827daaf8890557147fd10bdf72a7e>`_  2021-12-30   ``Fix template_fields type to have MyPy friendly Sequence type (#20571)``
`a0821235f <https://github.com/apache/airflow/commit/a0821235fb6877a471973295fe42283ef452abf6>`_  2021-12-30   ``Use typed Context EVERYWHERE (#20565)``
`dad2f8103 <https://github.com/apache/airflow/commit/dad2f8103be954afaedf15e9d098ee417b0d5d02>`_  2021-12-15   ``Fix mypy providers (#20190)``
`853576d90 <https://github.com/apache/airflow/commit/853576d9019d2aca8de1d9c587c883dcbe95b46a>`_  2021-11-30   ``Update documentation for November 2021 provider's release (#19882)``
`d9567eb10 <https://github.com/apache/airflow/commit/d9567eb106929b21329c01171fd398fbef2dc6c6>`_  2021-10-29   ``Prepare documentation for October Provider's release (#19321)``
`d937bebda <https://github.com/apache/airflow/commit/d937bebdadeab6d159be10ea328e1947001ba73c>`_  2021-10-16   ``Doc: Restoring additional context in Slack operators how-to guide (#18985)``
================================================================================================  ===========  ==============================================================================

4.1.0
.....

Latest change: 2021-09-30

================================================================================================  ===========  ======================================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  ======================================================================================
`840ea3efb <https://github.com/apache/airflow/commit/840ea3efb9533837e9f36b75fa527a0fbafeb23a>`_  2021-09-30   ``Update documentation for September providers release (#18613)``
`ef037e702 <https://github.com/apache/airflow/commit/ef037e702182e4370cb00c853c4fb0e246a0479c>`_  2021-09-29   ``Static start_date and default arg cleanup for misc. provider example DAGs (#18597)``
`29493d2d6 <https://github.com/apache/airflow/commit/29493d2d617198e34cded1a04ab6c039012eb068>`_  2021-09-26   ``Add Slack operators how-to guide (#18525)``
`9bf0ed217 <https://github.com/apache/airflow/commit/9bf0ed2179b62f374cad74334a8976534cf1a53b>`_  2021-09-23   ``Restore 'filename' to template_fields (#18466)``
================================================================================================  ===========  ======================================================================================

4.0.1
.....

Latest change: 2021-08-30

================================================================================================  ===========  ============================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  ============================================================================
`0a6858847 <https://github.com/apache/airflow/commit/0a68588479e34cf175d744ea77b283d9d78ea71a>`_  2021-08-30   ``Add August 2021 Provider's documentation (#17890)``
`be75dcd39 <https://github.com/apache/airflow/commit/be75dcd39cd10264048c86e74110365bd5daf8b7>`_  2021-08-23   ``Update description about the new ''connection-types'' provider meta-data``
`76ed2a49c <https://github.com/apache/airflow/commit/76ed2a49c6cd285bf59706cf04f39a7444c382c9>`_  2021-08-19   ``Import Hooks lazily individually in providers manager (#17682)``
`2935be199 <https://github.com/apache/airflow/commit/2935be19901467c645bce9d134e28335f2aee7d8>`_  2021-08-16   ``Fixed SlackAPIFileOperator to upload file and file content. (#17400)``
`07c8ee015 <https://github.com/apache/airflow/commit/07c8ee01512b0cc1c4602e356b7179cfb50a27f4>`_  2021-08-02   ``Fixed SlackAPIFileOperator to upload file and file content (#17247)``
`87f408b1e <https://github.com/apache/airflow/commit/87f408b1e78968580c760acb275ae5bb042161db>`_  2021-07-26   ``Prepares docs for Rc2 release of July providers (#17116)``
`b916b7507 <https://github.com/apache/airflow/commit/b916b7507921129dc48d6add1bdc4b923b60c9b9>`_  2021-07-15   ``Prepare documentation for July release of providers. (#17015)``
`866a601b7 <https://github.com/apache/airflow/commit/866a601b76e219b3c043e1dbbc8fb22300866351>`_  2021-06-28   ``Removes pylint from our toolchain (#16682)``
================================================================================================  ===========  ============================================================================

4.0.0
.....

Latest change: 2021-06-18

================================================================================================  ===========  =======================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  =======================================================================
`bbc627a3d <https://github.com/apache/airflow/commit/bbc627a3dab17ba4cf920dd1a26dbed6f5cebfd1>`_  2021-06-18   ``Prepares documentation for rc2 release of Providers (#16501)``
`cbf8001d7 <https://github.com/apache/airflow/commit/cbf8001d7630530773f623a786f9eb319783b33c>`_  2021-06-16   ``Synchronizes updated changelog after buggfix release (#16464)``
`1fba5402b <https://github.com/apache/airflow/commit/1fba5402bb14b3ffa6429fdc683121935f88472f>`_  2021-06-15   ``More documentation update for June providers release (#16405)``
`9c94b72d4 <https://github.com/apache/airflow/commit/9c94b72d440b18a9e42123d20d48b951712038f9>`_  2021-06-07   ``Updated documentation for June 2021 provider release (#16294)``
`1e647029e <https://github.com/apache/airflow/commit/1e647029e469c1bb17e9ad051d0184f3357644c3>`_  2021-06-01   ``Rename the main branch of the Airflow repo to be 'main' (#16149)``
`10ed42a83 <https://github.com/apache/airflow/commit/10ed42a837e11d8e954c1f885e289a4248edd2ca>`_  2021-05-27   ``Fix hooks extended from http hook (#16109)``
`6d9fc3ed9 <https://github.com/apache/airflow/commit/6d9fc3ed98f694a4f30bed29cb0599c5aa5b8ef1>`_  2021-05-14   ``Fix docstring formatting on ''SlackHook'' (#15840)``
`37681bca0 <https://github.com/apache/airflow/commit/37681bca0081dd228ac4047c17631867bba7a66f>`_  2021-05-07   ``Auto-apply apply_default decorator (#15667)``
`807ad32ce <https://github.com/apache/airflow/commit/807ad32ce59e001cb3532d98a05fa7d0d7fabb95>`_  2021-05-01   ``Prepares provider release after PIP 21 compatibility (#15576)``
`40a2476a5 <https://github.com/apache/airflow/commit/40a2476a5db14ee26b5108d72635da116eab720b>`_  2021-04-28   ``Adds interactivity when generating provider documentation. (#15518)``
`bf2b48174 <https://github.com/apache/airflow/commit/bf2b48174a1ccfe398eefba7f04a5cacac421266>`_  2021-04-27   ``Add Connection Documentation for Providers (#15499)``
`a7ca1b3b0 <https://github.com/apache/airflow/commit/a7ca1b3b0bdf0b7677e53be1b11e833714dfbbb4>`_  2021-03-26   ``Fix Sphinx Issues with Docstrings (#14968)``
`68e4c4dcb <https://github.com/apache/airflow/commit/68e4c4dcb0416eb51a7011a3bb040f1e23d7bba8>`_  2021-03-20   ``Remove Backport Providers (#14886)``
================================================================================================  ===========  =======================================================================

3.0.0
.....

Latest change: 2021-02-27

================================================================================================  ===========  =======================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  =======================================================================
`589d6dec9 <https://github.com/apache/airflow/commit/589d6dec922565897785bcbc5ac6bb3b973d7f5d>`_  2021-02-27   ``Prepare to release the next wave of providers: (#14487)``
`8c060d55d <https://github.com/apache/airflow/commit/8c060d55dfb3ded21cb9d2305cffe14e1c610680>`_  2021-02-18   ``Don't allow SlackHook.call method accept *args (#14289)``
`10343ec29 <https://github.com/apache/airflow/commit/10343ec29f8f0abc5b932ba26faf49bc63c6bcda>`_  2021-02-05   ``Corrections in docs and tools after releasing provider RCs (#14082)``
================================================================================================  ===========  =======================================================================

2.0.0
.....

Latest change: 2021-02-04

================================================================================================  ===========  ========================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  ========================================================
`88bdcfa0d <https://github.com/apache/airflow/commit/88bdcfa0df5bcb4c489486e05826544b428c8f43>`_  2021-02-04   ``Prepare to release a new wave of providers. (#14013)``
`ac2f72c98 <https://github.com/apache/airflow/commit/ac2f72c98dc0821b33721054588adbf2bb53bb0b>`_  2021-02-01   ``Implement provider versioning tools (#13767)``
`283945001 <https://github.com/apache/airflow/commit/283945001363d8f492fbd25f2765d39fa06d757a>`_  2021-01-25   ``Upgrade slack_sdk to v3 (#13745)``
`3fd5ef355 <https://github.com/apache/airflow/commit/3fd5ef355556cf0ad7896bb570bbe4b2eabbf46e>`_  2021-01-21   ``Add missing logos for integrations (#13717)``
`295d66f91 <https://github.com/apache/airflow/commit/295d66f91446a69610576d040ba687b38f1c5d0a>`_  2020-12-30   ``Fix Grammar in PIP warning (#13380)``
`6cf76d7ac <https://github.com/apache/airflow/commit/6cf76d7ac01270930de7f105fb26428763ee1d4e>`_  2020-12-18   ``Fix typo in pip upgrade command :( (#13148)``
================================================================================================  ===========  ========================================================

1.0.0
.....

Latest change: 2020-12-09

================================================================================================  ===========  ==================================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  ==================================================================================
`32971a1a2 <https://github.com/apache/airflow/commit/32971a1a2de1db0b4f7442ed26facdf8d3b7a36f>`_  2020-12-09   ``Updates providers versions to 1.0.0 (#12955)``
`b40dffa08 <https://github.com/apache/airflow/commit/b40dffa08547b610162f8cacfa75847f3c4ca364>`_  2020-12-08   ``Rename remaing modules to match AIP-21 (#12917)``
`2947e0999 <https://github.com/apache/airflow/commit/2947e0999979fad1f2c98aeb4f1e46297e4c9864>`_  2020-12-02   ``SlackWebhookHook use password instead of extra (#12674)``
`c34ef853c <https://github.com/apache/airflow/commit/c34ef853c890e08f5468183c03dc8f3f3ce84af2>`_  2020-11-20   ``Separate out documentation building per provider  (#12444)``
`008035450 <https://github.com/apache/airflow/commit/00803545023b096b8db4fbd6eb473843096d7ce4>`_  2020-11-18   ``Update provider READMEs for 1.0.0b2 batch release (#12449)``
`ae7cb4a1e <https://github.com/apache/airflow/commit/ae7cb4a1e2a96351f1976cf5832615e24863e05d>`_  2020-11-17   ``Update wrong commit hash in backport provider changes (#12390)``
`6889a333c <https://github.com/apache/airflow/commit/6889a333cff001727eb0a66e375544a28c9a5f03>`_  2020-11-15   ``Improvements for operators and hooks ref docs (#12366)``
`7825e8f59 <https://github.com/apache/airflow/commit/7825e8f59034645ab3247229be83a3aa90baece1>`_  2020-11-13   ``Docs installation improvements (#12304)``
`dd2095f4a <https://github.com/apache/airflow/commit/dd2095f4a8b07c9b1a4c279a3578cd1e23b71a1b>`_  2020-11-10   ``Simplify string expressions & Use f-string (#12216)``
`85a18e13d <https://github.com/apache/airflow/commit/85a18e13d9dec84275283ff69e34704b60d54a75>`_  2020-11-09   ``Point at pypi project pages for cross-dependency of provider packages (#12212)``
`59eb5de78 <https://github.com/apache/airflow/commit/59eb5de78c70ee9c7ae6e4cba5c7a2babb8103ca>`_  2020-11-09   ``Update provider READMEs for up-coming 1.0.0beta1 releases (#12206)``
`b2a28d159 <https://github.com/apache/airflow/commit/b2a28d1590410630d66966aa1f2b2a049a8c3b32>`_  2020-11-09   ``Moves provider packages scripts to dev (#12082)``
`41bf172c1 <https://github.com/apache/airflow/commit/41bf172c1dc75099f4f9d8b3f3350b4b1f523ef9>`_  2020-11-04   ``Simplify string expressions (#12093)``
`4e8f9cc8d <https://github.com/apache/airflow/commit/4e8f9cc8d02b29c325b8a5a76b4837671bdf5f68>`_  2020-11-03   ``Enable Black - Python Auto Formmatter (#9550)``
`5a439e84e <https://github.com/apache/airflow/commit/5a439e84eb6c0544dc6c3d6a9f4ceeb2172cd5d0>`_  2020-10-26   ``Prepare providers release 0.0.2a1 (#11855)``
`872b1566a <https://github.com/apache/airflow/commit/872b1566a11cb73297e657ff325161721b296574>`_  2020-10-25   ``Generated backport providers readmes/setup for 2020.10.29 (#11826)``
`483068745 <https://github.com/apache/airflow/commit/48306874538eea7cfd42358d5ebb59705204bfc4>`_  2020-10-24   ``Use Python 3 style super classes (#11806)``
`4fb5c017f <https://github.com/apache/airflow/commit/4fb5c017fe5ca41ed95547a857c9c39efc4f1476>`_  2020-10-21   ``Check response status in slack webhook hook. (#11620)``
`349b0811c <https://github.com/apache/airflow/commit/349b0811c3022605426ba57d30936240a7c2848a>`_  2020-10-20   ``Add D200 pydocstyle check (#11688)``
`16e712971 <https://github.com/apache/airflow/commit/16e7129719f1c0940aef2a93bed81368e997a746>`_  2020-10-13   ``Added support for provider packages for Airflow 2.0 (#11487)``
`0a0e1af80 <https://github.com/apache/airflow/commit/0a0e1af80038ef89974c3c8444461fe867945daa>`_  2020-10-03   ``Fix Broken Markdown links in Providers README TOC (#11249)``
`ca4238eb4 <https://github.com/apache/airflow/commit/ca4238eb4d9a2aef70eb641343f59ee706d27d13>`_  2020-10-02   ``Fixed month in backport packages to October (#11242)``
`5220e4c38 <https://github.com/apache/airflow/commit/5220e4c3848a2d2c81c266ef939709df9ce581c5>`_  2020-10-02   ``Prepare Backport release 2020.09.07 (#11238)``
`720912f67 <https://github.com/apache/airflow/commit/720912f67b3af0bdcbac64d6b8bf6d51c6247e26>`_  2020-10-02   ``Strict type check for multiple providers (#11229)``
`0161b5ea2 <https://github.com/apache/airflow/commit/0161b5ea2b805d62a0317e5cab6f797b92c8abf1>`_  2020-09-26   ``Increasing type coverage for multiple provider (#11159)``
`f3e87c503 <https://github.com/apache/airflow/commit/f3e87c503081a3085dff6c7352640d7f08beb5bc>`_  2020-09-22   ``Add D202 pydocstyle check (#11032)``
`9549274d1 <https://github.com/apache/airflow/commit/9549274d110f689a0bd709db829a4d69e274eed9>`_  2020-09-09   ``Upgrade black to 20.8b1 (#10818)``
`fdd9b6f65 <https://github.com/apache/airflow/commit/fdd9b6f65b608c516b8a062b058972d9a45ec9e3>`_  2020-08-25   ``Enable Black on Providers Packages (#10543)``
`d1bce91bb <https://github.com/apache/airflow/commit/d1bce91bb21d5a468fa6a0207156c28fe1ca6513>`_  2020-08-25   ``PyDocStyle: Enable D403: Capitalized first word of docstring (#10530)``
`3696c34c2 <https://github.com/apache/airflow/commit/3696c34c28c6bc7b442deab999d9ecba24ed0e34>`_  2020-08-24   ``Fix typo in the word "release" (#10528)``
`2f2d8dbfa <https://github.com/apache/airflow/commit/2f2d8dbfafefb4be3dd80f22f31c649c8498f148>`_  2020-08-25   ``Remove all "noinspection" comments native to IntelliJ (#10525)``
`ee7ca128a <https://github.com/apache/airflow/commit/ee7ca128a17937313566f2badb6cc569c614db94>`_  2020-08-22   ``Fix broken Markdown refernces in Providers README (#10483)``
`cdec30125 <https://github.com/apache/airflow/commit/cdec3012542b45d23a05f62d69110944ba542e2a>`_  2020-08-07   ``Add correct signature to all operators and sensors (#10205)``
`aeea71274 <https://github.com/apache/airflow/commit/aeea71274d4527ff2351102e94aa38bda6099e7f>`_  2020-08-02   ``Remove 'args' parameter from provider operator constructors (#10097)``
`7cc1c8bc0 <https://github.com/apache/airflow/commit/7cc1c8bc0031f1d9839baaa5a6c7a9bc7ec37ead>`_  2020-07-25   ``Updates the slack WebClient call to use the instance variable - token (#9995)``
`33f0cd265 <https://github.com/apache/airflow/commit/33f0cd2657b2e77ea3477e0c93f13f1474be628e>`_  2020-07-22   ``apply_default keeps the function signature for mypy (#9784)``
`df8efd04f <https://github.com/apache/airflow/commit/df8efd04f394afc4b5affb677bc78d8b7bd5275a>`_  2020-06-21   ``Enable & Fix "Docstring Content Issues" PyDocStyle Check (#9460)``
`d0e7db402 <https://github.com/apache/airflow/commit/d0e7db4024806af35e3c9a2cae460fdeedd4d2ec>`_  2020-06-19   ``Fixed release number for fresh release (#9408)``
`12af6a080 <https://github.com/apache/airflow/commit/12af6a08009b8776e00d8a0aab92363eb8c4e8b1>`_  2020-06-19   ``Final cleanup for 2020.6.23rc1 release preparation (#9404)``
`c7e5bce57 <https://github.com/apache/airflow/commit/c7e5bce57fe7f51cefce4f8a41ce408ac5675d13>`_  2020-06-19   ``Prepare backport release candidate for 2020.6.23rc1 (#9370)``
`f6bd817a3 <https://github.com/apache/airflow/commit/f6bd817a3aac0a16430fc2e3d59c1f17a69a15ac>`_  2020-06-16   ``Introduce 'transfers' packages (#9320)``
`5cf46fad1 <https://github.com/apache/airflow/commit/5cf46fad1e0a9cdde213258b2064e16d30d3160e>`_  2020-05-29   ``Add SlackAPIFileOperator impementing files.upload from Slack API (#9004)``
`0b0e4f7a4 <https://github.com/apache/airflow/commit/0b0e4f7a4cceff3efe15161fb40b984782760a34>`_  2020-05-26   ``Preparing for RC3 relase of backports (#9026)``
`00642a46d <https://github.com/apache/airflow/commit/00642a46d019870c4decb3d0e47c01d6a25cb88c>`_  2020-05-26   ``Fixed name of 20 remaining wrongly named operators. (#8994)``
`427257c2e <https://github.com/apache/airflow/commit/427257c2e2ffc886ef9f516e9c4d015a4ede9bbd>`_  2020-05-24   ``Remove defunct code from setup.py (#8982)``
`375d1ca22 <https://github.com/apache/airflow/commit/375d1ca229464617780623c61c6e8a1bf570c87f>`_  2020-05-19   ``Release candidate 2 for backport packages 2020.05.20 (#8898)``
`12c5e5d8a <https://github.com/apache/airflow/commit/12c5e5d8ae25fa633efe63ccf4db389e2b796d79>`_  2020-05-17   ``Prepare release candidate for backport packages (#8891)``
`f3521fb0e <https://github.com/apache/airflow/commit/f3521fb0e36733d8bd356123e56a453fd37a6dca>`_  2020-05-16   ``Regenerate readme files for backport package release (#8886)``
`92585ca4c <https://github.com/apache/airflow/commit/92585ca4cb375ac879f4ab331b3a063106eb7b92>`_  2020-05-15   ``Added automated release notes generation for backport operators (#8807)``
`578fc514c <https://github.com/apache/airflow/commit/578fc514cd325b7d190bdcfb749a384d101238fa>`_  2020-05-12   ``[AIRFLOW-4543] Update slack operator to support slackclient v2 (#5519)``
`4bde99f13 <https://github.com/apache/airflow/commit/4bde99f1323d72f6c84c1548079d5e98fc0a2a9a>`_  2020-03-23   ``Make airflow/providers pylint compatible (#7802)``
`be2b2baa7 <https://github.com/apache/airflow/commit/be2b2baa7c5f53c2d73646e4623cdb6731551b70>`_  2020-03-23   ``Add missing call to Super class in 'http', 'grpc' & 'slack' providers (#7826)``
`97a429f9d <https://github.com/apache/airflow/commit/97a429f9d0cf740c5698060ad55f11e93cb57b55>`_  2020-02-02   ``[AIRFLOW-6714] Remove magic comments about UTF-8 (#7338)``
`9a04013b0 <https://github.com/apache/airflow/commit/9a04013b0e40b0d744ff4ac9f008491806d60df2>`_  2020-01-27   ``[AIRFLOW-6646][AIP-21] Move protocols classes to providers package (#7268)``
`c42a375e7 <https://github.com/apache/airflow/commit/c42a375e799e5adb3f9536616372dc90ff47e6c8>`_  2020-01-27   ``[AIRFLOW-6644][AIP-21] Move service classes to providers package (#7265)``
================================================================================================  ===========  ==================================================================================
