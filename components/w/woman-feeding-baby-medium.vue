<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#iF4Pwje)" class="d2kvgvbvc"><path fill="url(#i3qCxSb)" class="g07_awftm"/><path fill="url(#iLlGRGd)" class="g07_awftm"/><path fill="url(#iAVQBzc)" class="g07_awftm"/><path fill="url(#ixjsBlc)" class="g07_awftm"/><path fill="url(#iJC4oFd)" class="g07_awftm"/><path fill="url(#iKNWDLc)" class="g07_awftm"/><path fill="url(#i9rtmti)" class="g07_awftm"/><path fill="url(#irxL5Av)" class="g07_awftm"/><path fill="url(#i2Kk0Vc)" class="g07_awftm"/><path fill="url(#i8Wkybu)" class="g07_awftm"/><path fill="url(#izbyN1b)" class="g07_awftm"/><path fill="url(#iXK3xbc)" class="g07_awftm"/></g><path fill="url(#iKcuqsd)" class="u3dyzlbjv"/><path fill="url(#imkOl4b)" class="u3dyzlbjv"/><path fill="url(#iMgemPi)" class="rk01_7i4j"/><path fill="url(#iQWMPBb)" class="rk01_7i4j"/><g filter="url(#i3Mjppe)"><path fill="url(#iHuZEVc)" class="v38ej3bia"/></g><path fill="url(#iGeh32d)" class="v38ej3bia"/><g filter="url(#i21qFId)"><path fill="url(#iPge7eb)" class="hy2yz5u7s"/><path fill="url(#iYN7zCb)" class="hy2yz5u7s"/></g><g filter="url(#iDELRob)"><path class="ozj168bih"/><path fill="url(#iKsY4Ud)" class="k-7z2k2_j"/></g><g filter="url(#iCgOacc)"><path class="lrxzofbuv"/><path fill="url(#idm5lYb)" class="xnxq0xbqz"/></g><g filter="url(#iDvHm9b)"><path fill="url(#ids84Kb)" class="e77imdbzb"/><path fill="url(#iJVmPic)" class="e77imdbzb"/><path fill="url(#ih8jOLc)" class="e77imdbzb"/><path fill="url(#idXcovZ)" class="e77imdbzb"/><path fill="url(#i4aM6Ll)" class="e77imdbzb"/><path fill="url(#ifmfvnc)" class="e77imdbzb"/></g><path fill="url(#iDHzuxp)" class="e77imdbzb"/><g filter="url(#iBeGdLb)"><path class="ik8tofw5s"/></g><g filter="url(#iERhsId)"><path class="ojndfubpq"/><path fill="url(#ihYUfkc)" class="raehomb3g"/><path fill="url(#irNzV7d)" class="raehomb3g"/><path fill="url(#igIPYOc)" class="raehomb3g"/><path fill="url(#iJf7Vzj)" class="raehomb3g"/></g><g filter="url(#iZsvJbb)"><path stroke="url(#iNqzOrv)" class="gt7ho0b4o"/></g><path class="qks5xj_da"/><g filter="url(#iT87RBb)"><path class="ulcnlcctq"/><path fill="url(#iq91aMc)" class="t8gy_cbga"/><path fill="url(#iJ6b5vd)" class="t8gy_cbga"/></g><g filter="url(#iIV2gOd)"><path class="in-d1dbxg"/><path fill="url(#ikh6QIb)" class="fi_urxbxe"/><path fill="url(#i0sFhod)" class="fi_urxbxe"/></g><g filter="url(#itDY7fW)"><path stroke="url(#iNwzCGc)" class="d9zj3qbkr"/></g><g filter="url(#iRroR6c)"><path class="klrjvtrbl"/></g><g filter="url(#iObM9qe)"><path fill="url(#imzILBc)" class="vnqb_2bjn"/></g><g filter="url(#ilK9uUc)"><path fill="url(#iivFF0c)" class="yzuakkeae"/></g><path fill="url(#iTBAsab)" class="vl1ra-bem"/><path fill="url(#iMpsobd)" class="k8e__sbjl"/><g filter="url(#iklMZ2Z)" class="tryqaac1t"><path stroke="url(#iLBO4bW)" class="em-92_bvs"/><path stroke="url(#i5YtwdL)" class="em-92_bvs"/></g><g filter="url(#ivKmOAb)" class="tryqaac1t"><path stroke="url(#isDScBd)" class="lde8gublo"/><path stroke="url(#iq51pub)" class="lde8gublo"/></g><g filter="url(#iYXLpeb)"><path clip-rule="evenodd" class="w_r29tbtd"/></g><g filter="url(#ihgHe0b)"><path class="kc1t_obvi"/></g><g filter="url(#iSZqKjd)"><path class="hgsquxqdw"/></g><g filter="url(#it1qJTb)"><path class="ozr03ck1l"/></g><path class="umj075h7d"/><path fill="url(#ijIm0je)" class="kk7js4npx"/><path fill="url(#iWTYRmb)" class="kk7js4npx"/><path fill="url(#idGb3ie)" class="kk7js4npx"/><path fill="url(#ikv8kRc)" class="kk7js4npx"/><path fill="url(#iqjXkZd)" class="kk7js4npx"/><path fill="url(#iIIe9Md)" class="kk7js4npx"/><path fill="url(#i9DRdse)" class="kk7js4npx"/><g filter="url(#ihzE3db)"><path fill="url(#iPUUIce)" class="p974_vb_p"/><path fill="url(#iM6JAsb)" class="p974_vb_p"/><path fill="url(#i6JFKDb)" class="p974_vb_p"/></g><path fill="url(#iRPDqEd)" class="uz-edxbzx"/><g filter="url(#iuNxZWc)"><path fill="url(#iFiTdqd)" class="zolpq1kdo"/><path fill="url(#iAYuGMM)" class="zolpq1kdo"/></g><g filter="url(#iYp1UFN)"><path class="iacyjubvw"/><path fill="url(#ioE3iMb)" class="i-2nraczg"/><path fill="url(#ijJybcd)" class="i-2nraczg"/><path fill="url(#id1DTZc)" class="i-2nraczg"/><path fill="url(#ijapF0b)" class="i-2nraczg"/></g><path fill="url(#iBSV0iK)" class="gg58tgbtk"/><path fill="url(#i4MWA1c)" class="gg58tgbtk"/><path fill="url(#ihV8szb)" class="lwi__xyuu"/><path fill="url(#i04pdnc)" class="lwi__xyuu"/><path fill="url(#i6QVbxc)" class="zb5d44soh"/><path fill="url(#iRYEX3d)" class="zb5d44soh"/><path fill="url(#iX37L0z)" class="zb5d44soh"/><path fill="url(#imRRpcM)" class="zb5d44soh"/><path fill="url(#iu8Faze)" class="zb5d44soh"/><path fill="url(#izbDsMb)" class="y0lpdikzy"/><path fill="url(#iT456Zc)" class="il7yezind"/><path fill="url(#ip7sBie)" class="il7yezind"/><path fill="url(#im4jhQa)" class="il7yezind"/><g filter="url(#izccVOb)"><path stroke="url(#iy7eB4D)" class="z-s5vdp4x"/></g><path fill="url(#i56o3ob)" class="oqsvzkbhl"/><path fill="url(#iSLhZHd)" class="oqsvzkbhl"/><path fill="url(#ih3UDjd)" class="i5kg2cb1n"/><g filter="url(#i5FaADe)"><path fill="url(#iTnmQMj)" class="o01kmnp0p"/><path fill="url(#iDFtQpd)" class="o01kmnp0p"/><path fill="url(#izdsDLe)" class="o01kmnp0p"/></g><path fill="url(#i3JP01b)" class="o4hb8tz8h"/><path fill="url(#ix8npxc)" class="o4hb8tz8h"/><path fill="url(#ie1XBke)" class="o4hb8tz8h"/><path fill="url(#iiIo3Ce)" class="o4hb8tz8h"/><path class="klzkplifs"/><path fill="url(#i4YBCST)" class="e86gmxb3l"/><path fill="url(#izJllOd)" class="e86gmxb3l"/><path class="hb9ublb3w"/><path fill="url(#i59Jzld)" class="z0jq_6xno"/><path fill="url(#iXvFtpd)" class="z0jq_6xno"/><path fill="url(#iN0T2TQ)" class="z0jq_6xno"/><path fill="url(#i02pvSc)" class="ozbs1sb6t"/><path fill="url(#ilMOFDc)" class="ozbs1sb6t"/><path fill="url(#iKoQdid)" class="ozbs1sb6t"/><path fill="url(#iNdz0hc)" class="ozbs1sb6t"/><path fill="url(#il79Ige)" class="v7qudgp8n"/><path fill="url(#ibgm4kd)" class="v7qudgp8n"/><path fill="url(#iUdByzd)" class="v7qudgp8n"/><path fill="url(#iBwVZSb)" class="v7qudgp8n"/><path fill="url(#if6rkxd)" class="v7qudgp8n"/><path fill="url(#i5Kyhic)" class="fwtpwjaqk"/><path fill="url(#i76VVRd)" class="fwtpwjaqk"/><path fill="url(#isZgIId)" class="fwtpwjaqk"/><path fill="url(#i5fNVEb)" class="fwtpwjaqk"/><g filter="url(#iT8sFmE)"><path stroke="url(#i1ryvGd)" class="e26829b8n"/></g><g filter="url(#icD23tb)" class="mc2zb0bvp"><path class="y25ki7bsx"/></g><g filter="url(#iIJCYNb)" class="mc2zb0bvp"><path class="ebqtlac1e"/></g><defs><radialGradient id="iLlGRGd" cx="0" cy="0" r="1" gradientTransform="matrix(.27691 4.62668 -5.77967 .34592 14.51 13.01)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="w9gpkna4y"/><stop offset="1" class="xvq3mubqy"/></radialGradient><radialGradient id="iAVQBzc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.47993 2.47647 -3.25388 -3.25843 11.776 13.815)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="u3fmvdnwh"/><stop offset="1" class="ysga7wb0w"/></radialGradient><radialGradient id="ixjsBlc" cx="0" cy="0" r="1" gradientTransform="matrix(-.96587 1.94224 -1.49138 -.74166 9.58 11.625)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="jo-m975mj"/><stop offset="1" class="ecm2ecc2d"/></radialGradient><radialGradient id="iJC4oFd" cx="0" cy="0" r="1" gradientTransform="matrix(-.87217 2.33707 -1.64626 -.61436 9.638 9.532)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="ksj-40n4x"/><stop offset="1" class="qkj18_koj"/></radialGradient><radialGradient id="iKNWDLc" cx="0" cy="0" r="1" gradientTransform="matrix(1.86118 2.32372 -3.22568 2.5836 9.302 3.178)" gradientUnits="userSpaceOnUse"><stop class="bk_mrebvc"/><stop offset="1" class="o57gz703y"/></radialGradient><radialGradient id="i9rtmti" cx="0" cy="0" r="1" gradientTransform="rotate(124.034 8.563 6.757)scale(2.05451 2.87114)" gradientUnits="userSpaceOnUse"><stop class="g2m4aac5s"/><stop offset="1" class="tulkzacvs"/></radialGradient><radialGradient id="irxL5Av" cx="0" cy="0" r="1" gradientTransform="matrix(-1.72141 .88412 -1.84376 -3.58987 21.596 8.196)" gradientUnits="userSpaceOnUse"><stop class="ii82yjbfl"/><stop offset="1" class="tobrp8lrd"/></radialGradient><radialGradient id="i2Kk0Vc" cx="0" cy="0" r="1" gradientTransform="rotate(154.999 9.531 8.248)scale(2.92529 3.72638)" gradientUnits="userSpaceOnUse"><stop class="gto3tpbjl"/><stop offset="1" class="k8ni71bqd"/></radialGradient><radialGradient id="i8Wkybu" cx="0" cy="0" r="1" gradientTransform="rotate(-119.808 11.023 -2.167)scale(2.82234 2.23231)" gradientUnits="userSpaceOnUse"><stop class="j6tbtfb5n"/><stop offset="1" class="u7ezkxzae"/></radialGradient><radialGradient id="izbyN1b" cx="0" cy="0" r="1" gradientTransform="matrix(1.5183 -.1322 .2142 2.4601 8.082 10.777)" gradientUnits="userSpaceOnUse"><stop class="r4e237cot"/><stop offset="1" class="ktpt3tb_i"/></radialGradient><radialGradient id="iXK3xbc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53933 -3.50454 1.26486 -.55558 19.093 7.975)" gradientUnits="userSpaceOnUse"><stop class="fyy3crxae"/><stop offset="1" class="x7431zb1g"/></radialGradient><radialGradient id="imkOl4b" cx="0" cy="0" r="1" gradientTransform="matrix(2.19471 3.52472 -6.20084 3.86104 16.045 15.479)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="wcbvx-n_a"/><stop offset="1" class="sbx2zkbbn"/></radialGradient><radialGradient id="iQWMPBb" cx="0" cy="0" r="1" gradientTransform="matrix(.49877 3.04 -2.59498 .42576 15.685 15.46)" gradientUnits="userSpaceOnUse"><stop offset=".787" class="cicq2ubuy"/><stop offset=".984" class="kvmahyufm"/></radialGradient><radialGradient id="iGeh32d" cx="0" cy="0" r="1" gradientTransform="rotate(-129.474 7.884 4.253)scale(1.38004 1.56378)" gradientUnits="userSpaceOnUse"><stop class="wlzou1bho"/><stop offset="1" class="muarw1mje"/></radialGradient><radialGradient id="iPge7eb" cx="0" cy="0" r="1" gradientTransform="matrix(2.24553 -1.59629 1.949 2.74169 18.41 10.138)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="xqzyuky4n"/><stop offset="1" class="yiz6fvgdb"/></radialGradient><radialGradient id="iYN7zCb" cx="0" cy="0" r="1" gradientTransform="matrix(1.19387 -.2313 .09959 .51403 18.895 7.842)" gradientUnits="userSpaceOnUse"><stop class="v4cuahbfk"/><stop offset="1" class="ame5l9u0o"/></radialGradient><radialGradient id="iKsY4Ud" cx="0" cy="0" r="1" gradientTransform="matrix(1.47217 -.4005 .31308 1.15082 18.697 9.747)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="j_jb06m8v"/><stop offset="1" class="t9v208shd"/></radialGradient><radialGradient id="idm5lYb" cx="0" cy="0" r="1" gradientTransform="rotate(169.035 4.343 6.149)scale(1.06406)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="w5re42dqy"/><stop offset="1" class="w4wkyodwa"/></radialGradient><radialGradient id="ids84Kb" cx="0" cy="0" r="1" gradientTransform="rotate(144.28 7.013 7.446)scale(7.21801 9.66118)" gradientUnits="userSpaceOnUse"><stop class="ox3481l0h"/><stop offset="1" class="l65mx1yct"/></radialGradient><radialGradient id="iJVmPic" cx="0" cy="0" r="1" gradientTransform="matrix(-1.97337 1.36724 -.95213 -1.37423 16.34 10.413)" gradientUnits="userSpaceOnUse"><stop class="vw42v6b3v"/><stop offset="1" class="v5m4qhb2r"/></radialGradient><radialGradient id="ih8jOLc" cx="0" cy="0" r="1" gradientTransform="matrix(.52251 -4.13407 5.24537 .66297 13.334 16.799)" gradientUnits="userSpaceOnUse"><stop class="hl813wbpa"/><stop offset="1" class="a21bmlbcx"/></radialGradient><radialGradient id="idXcovZ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 8.1028 -9.76973 -1.54484 15.902 9.258)" gradientUnits="userSpaceOnUse"><stop offset=".534" class="f3s_o0kxd"/><stop offset=".901" class="a0ddhhfxg"/></radialGradient><radialGradient id="i4aM6Ll" cx="0" cy="0" r="1" gradientTransform="rotate(157.932 7.072 7.25)scale(7.09267 12.2114)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="qh0bdqbav"/><stop offset="1" class="dt7ct4boy"/></radialGradient><radialGradient id="ifmfvnc" cx="0" cy="0" r="1" gradientTransform="matrix(-.2424 3.35954 -2.68818 -.19396 15.07 6.975)" gradientUnits="userSpaceOnUse"><stop class="aotu-xwil"/><stop offset="1" class="izc7dk1pl"/></radialGradient><radialGradient id="iDHzuxp" cx="0" cy="0" r="1" gradientTransform="rotate(169.035 9.255 5.948)scale(1.29538 6.49621)" gradientUnits="userSpaceOnUse"><stop class="fyxppic9g"/><stop offset="1" class="kq5b787yl"/></radialGradient><radialGradient id="ihYUfkc" cx="0" cy="0" r="1" gradientTransform="rotate(-113.528 11.465 .758)scale(2.11022 .65035)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="iJf7Vzj" cx="0" cy="0" r="1" gradientTransform="matrix(-.77104 .14939 -.04176 -.21556 15.15 11.828)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="iq91aMc" cx="0" cy="0" r="1" gradientTransform="rotate(-76.356 9.747 -.784)scale(3.05394 1.56232)" gradientUnits="userSpaceOnUse"><stop class="gaydocc3b"/><stop offset="1" class="o5ryhdc_j"/></radialGradient><radialGradient id="iJ6b5vd" cx="0" cy="0" r="1" gradientTransform="matrix(.75862 -2.17437 1.16734 .40728 9.71 7.575)" gradientUnits="userSpaceOnUse"><stop class="bkfqk3fbn"/><stop offset="1" class="hrqlkdbpd"/></radialGradient><radialGradient id="ikh6QIb" cx="0" cy="0" r="1" gradientTransform="rotate(104.719 6.474 6.804)scale(4.91118 8.0295)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ukea7pdhy"/><stop offset="1" class="wuqjd3b5z"/></radialGradient><radialGradient id="i0sFhod" cx="0" cy="0" r="1" gradientTransform="rotate(87.782 5.005 8.284)scale(1.39415 2.99944)" gradientUnits="userSpaceOnUse"><stop class="y3gk9pbvh"/><stop offset="1" class="j2p90_-bc"/><stop offset="1" class="ru9fl6bjc"/></radialGradient><radialGradient id="i5YtwdL" cx="0" cy="0" r="1" gradientTransform="matrix(-.11643 .20123 -.19436 -.11246 17.284 9.658)" gradientUnits="userSpaceOnUse"><stop class="lql_2ab8k"/><stop offset="1" class="ea15stbaq"/></radialGradient><radialGradient id="iq51pub" cx="0" cy="0" r="1" gradientTransform="matrix(-.11643 .20123 -.19436 -.11246 13.06 10.37)" gradientUnits="userSpaceOnUse"><stop class="lql_2ab8k"/><stop offset="1" class="ea15stbaq"/></radialGradient><radialGradient id="idGb3ie" cx="0" cy="0" r="1" gradientTransform="matrix(.28711 3.40925 -4.12958 .34777 8.64 20.595)" gradientUnits="userSpaceOnUse"><stop offset=".604" class="v442oubmz"/><stop offset="1" class="p_ew-572a"/></radialGradient><radialGradient id="ikv8kRc" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 3.4375 -2.71722 -.59285 6.39 19.313)" gradientUnits="userSpaceOnUse"><stop offset=".518" class="m0rm-m-qv"/><stop offset="1" class="wi8a08bum"/></radialGradient><radialGradient id="iqjXkZd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15508 -.34883 1.8893 -6.25609 8.598 29.97)" gradientUnits="userSpaceOnUse"><stop class="wagk6dfaq"/><stop offset="1" class="hfzkti_ts"/></radialGradient><radialGradient id="i9DRdse" cx="0" cy="0" r="1" gradientTransform="rotate(86.386 -7.186 15.61)scale(1.85287 2.95057)" gradientUnits="userSpaceOnUse"><stop offset=".6" class="k5vtewq9k"/><stop offset="1" class="z1zjblq2q"/></radialGradient><radialGradient id="iPUUIce" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0785 6 -4.46735 -1.54757 16.937 24.75)" gradientUnits="userSpaceOnUse"><stop class="v2wkn2ras"/><stop offset="1" class="yxmxw0ard"/></radialGradient><radialGradient id="iM6JAsb" cx="0" cy="0" r="1" gradientTransform="rotate(-132.901 14.854 10.13)scale(4.22338 6.72611)" gradientUnits="userSpaceOnUse"><stop class="bji58ac7a"/><stop offset="1" class="eqapwmsga"/></radialGradient><radialGradient id="i6JFKDb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62501 -3.8277 2.0945 -1.4364 21.109 25.688)" gradientUnits="userSpaceOnUse"><stop offset=".393" class="c8r1g2bnk"/><stop offset="1" class="kyl8adb5j"/></radialGradient><radialGradient id="iRPDqEd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.038 1.01561 -1.51165 -8.987 27.271 22.799)" gradientUnits="userSpaceOnUse"><stop class="z3zsa5bpu"/><stop offset="1" class="c_p6lvbtv"/></radialGradient><radialGradient id="iFiTdqd" cx="0" cy="0" r="1" gradientTransform="rotate(164.954 9.06 12.707)scale(3.00943 4.47011)" gradientUnits="userSpaceOnUse"><stop class="dyh_p3bsl"/><stop offset="1" class="acgtzjb8q"/></radialGradient><radialGradient id="iAYuGMM" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66156 -1.3125 1.73451 -2.1958 22.802 25.47)" gradientUnits="userSpaceOnUse"><stop class="fo4qq4q_b"/><stop offset="1" class="a6ayzxb8w"/></radialGradient><radialGradient id="ioE3iMb" cx="0" cy="0" r="1" gradientTransform="rotate(33.14 -37.763 40.416)scale(2.25791 .79383)" gradientUnits="userSpaceOnUse"><stop class="mu_dstxav"/><stop offset="1" class="vr5bp_bxf"/></radialGradient><radialGradient id="ijJybcd" cx="0" cy="0" r="1" gradientTransform="matrix(6.57813 0 0 1.16319 12.924 29.969)" gradientUnits="userSpaceOnUse"><stop class="vc2ezub_b"/><stop offset="1" class="pdof6qbxo"/></radialGradient><radialGradient id="ijapF0b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02913 0 0 -3.40472 19.265 28.906)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="h5yda4bml"/><stop offset="1" class="xmthgnb3w"/></radialGradient><radialGradient id="iBSV0iK" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.02344 -.68462 0 19.607 27.988)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="rntqzsbvm"/><stop offset="1" class="kn6547brm"/></radialGradient><radialGradient id="i04pdnc" cx="0" cy="0" r="1" gradientTransform="matrix(-8.5625 1.81252 -.47277 -2.23342 29.083 26.44)" gradientUnits="userSpaceOnUse"><stop class="o7yf4tl0b"/><stop offset="1" class="x9s6ceaht"/></radialGradient><radialGradient id="i6QVbxc" cx="0" cy="0" r="1" gradientTransform="matrix(.84205 2.73 -2.93117 .9041 6.765 19.844)" gradientUnits="userSpaceOnUse"><stop class="h0nz-rbjw"/><stop offset="1" class="kfbnffbzx"/></radialGradient><radialGradient id="iX37L0z" cx="0" cy="0" r="1" gradientTransform="rotate(110.854 -2.794 13.022)scale(2.10677 2.16117)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="jz746dbzd"/><stop offset="1" class="dzs1febsk"/></radialGradient><radialGradient id="imRRpcM" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 .87171 -.46263 -.67998 9.906 20.816)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="cwu2h0blp"/><stop offset="1" class="f9-tluqmj"/></radialGradient><radialGradient id="iu8Faze" cx="0" cy="0" r="1" gradientTransform="matrix(.32031 .75 -.43392 .18532 7.163 20.453)" gradientUnits="userSpaceOnUse"><stop offset=".827" class="yyn9swbvh"/><stop offset="1" class="pviihufyn"/></radialGradient><radialGradient id="im4jhQa" cx="0" cy="0" r="1" gradientTransform="matrix(-.3711 1.25391 -.1532 -.04534 16.01 18.445)" gradientUnits="userSpaceOnUse"><stop class="tomvu1bgl"/><stop offset="1" class="sinn-3bvk"/></radialGradient><radialGradient id="iy7eB4D" cx="0" cy="0" r="1" gradientTransform="matrix(-.20313 -.60156 1.71998 -.58078 9.312 22.985)" gradientUnits="userSpaceOnUse"><stop class="ut4bgvb0y"/><stop offset="1" class="gngaedcou"/></radialGradient><radialGradient id="iSLhZHd" cx="0" cy="0" r="1" gradientTransform="matrix(-.64063 2 -.16496 -.05284 15.822 17.785)" gradientUnits="userSpaceOnUse"><stop class="njdbcpw8w"/><stop offset="1" class="p6n8nbb9p"/></radialGradient><radialGradient id="iDFtQpd" cx="0" cy="0" r="1" gradientTransform="rotate(25.805 -34.592 34.24)scale(1.57936 1.44294)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="l8v5z5bog"/><stop offset="1" class="ll6ec2bpd"/></radialGradient><radialGradient id="ix8npxc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0156 3.18752 -2.63101 -1.6637 9.455 18.431)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="i9r9kkbqw"/><stop offset="1" class="e16i7e3de"/></radialGradient><radialGradient id="ie1XBke" cx="0" cy="0" r="1" gradientTransform="rotate(119.595 -.04 11.712)scale(3.70167 1.33422)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="e7zd_qbyg"/><stop offset="1" class="sv2l0pbpa"/></radialGradient><radialGradient id="iiIo3Ce" cx="0" cy="0" r="1" gradientTransform="matrix(.15625 1.04772 -1.07633 .16052 9.01 20.61)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="b1nef-bor"/><stop offset="1" class="jcycylcex"/></radialGradient><radialGradient id="i4YBCST" cx="0" cy="0" r="1" gradientTransform="matrix(.03125 -.93275 3.89243 .13041 12.72 17.494)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="lp7kx4bze"/><stop offset="1" class="hbjsfnbqm"/></radialGradient><radialGradient id="izJllOd" cx="0" cy="0" r="1" gradientTransform="matrix(.82031 .17968 -.24565 1.1215 9.814 16.078)" gradientUnits="userSpaceOnUse"><stop offset=".293" class="jwxh3bbfb"/><stop offset="1" class="r6a-j5bnt"/></radialGradient><radialGradient id="i59Jzld" cx="0" cy="0" r="1" gradientTransform="rotate(-80.715 17.197 2.27)scale(.83681 3.75171)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="kyubtxb-o"/><stop offset="1" class="a0y-a0b2f"/></radialGradient><radialGradient id="iXvFtpd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 .41406 -.20022 -.51377 13.814 17.49)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="vhb97r3hm"/><stop offset="1" class="m9i-5tkbo"/></radialGradient><radialGradient id="iN0T2TQ" cx="0" cy="0" r="1" gradientTransform="matrix(.61328 .25 -.50554 1.24016 9.53 16.938)" gradientUnits="userSpaceOnUse"><stop class="xaxho9f-m"/><stop offset="1" class="g_ars-u5d"/></radialGradient><radialGradient id="i02pvSc" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 1.51562 -5.32458 -2.85442 11.143 18.742)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="bkr4sabrv"/><stop offset="1" class="vy_5_bh0s"/></radialGradient><radialGradient id="ilMOFDc" cx="0" cy="0" r="1" gradientTransform="matrix(1.85937 1.375 -.35309 .47747 11.69 18.993)" gradientUnits="userSpaceOnUse"><stop class="or_kejb-o"/><stop offset="1" class="a-of3kbjs"/></radialGradient><radialGradient id="iKoQdid" cx="0" cy="0" r="1" gradientTransform="matrix(-.3672 .53142 -1.08325 -.74848 12.062 18.766)" gradientUnits="userSpaceOnUse"><stop offset=".139" class="eh5j-nbpx"/><stop offset="1" class="ih66ipb5v"/></radialGradient><radialGradient id="iNdz0hc" cx="0" cy="0" r="1" gradientTransform="matrix(1.0304 -.54867 .96509 1.81241 8.94 18.82)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="esfed8bwd"/><stop offset="1" class="n24z6jbtl"/></radialGradient><radialGradient id="il79Ige" cx="0" cy="0" r="1" gradientTransform="matrix(1.09945 -1.69165 1.88005 1.2219 8.869 21.439)" gradientUnits="userSpaceOnUse"><stop offset=".407" class="wi_pdjbvv"/><stop offset="1" class="g5ydalx2k"/></radialGradient><radialGradient id="ibgm4kd" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 .84935 -.34383 .46806 10.768 19.993)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="y2mfwqgbt"/><stop offset="1" class="wo3blnxxa"/></radialGradient><radialGradient id="iUdByzd" cx="0" cy="0" r="1" gradientTransform="rotate(102.218 -2.946 14.086)scale(2.03036 4.87917)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="d-e4mcb8q"/><stop offset=".962" class="cts2nkbix"/></radialGradient><radialGradient id="iBwVZSb" cx="0" cy="0" r="1" gradientTransform="matrix(.61483 -.19518 .6509 2.0503 7.801 20.462)" gradientUnits="userSpaceOnUse"><stop class="l_gp-_bkz"/><stop offset="1" class="j9v-nnbxs"/></radialGradient><radialGradient id="if6rkxd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.56249 -1.92189 3.39221 -2.75786 9.83 21.54)" gradientUnits="userSpaceOnUse"><stop offset=".832" class="u_sc2wgtl"/><stop offset="1" class="iwejj4bye"/></radialGradient><radialGradient id="i76VVRd" cx="0" cy="0" r="1" gradientTransform="rotate(105.675 1.043 15.783)scale(1.31451 .34383)" gradientUnits="userSpaceOnUse"><stop class="cn05xwrkd"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="isZgIId" cx="0" cy="0" r="1" gradientTransform="rotate(105.036 .927 16.259)scale(.54206 .1592)" gradientUnits="userSpaceOnUse"><stop class="em3lc9y5i"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="i5fNVEb" cx="0" cy="0" r="1" gradientTransform="rotate(174.906 8.355 10.276)scale(.43997 .38553)" gradientUnits="userSpaceOnUse"><stop class="tzj34xnjq"/><stop offset="1" class="ugbytbngn"/></radialGradient><radialGradient id="i1ryvGd" cx="0" cy="0" r="1" gradientTransform="matrix(-.26365 -2.21465 3.37212 -.40144 7.768 21.785)" gradientUnits="userSpaceOnUse"><stop class="zbwshaccu"/><stop offset="1" class="piz2rbc3b"/></radialGradient><linearGradient id="i3qCxSb" x1="17.641" x2="13.633" y1="2.699" y2="14.522" gradientUnits="userSpaceOnUse"><stop class="ap760fb9g"/><stop offset="1" class="w1etxcbdz"/></linearGradient><linearGradient id="iKcuqsd" x1="19.224" x2="12.336" y1="18.574" y2="30.251" gradientUnits="userSpaceOnUse"><stop class="q9xywcr7e"/><stop offset="1" class="jvlxembhy"/></linearGradient><linearGradient id="iMgemPi" x1="15.152" x2="17.218" y1="17.051" y2="18.188" gradientUnits="userSpaceOnUse"><stop class="j3joqzbnz"/><stop offset="1" class="butvbccuy"/></linearGradient><linearGradient id="iHuZEVc" x1="8.118" x2="9.955" y1="11.77" y2="11.414" gradientUnits="userSpaceOnUse"><stop class="cg1k0hirj"/><stop offset="1" class="u6m78ac0i"/></linearGradient><linearGradient id="irNzV7d" x1="13.656" x2="14.585" y1="11.975" y2="11.795" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="igIPYOc" x1="14.72" x2="14.6" y1="12.494" y2="11.874" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="iNqzOrv" x1="13.955" x2="14.274" y1="14.185" y2="13.392" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="iNwzCGc" x1="9.92" x2="10.647" y1="4.195" y2="5.353" gradientUnits="userSpaceOnUse"><stop class="olrv_cchi"/><stop offset="1" class="lwhsndh-i"/></linearGradient><linearGradient id="imzILBc" x1="12.753" x2="10.212" y1="9.806" y2="9.531" gradientUnits="userSpaceOnUse"><stop class="s_1mgzhbo"/><stop offset="1" class="t-u7o5ykp"/></linearGradient><linearGradient id="iivFF0c" x1="17.235" x2="13.95" y1="9.304" y2="8.213" gradientUnits="userSpaceOnUse"><stop offset=".394" class="aqne2ebmr"/><stop offset="1" class="zufjkvb9h"/></linearGradient><linearGradient id="iTBAsab" x1="17.18" x2="15.702" y1="10" y2="10.78" gradientUnits="userSpaceOnUse"><stop offset=".558" class="vg8k7bbhe"/><stop offset="1" class="w-7avbcrn"/></linearGradient><linearGradient id="iMpsobd" x1="12.927" x2="11.445" y1="10.718" y2="11.494" gradientUnits="userSpaceOnUse"><stop offset=".558" class="vg8k7bbhe"/><stop offset="1" class="w-7avbcrn"/></linearGradient><linearGradient id="iLBO4bW" x1="15.26" x2="17.461" y1="10.093" y2="10.246" gradientUnits="userSpaceOnUse"><stop class="hcvz7rbkn"/><stop offset="1" class="dq4m0ybwq"/></linearGradient><linearGradient id="isDScBd" x1="11.036" x2="13.237" y1="10.805" y2="10.958" gradientUnits="userSpaceOnUse"><stop class="hcvz7rbkn"/><stop offset="1" class="dq4m0ybwq"/></linearGradient><linearGradient id="ijIm0je" x1="9.109" x2="3.64" y1="26.282" y2="24.813" gradientUnits="userSpaceOnUse"><stop class="g1c-6jb6y"/><stop offset="1" class="hkdf97w8c"/></linearGradient><linearGradient id="iWTYRmb" x1="3.333" x2="5.328" y1="25.91" y2="26.563" gradientUnits="userSpaceOnUse"><stop class="da95trp0k"/><stop offset="1" class="feoz1vgta"/></linearGradient><linearGradient id="iIIe9Md" x1="9.229" x2="8.836" y1="28.3" y2="28.175" gradientUnits="userSpaceOnUse"><stop class="rehc034in"/><stop offset="1" class="psvt8ubmu"/></linearGradient><linearGradient id="id1DTZc" x1="18.227" x2="17.566" y1="26.244" y2="27.138" gradientUnits="userSpaceOnUse"><stop offset=".175" class="d9x2ylwjm"/><stop offset="1" class="ow_pc7b8u"/></linearGradient><linearGradient id="i4MWA1c" x1="19.395" x2="19.395" y1="26.602" y2="27.441" gradientUnits="userSpaceOnUse"><stop class="y-ymn0bhn"/><stop offset="1" class="he69lvb0i"/></linearGradient><linearGradient id="ihV8szb" x1="26.546" x2="26.984" y1="26.75" y2="30.469" gradientUnits="userSpaceOnUse"><stop class="tnk2b_bjh"/><stop offset="1" class="p40qzpbtf"/></linearGradient><linearGradient id="iRYEX3d" x1="5.833" x2="6.912" y1="19.722" y2="21.425" gradientUnits="userSpaceOnUse"><stop class="j4n7g28_w"/><stop offset="1" class="laie_nbgc"/></linearGradient><linearGradient id="izbDsMb" x1="12.351" x2="11.964" y1="20.233" y2="18.251" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="iT456Zc" x1="16.078" x2="15.296" y1="18.031" y2="21.018" gradientUnits="userSpaceOnUse"><stop class="e6bcurcdv"/><stop offset="1" class="jxwnoqbqn"/></linearGradient><linearGradient id="ip7sBie" x1="15.205" x2="15.428" y1="21.238" y2="20.347" gradientUnits="userSpaceOnUse"><stop class="w_57dfb5m"/><stop offset="1" class="t78i98bfv"/></linearGradient><linearGradient id="i56o3ob" x1="14.953" x2="13.828" y1="17.266" y2="21.594" gradientUnits="userSpaceOnUse"><stop class="nn3wh7bnm"/><stop offset="1" class="tbs366q3s"/></linearGradient><linearGradient id="ih3UDjd" x1="15.265" x2="14.156" y1="17.641" y2="17.282" gradientUnits="userSpaceOnUse"><stop class="h94nvm15h"/><stop offset="1" class="qtvy6rbzh"/></linearGradient><linearGradient id="iTnmQMj" x1="14.453" x2="13.223" y1="17.157" y2="21.907" gradientUnits="userSpaceOnUse"><stop class="qic_n_blg"/><stop offset="1" class="qh-ows9fr"/></linearGradient><linearGradient id="izdsDLe" x1="12.549" x2="12.768" y1="20.972" y2="19.894" gradientUnits="userSpaceOnUse"><stop class="e122-lbju"/><stop offset="1" class="grqmao4rm"/></linearGradient><linearGradient id="i3JP01b" x1="8.421" x2="8.964" y1="16.657" y2="21.157" gradientUnits="userSpaceOnUse"><stop class="a79moebrw"/><stop offset="1" class="hkuv0zb-z"/></linearGradient><linearGradient id="i5Kyhic" x1="16.521" x2="15.937" y1="18.532" y2="21.032" gradientUnits="userSpaceOnUse"><stop class="neym138jd"/><stop offset="1" class="kmp3a3cnr"/></linearGradient><filter id="iF4Pwje" width="15.862" height="16.554" x="6.835" y="1.229" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.133333 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3539"/></filter><filter id="i3Mjppe" width="3.393" height="3.244" x="8.071" y="9.754" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.607843 0 0 0 0 0.458824 0 0 0 0 0.403922 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3539"/></filter><filter id="i21qFId" width="3.243" height="3.494" x="17.484" y="7.681" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.34902 0 0 0 0 0.384314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3539"/></filter><filter id="iDELRob" width="3.165" height="3.165" x="17.523" y="7.97" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3539" stdDeviation=".25"/></filter><filter id="iCgOacc" width="2.865" height="2.865" x="8.28" y="9.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3539" stdDeviation=".175"/></filter><filter id="iDvHm9b" width="10.656" height="10.609" x="8.903" y="6.128" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3539"/></filter><filter id="iBeGdLb" width="2.876" height="3.758" x="13.045" y="9.49" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3539" stdDeviation=".25"/></filter><filter id="iERhsId" width="2.376" height="3.247" x="13.429" y="9.583" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3539" stdDeviation=".125"/></filter><filter id="iZsvJbb" width="3.672" height="1.839" x="13.011" y="12.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3539" stdDeviation=".05"/></filter><filter id="iT87RBb" width="4.053" height="5.102" x="7.262" y="4.21" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.286275 0 0 0 0 0.27451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3539"/><feGaussianBlur result="effect2_foregroundBlur_4002_3539" stdDeviation=".2"/></filter><filter id="iIV2gOd" width="9.437" height="4.692" x="9.944" y="2.635" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.317647 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3539"/><feGaussianBlur result="effect2_foregroundBlur_4002_3539" stdDeviation=".125"/></filter><filter id="itDY7fW" width="1.467" height="2.187" x="9.914" y="4.259" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3539" stdDeviation=".1"/></filter><filter id="iRroR6c" width="6.614" height="3.359" x="12.852" y="3.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3539" stdDeviation=".375"/></filter><filter id="iObM9qe" width="3.726" height="2.903" x="10.047" y="8.336" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3539" stdDeviation=".3"/></filter><filter id="ilK9uUc" width="3.547" height="2.822" x="14.652" y="7.411" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3539" stdDeviation=".3"/></filter><filter id="iklMZ2Z" width="2.468" height="1.196" x="15.15" y="9.352" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3539" stdDeviation=".075"/></filter><filter id="ivKmOAb" width="2.468" height="1.196" x="10.926" y="10.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3539" stdDeviation=".075"/></filter><filter id="iYXLpeb" width="2.5" height=".892" x="15.192" y="7.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3539"/></filter><filter id="ihgHe0b" width="2.309" height=".769" x="15.216" y="7.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3539" stdDeviation=".1"/></filter><filter id="iSZqKjd" width="2.377" height="1.388" x="10.172" y="8.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.121569 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3539"/></filter><filter id="it1qJTb" width="2.177" height="1.26" x="10.166" y="8.184" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3539" stdDeviation=".1"/></filter><filter id="ihzE3db" width="11.192" height="8.359" x="11.466" y="21.86" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.607843 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3539"/></filter><filter id="iuNxZWc" width="7.407" height="8.444" x="19.048" y="18.689" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3539"/></filter><filter id="iYp1UFN" width="8.208" height="4.667" x="12.416" y="25.302" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.54902 0 0 0 0 0.419608 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3539"/></filter><filter id="izccVOb" width="3.456" height="1.701" x="7.381" y="21.772" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3539" stdDeviation=".1"/></filter><filter id="i5FaADe" width="4.309" height="4.662" x="11.043" y="16.434" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.552941 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3539"/></filter><filter id="iT8sFmE" width="3.647" height="2.753" x="6.263" y="19.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3539" stdDeviation=".05"/></filter><filter id="icD23tb" width="2.634" height="2.141" x="16.374" y="25.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3539" stdDeviation=".125"/></filter><filter id="iIJCYNb" width="4.536" height="1" x="12.746" y="28.565" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3539" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-feeding-baby-medium" /></template>
<style>
.a-of3kbjs {
  stop-color: var(--svg-color--a87f6c, #A87F6C);
  stop-opacity: 0;
}

.a0ddhhfxg {
  stop-color: var(--svg-color--754865, #754865);
}

.a0y-a0b2f {
  stop-color: var(--svg-color--8d5c59, #8D5C59);
  stop-opacity: 0;
}

.a21bmlbcx {
  stop-color: var(--svg-color--945a73, #945A73);
  stop-opacity: 0;
}

.a6ayzxb8w {
  stop-color: var(--svg-color--289d47, #289D47);
  stop-opacity: 0;
}

.a79moebrw {
  stop-color: var(--svg-color--8e705c, #8E705C);
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.acgtzjb8q {
  stop-color: var(--svg-color--3ba055, #3BA055);
}

.ame5l9u0o {
  stop-color: var(--svg-color--906d53, #906D53);
  stop-opacity: 0;
}

.aotu-xwil {
  stop-color: var(--svg-color--ab8179, #AB8179);
}

.ap760fb9g {
  stop-color: var(--svg-color--6d524e, #6D524E);
}

.aqne2ebmr {
  stop-color: var(--svg-color--b48474, #B48474);
}

.b1nef-bor {
  stop-color: var(--svg-color--94596d, #94596D);
}

.bji58ac7a {
  stop-color: var(--svg-color--208d47, #208D47);
}

.bk_mrebvc {
  stop-color: var(--svg-color--554543, #554543);
}

.bkfqk3fbn {
  stop-color: var(--svg-color--4b2839, #4B2839);
}

.bkr4sabrv {
  stop-color: var(--svg-color--ac866d, #AC866D);
}

.butvbccuy {
  stop-color: var(--svg-color--ab837b, #AB837B);
}

.c_p6lvbtv {
  stop-color: var(--svg-color--31be7d, #31BE7D);
}

.c8r1g2bnk {
  stop-color: var(--svg-color--148c3e, #148C3E);
}

.cg1k0hirj {
  stop-color: var(--svg-color--8d645f, #8D645F);
}

.cicq2ubuy {
  stop-color: var(--svg-color--7f5268, #7F5268);
  stop-opacity: 0;
}

.cn05xwrkd {
  stop-color: var(--svg-color--fed466, #FED466);
}

.cts2nkbix {
  stop-color: var(--svg-color--935067, #935067);
}

.cwu2h0blp {
  stop-color: var(--svg-color--6b3d8e, #6B3D8E);
}

.d-e4mcb8q {
  stop-color: var(--svg-color--935067, #935067);
  stop-opacity: 0;
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d9x2ylwjm {
  stop-color: var(--svg-color--b99477, #B99477);
}

.d9zj3qbkr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M10.214 4.56c.07.235.454 1.098.866 1.586");
}

.da95trp0k {
  stop-color: var(--svg-color--8f73b3, #8F73B3);
}

.dq4m0ybwq {
  stop-color: var(--svg-color--533f3d, #533F3D);
  stop-opacity: 0;
}

.dt7ct4boy {
  stop-color: var(--svg-color--9a7267, #9A7267);
}

.dyh_p3bsl {
  stop-color: var(--svg-color--279f64, #279F64);
}

.dzs1febsk {
  stop-color: var(--svg-color--6f409a, #6F409A);
  stop-opacity: 0;
}

.e122-lbju {
  stop-color: var(--svg-color--8b72aa, #8B72AA);
}

.e16i7e3de {
  stop-color: var(--svg-color--6f3928, #6F3928);
}

.e26829b8n {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.593 19.72c-.206.431-.319 1.448.875 2.054s1.992.148 2.242-.156");
}

.e6bcurcdv {
  stop-color: var(--svg-color--6cd9f5, #6CD9F5);
}

.e77imdbzb {
  d: path("m9.053 10.203l.012-.002l-.06-.26l-.07-.301c-.161-.943.317-1.413.526-1.58q.022-.011.047-.03L9.555 8c.48-.344.825-.85.94-1.449l.044-.207a.266.266 0 0 1 .447-.14a3.9 3.9 0 0 0 3.477 1.045l3.186-.617c.178-.035 1.087-.121 1.379 1.1l.472 3.064c.415 2.796-1.39 5.078-4.033 5.59s-5.17-.93-5.829-3.68z");
}

.e7zd_qbyg {
  stop-color: var(--svg-color--ab8870, #AB8870);
}

.e86gmxb3l {
  d: path("M10.099 16.43c.356.125.482.33.515.453l.446.39l2.291.363a.92.92 0 0 0 1.062-.872a.913.913 0 0 0-.922-.95c-1.175.014-2.687.036-3.044.026c-.586-.015-.793.434-.348.59");
}

.ea15stbaq {
  stop-color: var(--svg-color--594543, #594543);
  stop-opacity: 0;
}

.ebqtlac1e {
  stroke: var(--svg-color--ba8c83, #BA8C83);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.246 29.065h3.536");
}

.ecm2ecc2d {
  stop-color: var(--svg-color--27141e, #27141E);
  stop-opacity: 0;
}

.eh5j-nbpx {
  stop-color: var(--svg-color--87624f, #87624F);
}

.em-92_bvs {
  d: path("M15.4 10.008c.124.116.49.334.966.282c.477-.051.895-.514 1.003-.688");
}

.em3lc9y5i {
  stop-color: var(--svg-color--fed064, #FED064);
}

.eqapwmsga {
  stop-color: var(--svg-color--208d47, #208D47);
  stop-opacity: 0;
}

.esfed8bwd {
  stop-color: var(--svg-color--947260, #947260);
}

.f3s_o0kxd {
  stop-color: var(--svg-color--946b6c, #946B6C);
  stop-opacity: 0;
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.f9-tluqmj {
  stop-color: var(--svg-color--6b3d8e, #6B3D8E);
  stop-opacity: 0;
}

.feoz1vgta {
  stop-color: var(--svg-color--8f73b3, #8F73B3);
  stop-opacity: 0;
}

.fi_urxbxe {
  d: path("M12.238 2.885c-1.168-.03-1.958 1.283-1.994 1.72c1.72 3.306 4.316 2.604 6.86 1.812c1.522-.475 1.828.202 2.027.519c-.753-3.891-4.204-3.98-6.863-4.05z");
}

.fo4qq4q_b {
  stop-color: var(--svg-color--289d47, #289D47);
}

.ft5dv1b6b {
  fill: none;
}

.fu3c0cblo {
  stop-color: var(--svg-color--f38820, #F38820);
}

.fwtpwjaqk {
  d: path("m15.454 20.735l.227.068a.5.5 0 0 0 .492-.12l.363-.352a.13.13 0 0 1 .128-.033l.315.084a.484.484 0 0 0 .253-.936l-.304-.083a.13.13 0 0 1-.097-.108l-.069-.44a.5.5 0 0 0-.36-.404l-.26-.072z");
}

.fyxppic9g {
  stop-color: var(--svg-color--c0967a, #C0967A);
}

.fyy3crxae {
  stop-color: var(--svg-color--3e2125, #3E2125);
}

.g_ars-u5d {
  stop-color: var(--svg-color--997963, #997963);
  stop-opacity: 0;
}

.g07_awftm {
  d: path("M21.71 10.495a3.3 3.3 0 0 0 .046-1.474a3.3 3.3 0 0 0-.516-1.24h.006a3 3 0 0 0-.377-.455l-.003-.002a3.27 3.27 0 0 1-.86-1.652l-.002-.01a3.326 3.326 0 0 0-3.897-2.632a.54.54 0 0 1-.495-.143a3.33 3.33 0 0 0-2.917-.847a3.33 3.33 0 0 0-2.39 1.875a.57.57 0 0 1-.406.318l-.084.017a3.326 3.326 0 0 0-2.548 3.88l.002.01c.12.62.058 1.266-.181 1.853l-.002.004a3.33 3.33 0 0 0 .404 3.253c.098.127.13.297.088.45a3.24 3.24 0 0 0 3.75 4.021l8.491-1.644a3.24 3.24 0 0 0 1.978-5.131a.52.52 0 0 1-.088-.45m-12.644-.294l-.012.003l1.638 2.1c.659 2.75 1.204-.233 3.847-.745s4.394 2.351 3.979-.445l.51-3.382c-.291-1.221-1.2-1.134-1.379-1.1l-3.186.617a3.9 3.9 0 0 1-3.476-1.044a.266.266 0 0 0-.447.139l-.044.207a2.32 2.32 0 0 1-.94 1.45l-.047.03l-.047.03c-.21.166-.687.636-.526 1.579l.07.3z");
}

.g1c-6jb6y {
  stop-color: var(--svg-color--8a4fe4, #8A4FE4);
}

.g2m4aac5s {
  stop-color: var(--svg-color--6e5350, #6E5350);
}

.g5ydalx2k {
  stop-color: var(--svg-color--ba9374, #BA9374);
}

.gaydocc3b {
  stop-color: var(--svg-color--5c4643, #5C4643);
}

.gg58tgbtk {
  d: path("M18.998 26.752a.15.15 0 0 1 .15-.15h.643v3.367h-.793z");
}

.gngaedcou {
  stop-color: var(--svg-color--8a68c3, #8A68C3);
  stop-opacity: 0;
}

.grqmao4rm {
  stop-color: var(--svg-color--b59cc2, #B59CC2);
  stop-opacity: 0;
}

.gt7ho0b4o {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.887 13.359c-.515.1-1.023.07-1.472-.069c-.153-.045-.272.144-.16.256a1.947 1.947 0 0 0 3.216-.622c.061-.152-.118-.278-.244-.179c-.364.296-.82.513-1.34.614Z");
}

.gto3tpbjl {
  stop-color: var(--svg-color--564544, #564544);
}

.h0nz-rbjw {
  stop-color: var(--svg-color--7f5499, #7F5499);
}

.h5yda4bml {
  stop-color: var(--svg-color--814c4e, #814C4E);
}

.h94nvm15h {
  stop-color: var(--svg-color--43b1db, #43B1DB);
}

.hb9ublb3w {
  fill: var(--svg-color--a8836a, #A8836A);
  d: path("M9.67 17.352c.243.25.33.526.343.633l.485.469l2.34.407a.89.89 0 0 0 1.025-.693a.9.9 0 0 0-.774-1.079c-1.09-.132-2.42-.305-2.779-.346c-.613-.07-.945.297-.64.609");
}

.hbjsfnbqm {
  stop-color: var(--svg-color--936e63, #936E63);
  stop-opacity: 0;
}

.hcvz7rbkn {
  stop-color: var(--svg-color--533f3d, #533F3D);
}

.he69lvb0i {
  stop-color: var(--svg-color--755994, #755994);
  stop-opacity: 0;
}

.hfzkti_ts {
  stop-color: var(--svg-color--8e5de1, #8E5DE1);
  stop-opacity: 0;
}

.hgsquxqdw {
  fill: var(--svg-color--432a28, #432A28);
  d: path("m10.627 9.37l-.004.003a.27.27 0 0 1-.361-.402l.001-.002l.003-.002l.008-.007a2 2 0 0 1 .132-.105a3 3 0 0 1 .375-.238a2.8 2.8 0 0 1 1.293-.363a.27.27 0 0 1 .01.54c-.409.007-.774.15-1.044.297a3 3 0 0 0-.413.278");
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hkdf97w8c {
  stop-color: var(--svg-color--804ec1, #804EC1);
}

.hkuv0zb-z {
  stop-color: var(--svg-color--8e685c, #8E685C);
}

.hl813wbpa {
  stop-color: var(--svg-color--945a73, #945A73);
}

.hm31m3bmo {
  stop-color: var(--svg-color--875f54, #875F54);
}

.hrqlkdbpd {
  stop-color: var(--svg-color--4b2839, #4B2839);
  stop-opacity: 0;
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.hy2yz5u7s {
  d: path("M19.414 11.144a1.621 1.621 0 1 0-.617-3.183a1.621 1.621 0 0 0 .617 3.183");
}

.i-2nraczg {
  d: path("M17.18 25.651a.937.937 0 0 0-1.12 1.498l.931.801a.1.1 0 0 1-.063.176l-3.644.072a.886.886 0 0 0 .018 1.77h6.06v-1l1.062-1.226z");
}

.i5kg2cb1n {
  d: path("m14.826 17.067l-2.636-.735l-1.073 3.896l2.6.733c.408.11.755-.064.85-.393l.78-2.704c.123-.39-.164-.693-.521-.797");
}

.i9r9kkbqw {
  stop-color: var(--svg-color--91576c, #91576C);
  stop-opacity: 0;
}

.iacyjubvw {
  fill: var(--svg-color--a77671, #A77671);
  d: path("M17.18 25.651a.937.937 0 0 0-1.12 1.498l.931.801a.1.1 0 0 1-.063.176l-3.644.072a.886.886 0 0 0 .018 1.77h6.06v-1l1.062-1.226z");
}

.ih66ipb5v {
  stop-color: var(--svg-color--87624f, #87624F);
  stop-opacity: 0;
}

.ii82yjbfl {
  stop-color: var(--svg-color--604947, #604947);
}

.ik8tofw5s {
  fill: var(--svg-color--88555f, #88555F);
  d: path("m13.899 10.333l-.35 1.812a.543.543 0 0 0 .648.593l.778-.151a.545.545 0 0 0 .381-.792l-.851-1.58c-.185-.35-.56-.278-.607.118");
}

.il7yezind {
  d: path("m15.53 17.835l.554.159a.15.15 0 0 1 .103.185l-.784 2.73a.15.15 0 0 1-.185.103l-.555-.16z");
}

.in-d1dbxg {
  fill: var(--svg-color--553836, #553836);
  d: path("M12.238 2.885c-1.168-.03-1.958 1.283-1.994 1.72c1.72 3.306 4.316 2.604 6.86 1.812c1.522-.475 1.828.202 2.027.519c-.753-3.891-4.204-3.98-6.863-4.05z");
}

.iwejj4bye {
  stop-color: var(--svg-color--937160, #937160);
}

.izc7dk1pl {
  stop-color: var(--svg-color--ab8179, #AB8179);
  stop-opacity: 0;
}

.j_jb06m8v {
  stop-color: var(--svg-color--a26d62, #A26D62);
  stop-opacity: 0;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j3joqzbnz {
  stop-color: var(--svg-color--764a5c, #764A5C);
}

.j4n7g28_w {
  stop-color: var(--svg-color--8e72a9, #8E72A9);
}

.j6tbtfb5n {
  stop-color: var(--svg-color--5f4846, #5F4846);
}

.j9v-nnbxs {
  stop-color: var(--svg-color--8e655d, #8E655D);
  stop-opacity: 0;
}

.jcycylcex {
  stop-color: var(--svg-color--945c6f, #945C6F);
  stop-opacity: 0;
}

.jo-m975mj {
  stop-color: var(--svg-color--27141e, #27141E);
}

.jvlxembhy {
  stop-color: var(--svg-color--7d49d2, #7D49D2);
}

.jwxh3bbfb {
  stop-color: var(--svg-color--987763, #987763);
}

.jxwnoqbqn {
  stop-color: var(--svg-color--3782ce, #3782CE);
}

.jz746dbzd {
  stop-color: var(--svg-color--6f409a, #6F409A);
}

.k_pdrlblj {
  stop-color: var(--svg-color--ebb830, #EBB830);
  stop-opacity: 0;
}

.k-7z2k2_j {
  d: path("M19.312 10.615A1.082 1.082 0 1 0 18.9 8.49a1.082 1.082 0 0 0 .412 2.125");
}

.k5vtewq9k {
  stop-color: var(--svg-color--8b5dd1, #8B5DD1);
}

.k8e__sbjl {
  d: path("M12.994 10.153c-.075.01-.132.057-.18.123a1.04 1.04 0 0 1-.7.482a1 1 0 0 1-.812-.208a.24.24 0 0 0-.208-.056a.252.252 0 0 0-.114.444a1.49 1.49 0 0 0 1.23.321a1.51 1.51 0 0 0 1.049-.728c.104-.18-.057-.406-.265-.378");
}

.k8ni71bqd {
  stop-color: var(--svg-color--564544, #564544);
  stop-opacity: 0;
}

.kc1t_obvi {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.516 7.89c.304-.139 1.105-.253 1.708.023");
}

.kfbnffbzx {
  stop-color: var(--svg-color--7a45b3, #7A45B3);
}

.kk7js4npx {
  d: path("m2.201 29.97l2.93-9.157C5.482 19.4 7.2 18.71 8.78 19.2s2.49 2.332 2.006 3.691L8.571 29.97z");
}

.klrjvtrbl {
  fill: var(--svg-color--664a4a, #664A4A);
  d: path("m15.909 5.88l-1.36.532a.693.693 0 1 1-.385-1.327l2.315-.448c1.37-.265 2.09 1.027 2.237 1.488a3.17 3.17 0 0 0-2.807-.246");
}

.klzkplifs {
  fill: var(--svg-color--a37e69, #A37E69);
  d: path("M10.099 16.43c.356.125.482.33.515.453l.446.39l2.291.363a.92.92 0 0 0 1.062-.872a.913.913 0 0 0-.922-.95c-1.175.014-2.687.036-3.044.026c-.586-.015-.793.434-.348.59");
}

.kmp3a3cnr {
  stop-color: var(--svg-color--ce953a, #CE953A);
}

.kn6547brm {
  stop-color: var(--svg-color--8259a4, #8259A4);
}

.kq5b787yl {
  stop-color: var(--svg-color--c0967a, #C0967A);
  stop-opacity: 0;
}

.ksj-40n4x {
  stop-color: var(--svg-color--230c14, #230C14);
}

.ktpt3tb_i {
  stop-color: var(--svg-color--56413d, #56413D);
  stop-opacity: 0;
}

.kvmahyufm {
  stop-color: var(--svg-color--7f5268, #7F5268);
}

.kyl8adb5j {
  stop-color: var(--svg-color--148c3e, #148C3E);
  stop-opacity: 0;
}

.kyubtxb-o {
  stop-color: var(--svg-color--8d5c59, #8D5C59);
}

.l_gp-_bkz {
  stop-color: var(--svg-color--8e655d, #8E655D);
}

.l65mx1yct {
  stop-color: var(--svg-color--946568, #946568);
}

.l8v5z5bog {
  stop-color: var(--svg-color--6e574e, #6E574E);
}

.laie_nbgc {
  stop-color: var(--svg-color--8e72a9, #8E72A9);
  stop-opacity: 0;
}

.lde8gublo {
  d: path("M11.176 10.72c.124.116.49.333.966.282c.477-.052.896-.514 1.003-.688");
}

.ll6ec2bpd {
  stop-color: var(--svg-color--6e574e, #6E574E);
  stop-opacity: 0;
}

.lp7kx4bze {
  stop-color: var(--svg-color--936e63, #936E63);
}

.lql_2ab8k {
  stop-color: var(--svg-color--594543, #594543);
}

.lrxzofbuv {
  fill: var(--svg-color--7e555a, #7E555A);
  d: path("M9.918 12.435a1.082 1.082 0 1 0-.412-2.126a1.082 1.082 0 0 0 .412 2.126");
}

.lwhsndh-i {
  stop-color: var(--svg-color--452531, #452531);
}

.lwi__xyuu {
  d: path("M20.615 25.746c1.598-.23 4.567-.808 6.543-1.27c1.522-.262 2.641 1.204 2.641 2.782c0 1.37-1.022 2.236-1.747 2.618a.86.86 0 0 1-.403.093h-8.014v-3.086c0-.797.281-1 .98-1.137");
}

.m0rm-m-qv {
  stop-color: var(--svg-color--785191, #785191);
}

.m9i-5tkbo {
  stop-color: var(--svg-color--a6816a, #A6816A);
  stop-opacity: 0;
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mu_dstxav {
  stop-color: var(--svg-color--905d66, #905D66);
}

.muarw1mje {
  stop-color: var(--svg-color--814e62, #814E62);
  stop-opacity: 0;
}

.n24z6jbtl {
  stop-color: var(--svg-color--8f6d5d, #8F6D5D);
  stop-opacity: 0;
}

.n8jici3hn {
  stop-color: var(--svg-color--fed466, #FED466);
  stop-opacity: 0;
}

.neym138jd {
  stop-color: var(--svg-color--f3c22a, #F3C22A);
}

.njdbcpw8w {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
}

.nn3wh7bnm {
  stop-color: var(--svg-color--58d4f5, #58D4F5);
}

.o01kmnp0p {
  d: path("m12.167 16.434l2.635.735c.357.103.645.406.521.797l-.779 2.703c-.096.33-.442.504-.851.394l-2.6-.734z");
}

.o4hb8tz8h {
  d: path("M8.13 17.211c1.031-1.085 1.92-1.37 2.32-1.375l.797.868l-.93 3.515c-.179.315-.563.996-.695 1.153c-.164.195-.734.63-1.765.238c-.888-.338-1.15-.899-1.176-1.149c.234-1.167.649-2.357 1.45-3.25");
}

.o57gz703y {
  stop-color: var(--svg-color--554543, #554543);
  stop-opacity: 0;
}

.o5ryhdc_j {
  stop-color: var(--svg-color--5c4643, #5C4643);
  stop-opacity: 0;
}

.o7yf4tl0b {
  stop-color: var(--svg-color--b087f9, #B087F9);
}

.ojndfubpq {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m13.882 10.194l-.2 1.783a.543.543 0 0 0 .65.592l.777-.15a.545.545 0 0 0 .381-.792l-.852-1.58c-.184-.35-.71-.249-.756.147");
}

.olrv_cchi {
  stop-color: var(--svg-color--361f1f, #361F1F);
}

.oqsvzkbhl {
  d: path("m11.939 16.003l3.172.884c.43.125.744.559.627.96l-.9 3.086c-.115.396-.532.607-1.024.474l-3.129-.883z");
}

.or_kejb-o {
  stop-color: var(--svg-color--c29c8a, #C29C8A);
}

.ow_pc7b8u {
  stop-color: var(--svg-color--b99477, #B99477);
  stop-opacity: 0;
}

.ox3481l0h {
  stop-color: var(--svg-color--c79980, #C79980);
}

.ozbs1sb6t {
  d: path("M8.521 18.45a.28.28 0 0 1 .133-.27c.981-.69 2.005-.305 2.383 0c.304.236 1 .789 1.363 1.082c.446.36.372.961.043 1.316c-.276.298-.751.241-.93.149l-2.097-1.313c-.055-.312-.235-.562-.48-.637c-.247-.074-.403-.132-.415-.328");
}

.ozj168bih {
  fill: var(--svg-color--b38574, #B38574);
  d: path("M19.312 10.615A1.082 1.082 0 1 0 18.9 8.49a1.082 1.082 0 0 0 .412 2.125");
}

.ozr03ck1l {
  stroke: var(--svg-color--5b4545, #5B4545);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M12.043 8.485c-.334-.016-1.12.176-1.577.659");
}

.p_ew-572a {
  stop-color: var(--svg-color--8152c8, #8152C8);
  stop-opacity: 0;
}

.p40qzpbtf {
  stop-color: var(--svg-color--985ef1, #985EF1);
}

.p6n8nbb9p {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
  stop-opacity: 0;
}

.p974_vb_p {
  d: path("M21.835 23.989c-1.17-2.04-3.78-2.73-5.81-1.56l-2.43 1.4c-2.04 1.17-2.73 3.78-1.56 5.81l.21.33h7.73l.3-.18a4.23 4.23 0 0 0 1.56-5.8");
}

.pdof6qbxo {
  stop-color: var(--svg-color--98567e, #98567E);
  stop-opacity: 0;
}

.pdon63boo {
  stop-color: var(--svg-color--f38820, #F38820);
  stop-opacity: 0;
}

.piz2rbc3b {
  stop-color: var(--svg-color--875ab4, #875AB4);
  stop-opacity: 0;
}

.psvt8ubmu {
  stop-color: var(--svg-color--8356d1, #8356D1);
  stop-opacity: 0;
}

.pviihufyn {
  stop-color: var(--svg-color--784787, #784787);
  stop-opacity: 0;
}

.q9xywcr7e {
  stop-color: var(--svg-color--9c6ed3, #9C6ED3);
}

.qh-ows9fr {
  stop-color: var(--svg-color--a07cb6, #A07CB6);
}

.qh0bdqbav {
  stop-color: var(--svg-color--9a7267, #9A7267);
  stop-opacity: 0;
}

.qic_n_blg {
  stop-color: var(--svg-color--d2c9d1, #D2C9D1);
}

.qkj18_koj {
  stop-color: var(--svg-color--230c14, #230C14);
  stop-opacity: 0;
}

.qks5xj_da {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M14.887 13.359c-.515.1-1.023.07-1.472-.069c-.153-.045-.272.144-.16.256a1.947 1.947 0 0 0 3.216-.622c.061-.152-.118-.278-.244-.179c-.364.296-.82.513-1.34.614");
}

.qtvy6rbzh {
  stop-color: var(--svg-color--42b8e0, #42B8E0);
}

.r4e237cot {
  stop-color: var(--svg-color--56413d, #56413D);
}

.r6a-j5bnt {
  stop-color: var(--svg-color--987763, #987763);
  stop-opacity: 0;
}

.raehomb3g {
  d: path("m13.882 10.194l-.2 1.783a.543.543 0 0 0 .65.592l.777-.15a.545.545 0 0 0 .381-.792l-.852-1.58c-.184-.35-.71-.249-.756.147");
}

.rehc034in {
  stop-color: var(--svg-color--8356d1, #8356D1);
}

.rk01_7i4j {
  d: path("M15.685 18.5c1.06 0 1.91-.86 1.91-1.91v-2.26a1.91 1.91 0 1 0-3.82 0v2.26c-.01 1.06.85 1.91 1.91 1.91");
}

.rntqzsbvm {
  stop-color: var(--svg-color--925cbe, #925CBE);
}

.ru9fl6bjc {
  stop-color: var(--svg-color--634945, #634945);
  stop-opacity: 0;
}

.s_1mgzhbo {
  stop-color: var(--svg-color--8d5d63, #8D5D63);
}

.sbx2zkbbn {
  stop-color: var(--svg-color--89579c, #89579C);
  stop-opacity: 0;
}

.sinn-3bvk {
  stop-color: var(--svg-color--6cd8f5, #6CD8F5);
  stop-opacity: 0;
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.sv2l0pbpa {
  stop-color: var(--svg-color--8f715e, #8F715E);
  stop-opacity: 0;
}

.t-u7o5ykp {
  stop-color: var(--svg-color--8d5d63, #8D5D63);
  stop-opacity: 0;
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.t78i98bfv {
  stop-color: var(--svg-color--735caf, #735CAF);
  stop-opacity: 0;
}

.t8gy_cbga {
  d: path("M8.165 5.524c.445-.701 1.504-.907 2.01-.914l.64 1.201c-.258.01-.293.055-.446.274c.074 1.107-1.024 2.002-2.434 2.727c-.433-1.447-.349-2.376.23-3.288");
}

.t9v208shd {
  stop-color: var(--svg-color--a26d62, #A26D62);
}

.tbs366q3s {
  stop-color: var(--svg-color--4760c0, #4760C0);
}

.tnk2b_bjh {
  stop-color: var(--svg-color--a078e0, #A078E0);
}

.tobrp8lrd {
  stop-color: var(--svg-color--604947, #604947);
  stop-opacity: 0;
}

.tomvu1bgl {
  stop-color: var(--svg-color--78e0ff, #78E0FF);
}

.tryqaac1t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.tulkzacvs {
  stop-color: var(--svg-color--6e5350, #6E5350);
  stop-opacity: 0;
}

.tzj34xnjq {
  stop-color: var(--svg-color--ffd267, #FFD267);
}

.u_sc2wgtl {
  stop-color: var(--svg-color--937160, #937160);
  stop-opacity: 0;
}

.u3dyzlbjv {
  d: path("M7.155 29.969c-1.05 0-1.9-.85-1.89-1.9l.01-2.13c0-5.77 4.79-10.46 10.69-10.46c5.91 0 10.69 4.68 10.69 10.46l.17 4.03z");
}

.u3fmvdnwh {
  stop-color: var(--svg-color--25131c, #25131C);
}

.u6m78ac0i {
  stop-color: var(--svg-color--604138, #604138);
}

.u7ezkxzae {
  stop-color: var(--svg-color--5f4846, #5F4846);
  stop-opacity: 0;
}

.ugbytbngn {
  stop-color: var(--svg-color--ffd267, #FFD267);
  stop-opacity: 0;
}

.ukea7pdhy {
  stop-color: var(--svg-color--442534, #442534);
  stop-opacity: 0;
}

.ulcnlcctq {
  fill: var(--svg-color--49302e, #49302E);
  d: path("M8.165 5.524c.445-.701 1.504-.907 2.01-.914l.64 1.201c-.258.01-.293.055-.446.274c.074 1.107-1.024 2.002-2.434 2.727c-.433-1.447-.349-2.376.23-3.288");
}

.umj075h7d {
  fill: var(--svg-color--9c84d0, #9C84D0);
  d: path("m29.145 25.31l-4.94-6.05l-3.16 8.57z");
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.ut4bgvb0y {
  stop-color: var(--svg-color--8a68c3, #8A68C3);
}

.uz-edxbzx {
  d: path("M23.695 27.099a4.3 4.3 0 1 0 0-8.6a4.3 4.3 0 0 0 0 8.6");
}

.v2wkn2ras {
  stop-color: var(--svg-color--31ae6a, #31AE6A);
}

.v38ej3bia {
  d: path("M10.001 12.968a1.621 1.621 0 1 0-.616-3.184A1.621 1.621 0 0 0 10 12.967");
}

.v442oubmz {
  stop-color: var(--svg-color--7c4ca4, #7C4CA4);
}

.v4cuahbfk {
  stop-color: var(--svg-color--906d53, #906D53);
}

.v5m4qhb2r {
  stop-color: var(--svg-color--c4967a, #C4967A);
  stop-opacity: 0;
}

.v7qudgp8n {
  d: path("M8.857 20.899c-.315.22-.723.21-.906-.11c-.391-.948.72-1.579 1.5-1.597c1.167-.028 1.75.629 1.937 1.12c.188.493.227 1.477-.672 1.54c-.803.056-.847-.5-.98-.742s-.594-.41-.879-.211");
}

.vc2ezub_b {
  stop-color: var(--svg-color--98567e, #98567E);
}

.vg8k7bbhe {
  stop-color: var(--svg-color--3a2522, #3A2522);
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vhb97r3hm {
  stop-color: var(--svg-color--c7a28d, #C7A28D);
}

.vl1ra-bem {
  d: path("M17.247 9.441c-.076.01-.132.057-.18.123a1.04 1.04 0 0 1-.7.482a.96.96 0 0 1-.812-.217a.27.27 0 0 0-.208-.057a.252.252 0 0 0-.114.444a1.49 1.49 0 0 0 1.23.322a1.51 1.51 0 0 0 1.049-.728c.104-.18-.057-.407-.265-.369");
}

.vnqb_2bjn {
  d: path("M10.647 8.994c1.3-.248 2.26.34 2.527 1.063c-1.337.198-1.928.36-2.341.582z");
}

.vr5bp_bxf {
  stop-color: var(--svg-color--905d66, #905D66);
  stop-opacity: 0;
}

.vw42v6b3v {
  stop-color: var(--svg-color--c4967a, #C4967A);
}

.vy_5_bh0s {
  stop-color: var(--svg-color--966464, #966464);
}

.w_57dfb5m {
  stop-color: var(--svg-color--735caf, #735CAF);
}

.w_r29tbtd {
  fill: var(--svg-color--432a28, #432A28);
  fill-rule: evenodd;
  d: path("m17.314 7.683l-.092.254za.27.27 0 0 1-.184.509l-.005-.002a1 1 0 0 0-.123-.036a3 3 0 0 0-.365-.068a2.3 2.3 0 0 0-1.078.114a.27.27 0 1 1-.193-.504c.49-.188.977-.189 1.335-.147a3.3 3.3 0 0 1 .598.13l.01.003h.003z");
}

.w-7avbcrn {
  stop-color: var(--svg-color--38221e, #38221E);
}

.w1etxcbdz {
  stop-color: var(--svg-color--2c1c24, #2C1C24);
}

.w4wkyodwa {
  stop-color: var(--svg-color--6c4640, #6C4640);
}

.w5re42dqy {
  stop-color: var(--svg-color--6c4640, #6C4640);
  stop-opacity: 0;
}

.w9gpkna4y {
  stop-color: var(--svg-color--261326, #261326);
}

.wagk6dfaq {
  stop-color: var(--svg-color--966be0, #966BE0);
}

.wcbvx-n_a {
  stop-color: var(--svg-color--89579c, #89579C);
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wi_pdjbvv {
  stop-color: var(--svg-color--935b6e, #935B6E);
}

.wi8a08bum {
  stop-color: var(--svg-color--785191, #785191);
  stop-opacity: 0;
}

.wlzou1bho {
  stop-color: var(--svg-color--814e62, #814E62);
}

.wo3blnxxa {
  stop-color: var(--svg-color--c7a08d, #C7A08D);
  stop-opacity: 0;
}

.wuqjd3b5z {
  stop-color: var(--svg-color--442534, #442534);
}

.x7431zb1g {
  stop-color: var(--svg-color--3e2125, #3E2125);
  stop-opacity: 0;
}

.x9s6ceaht {
  stop-color: var(--svg-color--b087f9, #B087F9);
  stop-opacity: 0;
}

.xaxho9f-m {
  stop-color: var(--svg-color--997963, #997963);
}

.xmthgnb3w {
  stop-color: var(--svg-color--814c4e, #814C4E);
  stop-opacity: 0;
}

.xnxq0xbqz {
  d: path("M9.918 12.435a1.082 1.082 0 1 0-.412-2.126a1.082 1.082 0 0 0 .412 2.126");
}

.xqzyuky4n {
  stop-color: var(--svg-color--b28279, #B28279);
}

.xvq3mubqy {
  stop-color: var(--svg-color--261326, #261326);
  stop-opacity: 0;
}

.y-ymn0bhn {
  stop-color: var(--svg-color--755994, #755994);
}

.y0lpdikzy {
  d: path("M10.565 18.539c-.28.05-.54.19-.74.38c.01-.05.02-.1.04-.15l.12-.33c.28-.78 1.09-1.27 1.91-1.15l1.66.23c.42.06.72.45.66.87s-.45.72-.87.66l-1.57-.22c-.34-.26-.78-.37-1.21-.29");
}

.y25ki7bsx {
  stroke: var(--svg-color--c19885, #C19885);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m16.874 26.26l1.634 1.14");
}

.y2mfwqgbt {
  stop-color: var(--svg-color--c7a08d, #C7A08D);
}

.y3gk9pbvh {
  stop-color: var(--svg-color--634945, #634945);
}

.yiz6fvgdb {
  stop-color: var(--svg-color--cca58b, #CCA58B);
}

.ysga7wb0w {
  stop-color: var(--svg-color--25131c, #25131C);
  stop-opacity: 0;
}

.yxmxw0ard {
  stop-color: var(--svg-color--32996b, #32996B);
}

.yyn9swbvh {
  stop-color: var(--svg-color--784787, #784787);
}

.yzuakkeae {
  d: path("M15.329 8.097c.984-.31 2.27.222 2.27 1.536c-.636-.354-1.898-.49-2.347-.354z");
}

.z-s5vdp4x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M7.78 23c.579.141 1.92.172 2.657-.828");
}

.z0jq_6xno {
  d: path("M9.67 17.352c.243.25.33.526.343.633l.485.469l2.34.407a.89.89 0 0 0 1.025-.693a.9.9 0 0 0-.774-1.079c-1.09-.132-2.42-.305-2.779-.346c-.613-.07-.945.297-.64.609");
}

.z1zjblq2q {
  stop-color: var(--svg-color--8b5dd1, #8B5DD1);
  stop-opacity: 0;
}

.z3zsa5bpu {
  stop-color: var(--svg-color--53f595, #53F595);
}

.zb5d44soh {
  d: path("M10.214 21.656c-.284.88-1.448 1.292-2.6.92C6.462 22.205 5.82 21.4 6.04 20.31c.18-.888.884-1.75 2.738-1.24c1.153.372 1.719 1.706 1.435 2.586");
}

.zbwshaccu {
  stop-color: var(--svg-color--875ab4, #875AB4);
}

.zolpq1kdo {
  d: path("M21.575 23.909a4.3 4.3 0 0 1 .71-5.22a4.31 4.31 0 0 0-2.61 6.21a4.304 4.304 0 0 0 6.78 1.01c-1.84.51-3.87-.26-4.88-2");
}

.zufjkvb9h {
  stop-color: var(--svg-color--b48474, #B48474);
  stop-opacity: 0;
}

</style>
