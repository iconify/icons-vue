<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#iYcx0Jb)" class="d2kvgvbvc"><path fill="url(#iElis9b)" class="ojg0kubzr"/><path fill="url(#iSVaKWc)" class="ojg0kubzr"/><path fill="url(#ii7i7ib)" class="ojg0kubzr"/><path fill="url(#iBe6Npd)" class="ojg0kubzr"/><path fill="url(#ihZb7dl)" class="ojg0kubzr"/><path fill="url(#i5tZzxe)" class="ojg0kubzr"/><path fill="url(#izPf4de)" class="ojg0kubzr"/><path fill="url(#iAzeJrr)" class="ojg0kubzr"/><path fill="url(#iNurDGe)" class="ojg0kubzr"/><path fill="url(#iQUIUdc)" class="ojg0kubzr"/><path fill="url(#ia8Z2lb)" class="ojg0kubzr"/><path fill="url(#i9zNRGW)" class="ojg0kubzr"/></g><path fill="url(#iTw5V3V)" class="r78w96dej"/><path fill="url(#i3Memdb)" class="r78w96dej"/><path fill="url(#iN3Iqzk)" class="rk01_7i4j"/><g filter="url(#iKcnFQd)"><path fill="url(#iy5E2Ub)" class="zp0o58pil"/></g><g filter="url(#iRDm5BP)"><path fill="url(#iQrqwid)" class="s5p0jt_2h"/><path fill="url(#iPvM35b)" class="s5p0jt_2h"/></g><g filter="url(#i1Errld)"><path class="xk654sehy"/><path fill="url(#iAMmTCs)" class="fku5dkblk"/></g><g filter="url(#iDgIGsd)"><path class="m5pz4_bjh"/><path fill="url(#iEeqWye)" class="ua_x0bb_u"/></g><g filter="url(#iKaSQdc)"><path fill="url(#iwwGVRc)" class="is46jlpxt"/><path fill="url(#iN4U6ie)" class="is46jlpxt"/><path fill="url(#iUz3Gwb)" class="is46jlpxt"/><path fill="url(#i6iByIc)" class="is46jlpxt"/><path fill="url(#iX91lub)" class="is46jlpxt"/><path fill="url(#icJZXze)" class="is46jlpxt"/></g><path fill="url(#iwoRGkb)" class="is46jlpxt"/><path fill="url(#iV4hLgc)" class="is46jlpxt"/><path fill="url(#izH2J0b)" class="is46jlpxt"/><g filter="url(#ikp0ikd)"><path class="mkxkbksmb"/></g><g filter="url(#iQuS7kY)"><path class="xvchkzb4d"/><path fill="url(#i6T9lKc)" class="gl190kz1y"/><path fill="url(#iRyqVlb)" class="gl190kz1y"/><path fill="url(#ivCza0c)" class="gl190kz1y"/><path fill="url(#iaipiVd)" class="gl190kz1y"/></g><g filter="url(#iTmQZOc)"><path stroke="url(#iVO9ryc)" class="lkp5p8bgu"/></g><path class="t8je_6qbh"/><g filter="url(#iYtOu2b)"><path class="znnnwod6o"/><path fill="url(#iURDzId)" class="s20jr_bro"/></g><g filter="url(#iOkMX2C)"><path class="jwj9mobso"/><path fill="url(#i9Y5TSc)" class="w212xwb1h"/><path fill="url(#idoQ1wb)" class="w212xwb1h"/></g><g filter="url(#ibSDoWb)"><path stroke="url(#iMpfqrm)" class="qww1g7b4f"/></g><g filter="url(#iph2HCe)"><path class="q726rgbgc"/></g><path fill="url(#i9P1uFc)" class="r22hnp7ou"/><path fill="url(#izOPDwb)" class="ncc0lbcfj"/><g filter="url(#iAMSdLb)" class="tryqaac1t"><path stroke="url(#iFC2Wjt)" class="ns7l0dbhs"/><path stroke="url(#ijtZHQe)" class="ns7l0dbhs"/></g><g filter="url(#iGd3yKe)" class="tryqaac1t"><path stroke="url(#iyFuZLy)" class="a5ensbcze"/><path stroke="url(#iTF1pAc)" class="a5ensbcze"/></g><g filter="url(#i09vhfe)"><path fill="url(#iU01JLq)" class="lrxagac4l"/></g><g filter="url(#i3lI8fc)"><path fill="url(#iJk3cMc)" class="m1u4bsjqr"/></g><g filter="url(#iQ97CBY)"><path clip-rule="evenodd" class="o88b13bjp"/></g><g filter="url(#igsGZWW)"><path class="eyf6cek9z"/></g><g filter="url(#iLvnMtb)"><path class="qz7bmgb4x"/></g><g filter="url(#i5XfFVA)"><path class="y8_rm488v"/></g><path class="umj075h7d"/><path fill="url(#ifEbLjb)" class="p3henobog"/><path fill="url(#iIoJDMe)" class="p3henobog"/><path fill="url(#iMjybJB)" class="p3henobog"/><path fill="url(#ihXBBTd)" class="p3henobog"/><path fill="url(#iqjXkZd)" class="p3henobog"/><path fill="url(#iUwxFXW)" class="p3henobog"/><path fill="url(#iTInKRb)" class="p3henobog"/><g filter="url(#iIP26kd)"><path fill="url(#iEU9L4c)" class="ih6scz3jp"/><path fill="url(#iIDMlib)" class="ih6scz3jp"/><path fill="url(#iTbgzRr)" class="ih6scz3jp"/></g><path fill="url(#iMlRNEb)" class="ydc3b1bgo"/><path fill="url(#iPLv6xb)" class="ydc3b1bgo"/><g filter="url(#i2EG15c)"><path fill="url(#iFiTdqd)" class="o-2hudmmt"/><path fill="url(#iAYuGMM)" class="o-2hudmmt"/></g><g filter="url(#iijoMXt)"><path class="e1ab2kbci"/><path fill="url(#iLs7bwd)" class="f-dbmsh9h"/><path fill="url(#iajjibe)" class="f-dbmsh9h"/></g><path fill="url(#iDkE4fe)" class="bfolokb0w"/><path fill="url(#ijEw0nb)" class="bfolokb0w"/><path fill="url(#i0onjwk)" class="jl5bjg5-e"/><path fill="url(#iLAz8tc)" class="jl5bjg5-e"/><path fill="url(#iVCSkFe)" class="ohw562bgk"/><path fill="url(#iOtVe5t)" class="ohw562bgk"/><path fill="url(#iytfxJb)" class="ohw562bgk"/><path fill="url(#iKZHdhe)" class="ohw562bgk"/><path fill="url(#iUXxjMd)" class="ohw562bgk"/><path fill="url(#ieuU50d)" class="ngosmac8t"/><path fill="url(#iPuFT0b)" class="r7lliibxj"/><path fill="url(#iU7hnNd)" class="r7lliibxj"/><path fill="url(#i89JGAq)" class="r7lliibxj"/><g filter="url(#ihp3ouc)"><path stroke="url(#iZqCCJd)" class="fnb8ugtoc"/></g><path fill="url(#igZzSle)" class="aqgcprbjk"/><path fill="url(#iPgqlKc)" class="aqgcprbjk"/><path fill="url(#innNaWd)" class="spm60ki7k"/><g filter="url(#if29Mwc)"><path fill="url(#iNgx9mb)" class="a20_60b_h"/><path fill="url(#iRvOyec)" class="a20_60b_h"/><path fill="url(#iI2Utbe)" class="a20_60b_h"/></g><path fill="url(#iEuTX6X)" class="moemzebdy"/><path fill="url(#ik7x9Jc)" class="moemzebdy"/><path fill="url(#iWmqh4c)" class="moemzebdy"/><path fill="url(#iFmbfte)" class="moemzebdy"/><path class="gpb_s4bfh"/><path fill="url(#i8ZFbhc)" class="nhvcqmwuq"/><path fill="url(#ia08m0b)" class="nhvcqmwuq"/><path class="hgbgo3h5d"/><path fill="url(#iO4PjQc)" class="quizolb0d"/><path fill="url(#iF9Yccb)" class="quizolb0d"/><path fill="url(#iKeoR4b)" class="quizolb0d"/><path fill="url(#iNftAHe)" class="iz0cumb_r"/><path fill="url(#iVXOFbc)" class="iz0cumb_r"/><path fill="url(#icnnAUc)" class="iz0cumb_r"/><path fill="url(#iug67cd)" class="k-tvti7jd"/><path fill="url(#ib6TxSy)" class="k-tvti7jd"/><path fill="url(#ia12Yud)" class="k-tvti7jd"/><path fill="url(#ifQq1ad)" class="e5ac5xbai"/><path fill="url(#iQE43ee)" class="e5ac5xbai"/><path fill="url(#ibLd5pb)" class="e5ac5xbai"/><path fill="url(#i8hrI5f)" class="e5ac5xbai"/><g filter="url(#ihfScue)"><path stroke="url(#i7wsdHe)" class="hbprp_aru"/></g><g filter="url(#iW2TYGG)" class="mc2zb0bvp"><path class="grcmvub8x"/></g><g filter="url(#igenHtc)" class="mc2zb0bvp"><path class="f4arcyb6u"/></g><defs><radialGradient id="iSVaKWc" cx="0" cy="0" r="1" gradientTransform="matrix(.28392 4.67825 -5.84409 .35468 14.492 13.082)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="ii7i7ib" cx="0" cy="0" r="1" gradientTransform="rotate(134.992 2.985 9.379)scale(3.54394 4.65646)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iBe6Npd" cx="0" cy="0" r="1" gradientTransform="rotate(116.393 1.129 8.79)scale(2.19344 1.68426)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="ihZb7dl" cx="0" cy="0" r="1" gradientTransform="matrix(-.87995 2.36398 -1.6652 -.61985 9.562 9.569)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="i5tZzxe" cx="0" cy="0" r="1" gradientTransform="matrix(1.88398 2.34817 -3.25962 2.61525 9.217 3.145)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="izPf4de" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1613 1.72262 -2.40733 -1.62291 18.978 3.403)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iAzeJrr" cx="0" cy="0" r="1" gradientTransform="matrix(-1.73994 .89547 -1.86744 -3.6285 21.653 8.208)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iNurDGe" cx="0" cy="0" r="1" gradientTransform="rotate(154.951 9.553 8.285)scale(2.95804 3.7681)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iQUIUdc" cx="0" cy="0" r="1" gradientTransform="rotate(-119.856 11.029 -2.17)scale(2.85394 2.2573)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="ia8Z2lb" cx="0" cy="0" r="1" gradientTransform="matrix(1.53519 -.13497 .21869 2.48746 7.99 10.83)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="i9zNRGW" cx="0" cy="0" r="1" gradientTransform="matrix(-.33014 2.95725 -2.72602 -.30432 7.9 7.64)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="gcrmpdfop"/><stop offset="1" class="nd--cppfl"/></radialGradient><radialGradient id="i3Memdb" cx="0" cy="0" r="1" gradientTransform="matrix(2.19471 3.52472 -6.20084 3.86104 16.045 15.48)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="wcbvx-n_a"/><stop offset="1" class="sbx2zkbbn"/></radialGradient><radialGradient id="iQrqwid" cx="0" cy="0" r="1" gradientTransform="matrix(2.26973 -1.61638 1.97352 2.77123 18.434 10.174)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="ayiod_bfg"/><stop offset=".944" class="wb78_hxsc"/></radialGradient><radialGradient id="iPvM35b" cx="0" cy="0" r="1" gradientTransform="rotate(18.259 -14.906 63.206)scale(1.53723 .4346)" gradientUnits="userSpaceOnUse"><stop class="s9u3_wbrp"/><stop offset="1" class="crde6o_5i"/></radialGradient><radialGradient id="iAMmTCs" cx="0" cy="0" r="1" gradientTransform="matrix(1.48859 -.4063 .31761 1.16366 18.722 9.778)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="rmmi4abgs"/><stop offset="1" class="xuyenabum"/></radialGradient><radialGradient id="iEeqWye" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20726 .23493 -.18533 -.95238 9.704 11.417)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="pj2ff5nxp"/><stop offset="1" class="sdufqstmc"/></radialGradient><radialGradient id="iwwGVRc" cx="0" cy="0" r="1" gradientTransform="rotate(144.232 7.01 7.466)scale(7.29883 9.76935)" gradientUnits="userSpaceOnUse"><stop offset=".134" class="zpqiekbmq"/><stop offset=".868" class="v2xpqhbrh"/></radialGradient><radialGradient id="iN4U6ie" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84823 1.36757 -.95235 -1.28708 16.194 10.47)" gradientUnits="userSpaceOnUse"><stop class="o3k0towjz"/><stop offset="1" class="x7h3p2bdy"/></radialGradient><radialGradient id="iUz3Gwb" cx="0" cy="0" r="1" gradientTransform="matrix(.39715 -3.68636 4.6773 .5039 13.343 17.193)" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></radialGradient><radialGradient id="i6iByIc" cx="0" cy="0" r="1" gradientTransform="rotate(85.714 1.98 12.979)scale(6.9782 7.01557)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="m6mmhsf1n"/><stop offset="1" class="do3fwrbgr"/></radialGradient><radialGradient id="iX91lub" cx="0" cy="0" r="1" gradientTransform="rotate(78.988 .684 13.716)scale(6.6926 6.72844)" gradientUnits="userSpaceOnUse"><stop offset=".794" class="d0fyzsbqc"/><stop offset="1" class="n8ysctycz"/></radialGradient><radialGradient id="icJZXze" cx="0" cy="0" r="1" gradientTransform="matrix(-6.64438 2.70017 -4.64885 -11.43957 16.35 11.363)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="f6uv1pf_h"/><stop offset="1" class="fp6zmm73k"/></radialGradient><radialGradient id="iwoRGkb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28576 .2502 -1.25476 -6.44799 19.508 10.061)" gradientUnits="userSpaceOnUse"><stop class="jids0zpwm"/><stop offset="1" class="zz4mcgrzh"/></radialGradient><radialGradient id="iV4hLgc" cx="0" cy="0" r="1" gradientTransform="rotate(128.267 6.085 11.804)scale(2.45945 1.64838)" gradientUnits="userSpaceOnUse"><stop class="ybvm9tprh"/><stop offset=".694" class="yxwqgvbem"/></radialGradient><radialGradient id="izH2J0b" cx="0" cy="0" r="1" gradientTransform="rotate(138.52 6.724 6.166)scale(3.23511 2.254)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="k7xyk1boq"/><stop offset="1" class="zpi5yt9_e"/></radialGradient><radialGradient id="i6T9lKc" cx="0" cy="0" r="1" gradientTransform="matrix(-.85362 -1.9561 .60286 -.26308 15.41 11.728)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="x_sue_b_g"/><stop offset="1" class="gl9okfban"/></radialGradient><radialGradient id="iaipiVd" cx="0" cy="0" r="1" gradientTransform="matrix(-.7797 .15173 -.04242 -.21798 15.212 11.986)" gradientUnits="userSpaceOnUse"><stop class="t5djkhb4t"/><stop offset="1" class="qm132ccsa"/></radialGradient><radialGradient id="iURDzId" cx="0" cy="0" r="1" gradientTransform="rotate(-76.404 9.716 -.706)scale(3.0887 1.5801)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="i9Y5TSc" cx="0" cy="0" r="1" gradientTransform="rotate(104.671 6.48 6.775)scale(4.96617 8.1194)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="idoQ1wb" cx="0" cy="0" r="1" gradientTransform="rotate(87.734 5.003 8.248)scale(1.40976 3.03302)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="ijtZHQe" cx="0" cy="0" r="1" gradientTransform="matrix(-.10984 .20681 -.19975 -.10609 17.267 9.516)" gradientUnits="userSpaceOnUse"><stop class="m-leh6bjs"/><stop offset="1" class="ka236wzgl"/></radialGradient><radialGradient id="iTF1pAc" cx="0" cy="0" r="1" gradientTransform="matrix(-.10984 .20681 -.19975 -.10609 13.04 10.386)" gradientUnits="userSpaceOnUse"><stop class="m-leh6bjs"/><stop offset="1" class="ka236wzgl"/></radialGradient><radialGradient id="iMjybJB" cx="0" cy="0" r="1" gradientTransform="matrix(.28711 3.40925 -4.12958 .34777 8.64 20.596)" gradientUnits="userSpaceOnUse"><stop offset=".604" class="v442oubmz"/><stop offset="1" class="p_ew-572a"/></radialGradient><radialGradient id="ihXBBTd" cx="0" cy="0" r="1" gradientTransform="matrix(-.75 3.4375 -2.71722 -.59285 6.39 19.315)" gradientUnits="userSpaceOnUse"><stop offset=".518" class="m0rm-m-qv"/><stop offset="1" class="wi8a08bum"/></radialGradient><radialGradient id="iqjXkZd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15508 -.34883 1.8893 -6.25609 8.598 29.97)" gradientUnits="userSpaceOnUse"><stop class="wagk6dfaq"/><stop offset="1" class="hfzkti_ts"/></radialGradient><radialGradient id="iTInKRb" cx="0" cy="0" r="1" gradientTransform="matrix(.1168 1.84919 -2.9447 .18598 8.846 21.8)" gradientUnits="userSpaceOnUse"><stop offset=".6" class="k5vtewq9k"/><stop offset="1" class="z1zjblq2q"/></radialGradient><radialGradient id="iEU9L4c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.0785 6 -4.46735 -1.54757 16.937 24.752)" gradientUnits="userSpaceOnUse"><stop class="v2wkn2ras"/><stop offset="1" class="yxmxw0ard"/></radialGradient><radialGradient id="iIDMlib" cx="0" cy="0" r="1" gradientTransform="rotate(-132.901 14.855 10.13)scale(4.22338 6.72611)" gradientUnits="userSpaceOnUse"><stop class="bji58ac7a"/><stop offset="1" class="eqapwmsga"/></radialGradient><radialGradient id="iTbgzRr" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62501 -3.8277 2.0945 -1.4364 21.109 25.689)" gradientUnits="userSpaceOnUse"><stop offset=".393" class="c8r1g2bnk"/><stop offset="1" class="kyl8adb5j"/></radialGradient><radialGradient id="iMlRNEb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.34372 2.81254 -2.95164 -5.608 26.328 21.033)" gradientUnits="userSpaceOnUse"><stop class="z3zsa5bpu"/><stop offset="1" class="c_p6lvbtv"/></radialGradient><radialGradient id="iFiTdqd" cx="0" cy="0" r="1" gradientTransform="rotate(164.954 9.06 12.707)scale(3.00943 4.47011)" gradientUnits="userSpaceOnUse"><stop class="dyh_p3bsl"/><stop offset="1" class="acgtzjb8q"/></radialGradient><radialGradient id="iAYuGMM" cx="0" cy="0" r="1" gradientTransform="matrix(-1.66156 -1.3125 1.73451 -2.1958 22.802 25.47)" gradientUnits="userSpaceOnUse"><stop class="fo4qq4q_b"/><stop offset="1" class="a6ayzxb8w"/></radialGradient><radialGradient id="iLs7bwd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -5.73004 19.265 28.909)" gradientUnits="userSpaceOnUse"><stop offset=".083" class="bamcey7be"/><stop offset="1" class="a-744r8ne"/></radialGradient><radialGradient id="iajjibe" cx="0" cy="0" r="1" gradientTransform="rotate(33.14 -37.767 40.417)scale(2.25791 .79383)" gradientUnits="userSpaceOnUse"><stop class="afa21ukyb"/><stop offset="1" class="sozlwmb1o"/></radialGradient><radialGradient id="iDkE4fe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.02344 -.68462 0 19.607 27.99)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="rntqzsbvm"/><stop offset="1" class="kn6547brm"/></radialGradient><radialGradient id="iLAz8tc" cx="0" cy="0" r="1" gradientTransform="matrix(-8.5625 1.81252 -.47277 -2.23342 29.083 26.443)" gradientUnits="userSpaceOnUse"><stop class="o7yf4tl0b"/><stop offset="1" class="x9s6ceaht"/></radialGradient><radialGradient id="iVCSkFe" cx="0" cy="0" r="1" gradientTransform="matrix(.84205 2.73 -2.93117 .9041 6.765 19.846)" gradientUnits="userSpaceOnUse"><stop class="h0nz-rbjw"/><stop offset="1" class="kfbnffbzx"/></radialGradient><radialGradient id="iytfxJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.74998 1.96876 -2.0196 -.76935 8.38 20.27)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="jz746dbzd"/><stop offset="1" class="dzs1febsk"/></radialGradient><radialGradient id="iKZHdhe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 .87171 -.46263 -.67998 9.906 20.818)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="cwu2h0blp"/><stop offset="1" class="f9-tluqmj"/></radialGradient><radialGradient id="iUXxjMd" cx="0" cy="0" r="1" gradientTransform="matrix(.32031 .75 -.43392 .18532 7.163 20.455)" gradientUnits="userSpaceOnUse"><stop offset=".827" class="yyn9swbvh"/><stop offset="1" class="pviihufyn"/></radialGradient><radialGradient id="i89JGAq" cx="0" cy="0" r="1" gradientTransform="matrix(-.3711 1.25391 -.1532 -.04534 16.01 18.446)" gradientUnits="userSpaceOnUse"><stop class="tomvu1bgl"/><stop offset="1" class="sinn-3bvk"/></radialGradient><radialGradient id="iZqCCJd" cx="0" cy="0" r="1" gradientTransform="matrix(-.20313 -.60156 1.71998 -.58078 9.312 22.987)" gradientUnits="userSpaceOnUse"><stop class="ut4bgvb0y"/><stop offset="1" class="gngaedcou"/></radialGradient><radialGradient id="iPgqlKc" cx="0" cy="0" r="1" gradientTransform="matrix(-.64063 2 -.16496 -.05284 15.822 17.786)" gradientUnits="userSpaceOnUse"><stop class="njdbcpw8w"/><stop offset="1" class="p6n8nbb9p"/></radialGradient><radialGradient id="iRvOyec" cx="0" cy="0" r="1" gradientTransform="rotate(25.805 -34.596 34.24)scale(1.57936 1.44294)" gradientUnits="userSpaceOnUse"><stop offset=".127" class="l8v5z5bog"/><stop offset="1" class="ll6ec2bpd"/></radialGradient><radialGradient id="ik7x9Jc" cx="0" cy="0" r="1" gradientTransform="rotate(53.038 -14.25 16.79)scale(3.87188 5.62527)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="zm6geub_u"/><stop offset="1" class="lrce32g5i"/></radialGradient><radialGradient id="iWmqh4c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.82813 3.21874 -1.86644 -1.06007 10.124 17.533)" gradientUnits="userSpaceOnUse"><stop offset=".289" class="eg892dbvw"/><stop offset="1" class="lq414ub4c"/></radialGradient><radialGradient id="iFmbfte" cx="0" cy="0" r="1" gradientTransform="matrix(-.1359 3.04807 -.73147 -.03261 7.274 18.087)" gradientUnits="userSpaceOnUse"><stop class="ny_jxsr8o"/><stop offset="1" class="s5w7sgqdm"/></radialGradient><radialGradient id="i8ZFbhc" cx="0" cy="0" r="1" gradientTransform="matrix(-.97119 .31036 -.1504 -.47062 14.299 16.422)" gradientUnits="userSpaceOnUse"><stop class="kaydztigo"/><stop offset="1" class="ojt9l7bfl"/></radialGradient><radialGradient id="ia08m0b" cx="0" cy="0" r="1" gradientTransform="matrix(.125 -.9375 3.91226 .52164 12.627 17.5)" gradientUnits="userSpaceOnUse"><stop offset=".2" class="i4p54obux"/><stop offset="1" class="z44v3-bta"/></radialGradient><radialGradient id="iO4PjQc" cx="0" cy="0" r="1" gradientTransform="matrix(.18995 -.92273 4.1369 .8516 12.109 18.876)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="bamcey7be"/><stop offset="1" class="a-744r8ne"/></radialGradient><radialGradient id="iF9Yccb" cx="0" cy="0" r="1" gradientTransform="rotate(-171.743 6.497 8.413)scale(2.12166 2.39641)" gradientUnits="userSpaceOnUse"><stop offset=".655" class="dto0_ubls"/><stop offset=".907" class="t-pst_b0z"/></radialGradient><radialGradient id="iKeoR4b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 .41406 -.20022 -.51377 13.814 17.492)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="k35cj8b6j"/><stop offset="1" class="kdyinjb2g"/></radialGradient><radialGradient id="iNftAHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.60938 .84374 -2.96419 -2.14083 11.374 18.861)" gradientUnits="userSpaceOnUse"><stop offset=".243" class="fus102bkw"/><stop offset="1" class="d_o4p9bes"/></radialGradient><radialGradient id="iVXOFbc" cx="0" cy="0" r="1" gradientTransform="matrix(2.3789 1.48047 -.66284 1.0651 11.28 18.972)" gradientUnits="userSpaceOnUse"><stop class="q_yfvabjb"/><stop offset="1" class="bxxfcfh8v"/></radialGradient><radialGradient id="icnnAUc" cx="0" cy="0" r="1" gradientTransform="matrix(-.3672 .53142 -1.08325 -.74848 12.062 18.767)" gradientUnits="userSpaceOnUse"><stop offset=".139" class="ikgl8m1ug"/><stop offset="1" class="qj5edhacv"/></radialGradient><radialGradient id="iug67cd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33928 1.42858 -2.02518 -1.89858 10.868 19.555)" gradientUnits="userSpaceOnUse"><stop class="gn724k1ul"/><stop offset="1" class="vgekv3bdy"/></radialGradient><radialGradient id="ib6TxSy" cx="0" cy="0" r="1" gradientTransform="matrix(1.65625 -.875 1.67102 3.163 8.203 21.08)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="ex769achu"/><stop offset="1" class="e7foweb5i"/></radialGradient><radialGradient id="ia12Yud" cx="0" cy="0" r="1" gradientTransform="matrix(1.20313 .67188 -.27198 .48704 10.72 20.172)" gradientUnits="userSpaceOnUse"><stop class="cn3fn4-mf"/><stop offset="1" class="dzll2bclm"/></radialGradient><radialGradient id="iQE43ee" cx="0" cy="0" r="1" gradientTransform="rotate(105.675 1.043 15.784)scale(1.31451 .34383)" gradientUnits="userSpaceOnUse"><stop class="cn05xwrkd"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="ibLd5pb" cx="0" cy="0" r="1" gradientTransform="rotate(105.036 .926 16.26)scale(.54206 .1592)" gradientUnits="userSpaceOnUse"><stop class="em3lc9y5i"/><stop offset="1" class="k_pdrlblj"/><stop offset="1" class="n8jici3hn"/></radialGradient><radialGradient id="i8hrI5f" cx="0" cy="0" r="1" gradientTransform="rotate(174.906 8.355 10.277)scale(.43997 .38553)" gradientUnits="userSpaceOnUse"><stop class="tzj34xnjq"/><stop offset="1" class="ugbytbngn"/></radialGradient><radialGradient id="i7wsdHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.26365 -2.21465 3.37212 -.40144 7.768 21.786)" gradientUnits="userSpaceOnUse"><stop class="zbwshaccu"/><stop offset="1" class="piz2rbc3b"/></radialGradient><linearGradient id="iElis9b" x1="17.649" x2="13.295" y1="2.653" y2="16.587" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="iTw5V3V" x1="19.224" x2="12.336" y1="18.575" y2="30.252" gradientUnits="userSpaceOnUse"><stop class="q9xywcr7e"/><stop offset="1" class="jvlxembhy"/></linearGradient><linearGradient id="iN3Iqzk" x1="15.685" x2="17.218" y1="17.205" y2="18.19" gradientUnits="userSpaceOnUse"><stop offset=".103" class="nhce3bcqg"/><stop offset="1" class="p75tg79fv"/></linearGradient><linearGradient id="iy5E2Ub" x1="8.027" x2="10.988" y1="11.834" y2="11.258" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="qenr6bbwz"/></linearGradient><linearGradient id="iRyqVlb" x1="13.701" x2="14.64" y1="12.136" y2="11.953" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="ivCza0c" x1="14.795" x2="14.676" y1="12.752" y2="12.142" gradientUnits="userSpaceOnUse"><stop class="cctx1cb1y"/><stop offset="1" class="xfmbn4_bb"/></linearGradient><linearGradient id="iVO9ryc" x1="14.081" x2="14.404" y1="14.527" y2="13.725" gradientUnits="userSpaceOnUse"><stop class="w1_1yhbve"/><stop offset=".663" class="zbexf6jod"/></linearGradient><linearGradient id="iMpfqrm" x1="10.208" x2="11.001" y1="4.884" y2="6.052" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="i9P1uFc" x1="17.174" x2="15.715" y1="9.864" y2="10.703" gradientUnits="userSpaceOnUse"><stop offset=".558" class="incjljb4q"/><stop offset="1" class="j9v6w1g-o"/></linearGradient><linearGradient id="izOPDwb" x1="12.919" x2="11.456" y1="10.742" y2="11.578" gradientUnits="userSpaceOnUse"><stop offset=".558" class="incjljb4q"/><stop offset="1" class="j9v6w1g-o"/></linearGradient><linearGradient id="iFC2Wjt" x1="15.245" x2="17.466" y1="10.028" y2="10.101" gradientUnits="userSpaceOnUse"><stop class="m-leh6bjs"/><stop offset="1" class="ka236wzgl"/></linearGradient><linearGradient id="iyFuZLy" x1="11.019" x2="13.241" y1="10.899" y2="10.972" gradientUnits="userSpaceOnUse"><stop class="m-leh6bjs"/><stop offset="1" class="ka236wzgl"/></linearGradient><linearGradient id="iU01JLq" x1="12.886" x2="10.92" y1="9.708" y2="9.5" gradientUnits="userSpaceOnUse"><stop offset=".329" class="t4dyfpxnt"/><stop offset="1" class="hkxvz0u3y"/></linearGradient><linearGradient id="iJk3cMc" x1="17.278" x2="13.931" y1="9.056" y2="8.077" gradientUnits="userSpaceOnUse"><stop offset=".329" class="sexb1etbn"/><stop offset="1" class="ct55v9jwv"/></linearGradient><linearGradient id="ifEbLjb" x1="9.109" x2="3.64" y1="26.283" y2="24.815" gradientUnits="userSpaceOnUse"><stop class="g1c-6jb6y"/><stop offset="1" class="hkdf97w8c"/></linearGradient><linearGradient id="iIoJDMe" x1="3.333" x2="5.328" y1="25.911" y2="26.565" gradientUnits="userSpaceOnUse"><stop class="da95trp0k"/><stop offset="1" class="feoz1vgta"/></linearGradient><linearGradient id="iUwxFXW" x1="9.229" x2="8.836" y1="28.301" y2="28.176" gradientUnits="userSpaceOnUse"><stop class="rehc034in"/><stop offset="1" class="psvt8ubmu"/></linearGradient><linearGradient id="iPLv6xb" x1="24.609" x2="24.296" y1="25.315" y2="23.846" gradientUnits="userSpaceOnUse"><stop class="dy155dxdg"/><stop offset="1" class="dypnkmnss"/></linearGradient><linearGradient id="ijEw0nb" x1="19.395" x2="19.395" y1="26.604" y2="27.442" gradientUnits="userSpaceOnUse"><stop class="y-ymn0bhn"/><stop offset="1" class="he69lvb0i"/></linearGradient><linearGradient id="i0onjwk" x1="26.546" x2="26.984" y1="26.752" y2="30.471" gradientUnits="userSpaceOnUse"><stop class="tnk2b_bjh"/><stop offset="1" class="p40qzpbtf"/></linearGradient><linearGradient id="iOtVe5t" x1="5.833" x2="6.912" y1="19.724" y2="21.427" gradientUnits="userSpaceOnUse"><stop class="j4n7g28_w"/><stop offset="1" class="laie_nbgc"/></linearGradient><linearGradient id="ieuU50d" x1="12.351" x2="11.964" y1="20.234" y2="18.252" gradientUnits="userSpaceOnUse"><stop class="fu3c0cblo"/><stop offset="1" class="pdon63boo"/></linearGradient><linearGradient id="iPuFT0b" x1="16.078" x2="15.296" y1="18.033" y2="21.019" gradientUnits="userSpaceOnUse"><stop class="e6bcurcdv"/><stop offset="1" class="jxwnoqbqn"/></linearGradient><linearGradient id="iU7hnNd" x1="15.205" x2="15.428" y1="21.239" y2="20.348" gradientUnits="userSpaceOnUse"><stop class="w_57dfb5m"/><stop offset="1" class="t78i98bfv"/></linearGradient><linearGradient id="igZzSle" x1="14.953" x2="13.828" y1="17.268" y2="21.596" gradientUnits="userSpaceOnUse"><stop class="nn3wh7bnm"/><stop offset="1" class="tbs366q3s"/></linearGradient><linearGradient id="innNaWd" x1="15.265" x2="14.156" y1="17.643" y2="17.283" gradientUnits="userSpaceOnUse"><stop class="h94nvm15h"/><stop offset="1" class="qtvy6rbzh"/></linearGradient><linearGradient id="iNgx9mb" x1="14.453" x2="13.223" y1="17.158" y2="21.908" gradientUnits="userSpaceOnUse"><stop class="qic_n_blg"/><stop offset="1" class="qh-ows9fr"/></linearGradient><linearGradient id="iI2Utbe" x1="12.549" x2="12.768" y1="20.974" y2="19.896" gradientUnits="userSpaceOnUse"><stop class="e122-lbju"/><stop offset="1" class="grqmao4rm"/></linearGradient><linearGradient id="iEuTX6X" x1="8.421" x2="8.964" y1="16.658" y2="21.158" gradientUnits="userSpaceOnUse"><stop class="gnkeuhb_f"/><stop offset="1" class="vkqqj1b4e"/></linearGradient><linearGradient id="ifQq1ad" x1="16.521" x2="15.937" y1="18.534" y2="21.034" gradientUnits="userSpaceOnUse"><stop class="neym138jd"/><stop offset="1" class="kmp3a3cnr"/></linearGradient><filter id="iYcx0Jb" width="16.038" height="16.732" x="6.729" y="1.178" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3533"/></filter><filter id="iKcnFQd" width="3.43" height="3.28" x="7.98" y="9.793" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.266667 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3533"/></filter><filter id="iRDm5BP" width="3.28" height="3.53" x="17.496" y="7.691" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.0901961 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3533"/></filter><filter id="i1Errld" width="3.19" height="3.19" x="17.542" y="7.986" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3533" stdDeviation=".25"/></filter><filter id="iDgIGsd" width="2.69" height="2.69" x="8.294" y="10.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3533" stdDeviation=".125"/></filter><filter id="iKaSQdc" width="10.777" height="10.622" x="8.819" y="6.126" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.14902 0 0 0 0 0.0901961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3533"/></filter><filter id="ikp0ikd" width="2.898" height="3.79" x="13.088" y="9.628" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3533" stdDeviation=".25"/></filter><filter id="iQuS7kY" width="2.398" height="3.278" x="13.474" y="9.719" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3533" stdDeviation=".125"/></filter><filter id="iTmQZOc" width="3.708" height="1.857" x="13.129" y="12.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3533" stdDeviation=".05"/></filter><filter id="iYtOu2b" width="4.187" height="5.251" x="7.062" y="4.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3533"/><feGaussianBlur result="effect2_foregroundBlur_4002_3533" stdDeviation=".25"/></filter><filter id="iOkMX2C" width="9.539" height="4.738" x="9.872" y="2.595" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3533"/><feGaussianBlur result="effect2_foregroundBlur_4002_3533" stdDeviation=".125"/></filter><filter id="ibSDoWb" width="1.478" height="2.204" x="9.841" y="4.24" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3533" stdDeviation=".1"/></filter><filter id="iph2HCe" width="6.673" height="3.382" x="12.818" y="3.827" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3533" stdDeviation=".375"/></filter><filter id="iAMSdLb" width="2.466" height="1.243" x="15.133" y="9.206" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3533" stdDeviation=".075"/></filter><filter id="iGd3yKe" width="2.466" height="1.243" x="10.907" y="10.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3533" stdDeviation=".075"/></filter><filter id="i09vhfe" width="3.782" height="2.458" x="10.137" y="8.286" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3533" stdDeviation=".3"/></filter><filter id="i3lI8fc" width="3.575" height="2.665" x="14.681" y="7.309" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3533" stdDeviation=".3"/></filter><filter id="iQ97CBY" width="2.526" height=".901" x="15.459" y="7.201" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3533"/></filter><filter id="igsGZWW" width="2.328" height=".771" x="15.486" y="7.321" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3533" stdDeviation=".1"/></filter><filter id="iLvnMtb" width="2.401" height="1.403" x="10.102" y="8.075" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3533"/></filter><filter id="i5XfFVA" width="2.194" height="1.269" x="10.099" y="8.207" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3533" stdDeviation=".1"/></filter><filter id="iIP26kd" width="11.192" height="8.359" x="11.466" y="21.861" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.607843 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3533"/></filter><filter id="i2EG15c" width="7.407" height="8.444" x="19.048" y="18.69" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 0.45098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3533"/></filter><filter id="iijoMXt" width="8.208" height="4.667" x="12.416" y="25.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.129412 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3533"/></filter><filter id="ihp3ouc" width="3.456" height="1.701" x="7.381" y="21.775" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3533" stdDeviation=".1"/></filter><filter id="if29Mwc" width="4.309" height="4.662" x="11.043" y="16.436" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.533333 0 0 0 0 0.552941 0 0 0 0 0.619608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3533"/></filter><filter id="ihfScue" width="3.647" height="2.753" x="6.263" y="19.521" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3533" stdDeviation=".05"/></filter><filter id="iW2TYGG" width="2.634" height="2.141" x="16.374" y="25.761" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3533" stdDeviation=".125"/></filter><filter id="igenHtc" width="4.536" height="1" x="12.746" y="28.567" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3533" stdDeviation=".15"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-feeding-baby-dark" /></template>
<style>
.a-744r8ne {
  stop-color: var(--svg-color--2d1517, #2D1517);
  stop-opacity: 0;
}

.a20_60b_h {
  d: path("m12.167 16.436l2.635.734c.357.104.645.406.521.797l-.779 2.704c-.096.329-.442.504-.851.393l-2.6-.733z");
}

.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a5ensbcze {
  d: path("M11.157 10.808c.129.112.505.318.983.249c.478-.07.882-.55.984-.73");
}

.a6ayzxb8w {
  stop-color: var(--svg-color--289d47, #289D47);
  stop-opacity: 0;
}

.acgtzjb8q {
  stop-color: var(--svg-color--3ba055, #3BA055);
}

.afa21ukyb {
  stop-color: var(--svg-color--2f2127, #2F2127);
}

.aqgcprbjk {
  d: path("m11.939 16.005l3.172.884c.43.125.744.558.627.96l-.9 3.086c-.115.396-.532.606-1.024.473l-3.129-.883z");
}

.ayiod_bfg {
  stop-color: var(--svg-color--493033, #493033);
}

.bamcey7be {
  stop-color: var(--svg-color--2d1517, #2D1517);
}

.bfolokb0w {
  d: path("M18.998 26.754a.15.15 0 0 1 .15-.15h.643v3.367h-.793z");
}

.bji58ac7a {
  stop-color: var(--svg-color--208d47, #208D47);
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bxxfcfh8v {
  stop-color: var(--svg-color--462e2a, #462E2A);
  stop-opacity: 0;
}

.c_p6lvbtv {
  stop-color: var(--svg-color--31be7d, #31BE7D);
}

.c8r1g2bnk {
  stop-color: var(--svg-color--148c3e, #148C3E);
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cctx1cb1y {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.cn05xwrkd {
  stop-color: var(--svg-color--fed466, #FED466);
}

.cn3fn4-mf {
  stop-color: var(--svg-color--685655, #685655);
}

.crde6o_5i {
  stop-color: var(--svg-color--402824, #402824);
  stop-opacity: 0;
}

.ct55v9jwv {
  stop-color: var(--svg-color--472b2b, #472B2B);
  stop-opacity: 0;
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cwu2h0blp {
  stop-color: var(--svg-color--6b3d8e, #6B3D8E);
}

.d_o4p9bes {
  stop-color: var(--svg-color--3c2626, #3C2626);
}

.d0fyzsbqc {
  stop-color: var(--svg-color--3b232b, #3B232B);
  stop-opacity: 0;
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.da95trp0k {
  stop-color: var(--svg-color--8f73b3, #8F73B3);
}

.do3fwrbgr {
  stop-color: var(--svg-color--3f243b, #3F243B);
}

.dto0_ubls {
  stop-color: var(--svg-color--422e2b, #422E2B);
  stop-opacity: 0;
}

.dy155dxdg {
  stop-color: var(--svg-color--33c966, #33C966);
}

.dyh_p3bsl {
  stop-color: var(--svg-color--279f64, #279F64);
}

.dypnkmnss {
  stop-color: var(--svg-color--33c966, #33C966);
  stop-opacity: 0;
}

.dzll2bclm {
  stop-color: var(--svg-color--685655, #685655);
  stop-opacity: 0;
}

.dzs1febsk {
  stop-color: var(--svg-color--6f409a, #6F409A);
  stop-opacity: 0;
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e122-lbju {
  stop-color: var(--svg-color--8b72aa, #8B72AA);
}

.e1ab2kbci {
  fill: var(--svg-color--412526, #412526);
  d: path("M17.18 25.653a.937.937 0 0 0-1.12 1.498l.931.802a.1.1 0 0 1-.063.175l-3.644.072a.886.886 0 0 0 .018 1.771h6.06v-1l1.062-1.226z");
}

.e5ac5xbai {
  d: path("m15.454 20.737l.227.068a.5.5 0 0 0 .492-.12l.363-.353a.13.13 0 0 1 .128-.033l.315.084a.484.484 0 0 0 .253-.935l-.304-.083a.13.13 0 0 1-.097-.109l-.069-.44a.5.5 0 0 0-.36-.403l-.26-.072z");
}

.e6bcurcdv {
  stop-color: var(--svg-color--6cd9f5, #6CD9F5);
}

.e7foweb5i {
  stop-color: var(--svg-color--382028, #382028);
  stop-opacity: 0;
}

.eg892dbvw {
  stop-color: var(--svg-color--412c2a, #412C2A);
}

.em3lc9y5i {
  stop-color: var(--svg-color--fed064, #FED064);
}

.eqapwmsga {
  stop-color: var(--svg-color--208d47, #208D47);
  stop-opacity: 0;
}

.ex769achu {
  stop-color: var(--svg-color--382028, #382028);
}

.eyf6cek9z {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.786 7.77c.307-.142 1.117-.258 1.728.02");
}

.f-dbmsh9h {
  d: path("M17.18 25.653a.937.937 0 0 0-1.12 1.498l.931.802a.1.1 0 0 1-.063.175l-3.644.072a.886.886 0 0 0 .018 1.771h6.06v-1l1.062-1.226z");
}

.f4arcyb6u {
  stroke: var(--svg-color--543d3f, #543D3F);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.246 29.067h3.536");
}

.f6uv1pf_h {
  stop-color: var(--svg-color--5e4543, #5E4543);
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

.fku5dkblk {
  d: path("M19.346 10.656a1.095 1.095 0 1 0-.418-2.15a1.095 1.095 0 0 0 .418 2.15");
}

.fnb8ugtoc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M7.78 23.003c.579.14 1.92.172 2.657-.828");
}

.fo4qq4q_b {
  stop-color: var(--svg-color--289d47, #289D47);
}

.fp6zmm73k {
  stop-color: var(--svg-color--5e4543, #5E4543);
}

.ft5dv1b6b {
  fill: none;
}

.fu3c0cblo {
  stop-color: var(--svg-color--f38820, #F38820);
}

.fus102bkw {
  stop-color: var(--svg-color--49302c, #49302C);
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g1c-6jb6y {
  stop-color: var(--svg-color--8a4fe4, #8A4FE4);
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gcrmpdfop {
  stop-color: var(--svg-color--585352, #585352);
}

.gl190kz1y {
  d: path("m13.928 10.334l-.201 1.805a.55.55 0 0 0 .657.598l.787-.153a.55.55 0 0 0 .384-.801l-.862-1.598c-.188-.354-.72-.25-.765.15");
}

.gl9okfban {
  stop-color: var(--svg-color--634d4b, #634D4B);
  stop-opacity: 0;
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gn724k1ul {
  stop-color: var(--svg-color--543b38, #543B38);
}

.gngaedcou {
  stop-color: var(--svg-color--8a68c3, #8A68C3);
  stop-opacity: 0;
}

.gnkeuhb_f {
  stop-color: var(--svg-color--463836, #463836);
}

.gpb_s4bfh {
  fill: var(--svg-color--432c2a, #432C2A);
  d: path("M10.099 16.432c.356.125.482.33.515.453l.446.39l2.291.363a.92.92 0 0 0 1.062-.872a.913.913 0 0 0-.922-.95c-1.175.013-2.687.035-3.044.026c-.586-.016-.793.433-.348.59");
}

.grcmvub8x {
  stroke: var(--svg-color--5e4a49, #5E4A49);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m16.874 26.26l1.634 1.142");
}

.grqmao4rm {
  stop-color: var(--svg-color--b59cc2, #B59CC2);
  stop-opacity: 0;
}

.h0nz-rbjw {
  stop-color: var(--svg-color--7f5499, #7F5499);
}

.h94nvm15h {
  stop-color: var(--svg-color--43b1db, #43B1DB);
}

.hbprp_aru {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M6.593 19.72c-.206.433-.319 1.45.875 2.055c1.194.607 1.992.149 2.242-.156");
}

.he69lvb0i {
  stop-color: var(--svg-color--755994, #755994);
  stop-opacity: 0;
}

.hfzkti_ts {
  stop-color: var(--svg-color--8e5de1, #8E5DE1);
  stop-opacity: 0;
}

.hgbgo3h5d {
  fill: var(--svg-color--47302e, #47302E);
  d: path("M9.67 17.354c.243.25.33.526.343.632l.485.469l2.34.408a.89.89 0 0 0 1.025-.694a.9.9 0 0 0-.774-1.078c-1.09-.133-2.42-.306-2.779-.347c-.613-.07-.945.297-.64.61");
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkdf97w8c {
  stop-color: var(--svg-color--804ec1, #804EC1);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hkxvz0u3y {
  stop-color: var(--svg-color--351e25, #351E25);
  stop-opacity: 0;
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i4p54obux {
  stop-color: var(--svg-color--3b201d, #3B201D);
}

.ih6scz3jp {
  d: path("M21.835 23.99c-1.17-2.04-3.78-2.73-5.81-1.56l-2.43 1.4c-2.04 1.17-2.73 3.78-1.56 5.81l.21.33h7.73l.3-.18a4.23 4.23 0 0 0 1.56-5.8");
}

.ikgl8m1ug {
  stop-color: var(--svg-color--301d1a, #301D1A);
}

.incjljb4q {
  stop-color: var(--svg-color--090c09, #090C09);
}

.is46jlpxt {
  d: path("m8.972 10.248l.013-.002l-.062-.263l-.07-.305c-.164-.953.318-1.428.53-1.596l.048-.03l.047-.031c.486-.349.833-.862.95-1.467l.044-.21a.269.269 0 0 1 .452-.14a3.94 3.94 0 0 0 3.516 1.052l3.221-.626c.18-.035 1.1-.124 1.396 1.111l.48 3.097c.421 2.828-1.402 5.137-4.074 5.657s-5.228-.937-5.897-3.716z");
}

.iz0cumb_r {
  d: path("M8.521 18.45a.28.28 0 0 1 .133-.269c.981-.69 2.005-.304 2.383 0c.304.236 1 .79 1.363 1.082c.446.36.372.961.043 1.317c-.276.298-.751.24-.93.148l-2.097-1.312c-.055-.313-.235-.563-.48-.637c-.247-.074-.403-.133-.415-.328");
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j4n7g28_w {
  stop-color: var(--svg-color--8e72a9, #8E72A9);
}

.j9v6w1g-o {
  stop-color: var(--svg-color--0a0909, #0A0909);
}

.jids0zpwm {
  stop-color: var(--svg-color--59403d, #59403D);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jl5bjg5-e {
  d: path("M20.615 25.749c1.598-.23 4.567-.81 6.543-1.27c1.522-.263 2.641 1.203 2.641 2.78c0 1.372-1.022 2.237-1.747 2.62a.86.86 0 0 1-.403.092h-8.014v-3.086c0-.797.281-1 .98-1.137");
}

.jvlxembhy {
  stop-color: var(--svg-color--7d49d2, #7D49D2);
}

.jwj9mobso {
  fill: var(--svg-color--2f2428, #2F2428);
  d: path("M12.187 2.845c-1.182-.03-1.979 1.3-2.015 1.741c1.742 3.342 4.367 2.63 6.938 1.826c1.54-.48 1.85.203 2.051.523c-.766-3.934-4.255-4.021-6.944-4.089z");
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

.k-tvti7jd {
  d: path("M8.857 20.9c-.315.22-.723.211-.906-.11c-.391-.947.72-1.579 1.5-1.597c1.167-.027 1.75.63 1.937 1.121c.188.492.227 1.477-.672 1.54c-.803.055-.847-.5-.98-.743c-.133-.242-.594-.41-.879-.21");
}

.k35cj8b6j {
  stop-color: var(--svg-color--685755, #685755);
}

.k5vtewq9k {
  stop-color: var(--svg-color--8b5dd1, #8B5DD1);
}

.k7xyk1boq {
  stop-color: var(--svg-color--594947, #594947);
}

.ka236wzgl {
  stop-color: var(--svg-color--2b2b2b, #2B2B2B);
  stop-opacity: 0;
}

.kaydztigo {
  stop-color: var(--svg-color--695856, #695856);
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kdyinjb2g {
  stop-color: var(--svg-color--533a36, #533A36);
  stop-opacity: 0;
}

.kfbnffbzx {
  stop-color: var(--svg-color--7a45b3, #7A45B3);
}

.kmp3a3cnr {
  stop-color: var(--svg-color--ce953a, #CE953A);
}

.kn6547brm {
  stop-color: var(--svg-color--8259a4, #8259A4);
}

.kyl8adb5j {
  stop-color: var(--svg-color--148c3e, #148C3E);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l8v5z5bog {
  stop-color: var(--svg-color--6e574e, #6E574E);
}

.laie_nbgc {
  stop-color: var(--svg-color--8e72a9, #8E72A9);
  stop-opacity: 0;
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lkp5p8bgu {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.024 13.691a3.1 3.1 0 0 1-1.49-.068c-.154-.045-.274.146-.16.26a1.97 1.97 0 0 0 3.25-.633c.063-.153-.119-.28-.245-.18c-.37.3-.83.52-1.355.621Z");
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.ll6ec2bpd {
  stop-color: var(--svg-color--6e574e, #6E574E);
  stop-opacity: 0;
}

.lq414ub4c {
  stop-color: var(--svg-color--412c2a, #412C2A);
  stop-opacity: 0;
}

.lrce32g5i {
  stop-color: var(--svg-color--441f26, #441F26);
}

.lrxagac4l {
  d: path("M10.737 8.967c1.3-.297 2.288.26 2.582.979c-1.237-.277-1.975-.04-2.383.198z");
}

.m-leh6bjs {
  stop-color: var(--svg-color--2b2b2b, #2B2B2B);
}

.m0rm-m-qv {
  stop-color: var(--svg-color--785191, #785191);
}

.m1u4bsjqr {
  d: path("M15.315 7.91c1.333-.038 2.193.7 2.341 1.463c-1.159-.512-1.928-.424-2.375-.27z");
}

.m5pz4_bjh {
  fill: var(--svg-color--35252b, #35252B);
  d: path("M9.848 12.504a1.095 1.095 0 1 0-.418-2.149a1.095 1.095 0 0 0 .418 2.15");
}

.m6mmhsf1n {
  stop-color: var(--svg-color--3f243b, #3F243B);
  stop-opacity: 0;
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.mkxkbksmb {
  fill: var(--svg-color--331b25, #331B25);
  d: path("m13.944 10.476l-.353 1.833a.55.55 0 0 0 .657.599l.787-.153a.55.55 0 0 0 .385-.801l-.863-1.598c-.187-.354-.567-.28-.613.12");
}

.moemzebdy {
  d: path("M8.13 17.213c1.031-1.086 1.92-1.37 2.32-1.375l.797.867l-.93 3.516c-.179.315-.563.996-.695 1.152c-.164.195-.734.63-1.765.238c-.888-.337-1.15-.898-1.176-1.148c.234-1.168.649-2.358 1.45-3.25");
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n8jici3hn {
  stop-color: var(--svg-color--fed466, #FED466);
  stop-opacity: 0;
}

.n8ysctycz {
  stop-color: var(--svg-color--2b151b, #2B151B);
}

.ncc0lbcfj {
  d: path("M12.966 10.172c-.075.012-.13.061-.176.13a1.05 1.05 0 0 1-.687.51a1.01 1.01 0 0 1-.826-.179a.24.24 0 0 0-.211-.05a.254.254 0 0 0-.098.452c.343.264.795.38 1.249.279a1.52 1.52 0 0 0 1.03-.771c.098-.185-.072-.408-.28-.371");
}

.nd--cppfl {
  stop-color: var(--svg-color--585352, #585352);
  stop-opacity: 0;
}

.neym138jd {
  stop-color: var(--svg-color--f3c22a, #F3C22A);
}

.ngosmac8t {
  d: path("M10.565 18.54c-.28.05-.54.19-.74.38c.01-.05.02-.1.04-.15l.12-.33c.28-.78 1.09-1.27 1.91-1.15l1.66.23c.42.06.72.45.66.87s-.45.72-.87.66l-1.57-.22c-.34-.26-.78-.37-1.21-.29");
}

.nhce3bcqg {
  stop-color: var(--svg-color--2c1728, #2C1728);
}

.nhvcqmwuq {
  d: path("M10.099 16.432c.356.125.482.33.515.453l.446.39l2.291.363a.92.92 0 0 0 1.062-.872a.913.913 0 0 0-.922-.95c-1.175.013-2.687.035-3.044.026c-.586-.016-.793.433-.348.59");
}

.njdbcpw8w {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
}

.nn3wh7bnm {
  stop-color: var(--svg-color--58d4f5, #58D4F5);
}

.ns7l0dbhs {
  d: path("M15.383 9.937c.128.112.505.318.982.249c.478-.07.883-.55.984-.73");
}

.ny_jxsr8o {
  stop-color: var(--svg-color--574743, #574743);
}

.o-2hudmmt {
  d: path("M21.575 23.91a4.3 4.3 0 0 1 .71-5.22a4.31 4.31 0 0 0-2.61 6.21a4.304 4.304 0 0 0 6.78 1.01c-1.84.51-3.87-.26-4.88-2");
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.o7yf4tl0b {
  stop-color: var(--svg-color--b087f9, #B087F9);
}

.o88b13bjp {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m17.605 7.559l-.093.257za.273.273 0 0 1-.186.514l-.005-.002a1 1 0 0 0-.125-.036a3 3 0 0 0-.369-.069a2.3 2.3 0 0 0-1.09.117a.273.273 0 1 1-.196-.51a2.9 2.9 0 0 1 1.35-.15a3.3 3.3 0 0 1 .605.13l.01.004l.004.001z");
}

.ohw562bgk {
  d: path("M10.214 21.657c-.284.88-1.448 1.292-2.6.92c-1.152-.37-1.793-1.177-1.573-2.265c.18-.888.884-1.75 2.738-1.24c1.153.372 1.719 1.705 1.435 2.585");
}

.ojg0kubzr {
  d: path("M21.77 10.533c.128-.477.144-.984.046-1.49a3.3 3.3 0 0 0-.523-1.254l.005-.001a3.3 3.3 0 0 0-.38-.459l-.003-.002a3.3 3.3 0 0 1-.872-1.67l-.002-.01A3.363 3.363 0 0 0 16.1 2.99a.55.55 0 0 1-.501-.144a3.37 3.37 0 0 0-2.951-.855a3.37 3.37 0 0 0-2.415 1.9a.58.58 0 0 1-.41.32l-.085.018a3.363 3.363 0 0 0-2.573 3.925l.002.01c.122.628.06 1.281-.182 1.875l-.002.004a3.36 3.36 0 0 0 .412 3.289c.098.128.132.3.088.455c-.12.465-.148.964-.05 1.47a3.275 3.275 0 0 0 3.846 2.593l8.585-1.67a3.275 3.275 0 0 0 2.593-3.846a3.3 3.3 0 0 0-.598-1.344a.52.52 0 0 1-.088-.456m-12.785-.287l-.013.003l1.658 2.123c.669 2.78 1.217-.237 3.89-.757s4.445 2.374 4.023-.454l.514-3.42C18.76 6.508 17.84 6.596 17.66 6.63l-3.221.627a3.94 3.94 0 0 1-3.516-1.053a.269.269 0 0 0-.452.14l-.044.21a2.35 2.35 0 0 1-1.045 1.528c-.212.168-.694.644-.53 1.597l.07.304z");
}

.ojt9l7bfl {
  stop-color: var(--svg-color--695856, #695856);
  stop-opacity: 0;
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.p_ew-572a {
  stop-color: var(--svg-color--8152c8, #8152C8);
  stop-opacity: 0;
}

.p3henobog {
  d: path("m2.201 29.97l2.93-9.155C5.482 19.4 7.2 18.71 8.78 19.2s2.49 2.332 2.006 3.692L8.571 29.97z");
}

.p40qzpbtf {
  stop-color: var(--svg-color--985ef1, #985EF1);
}

.p6n8nbb9p {
  stop-color: var(--svg-color--78e2ff, #78E2FF);
  stop-opacity: 0;
}

.p75tg79fv {
  stop-color: var(--svg-color--4f3442, #4F3442);
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pdon63boo {
  stop-color: var(--svg-color--f38820, #F38820);
  stop-opacity: 0;
}

.piz2rbc3b {
  stop-color: var(--svg-color--875ab4, #875AB4);
  stop-opacity: 0;
}

.pj2ff5nxp {
  stop-color: var(--svg-color--2d181a, #2D181A);
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

.q_yfvabjb {
  stop-color: var(--svg-color--685756, #685756);
}

.q726rgbgc {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m15.9 5.87l-1.374.54a.701.701 0 1 1-.391-1.34l2.342-.456c1.384-.27 2.115 1.037 2.264 1.503a3.2 3.2 0 0 0-2.84-.246");
}

.q9xywcr7e {
  stop-color: var(--svg-color--9c6ed3, #9C6ED3);
}

.qenr6bbwz {
  stop-color: var(--svg-color--2a1c1f, #2A1C1F);
}

.qh-ows9fr {
  stop-color: var(--svg-color--a07cb6, #A07CB6);
}

.qic_n_blg {
  stop-color: var(--svg-color--d2c9d1, #D2C9D1);
}

.qj5edhacv {
  stop-color: var(--svg-color--301d1a, #301D1A);
  stop-opacity: 0;
}

.qm132ccsa {
  stop-color: var(--svg-color--655251, #655251);
  stop-opacity: 0;
}

.qtvy6rbzh {
  stop-color: var(--svg-color--42b8e0, #42B8E0);
}

.quizolb0d {
  d: path("M9.67 17.354c.243.25.33.526.343.632l.485.469l2.34.408a.89.89 0 0 0 1.025-.694a.9.9 0 0 0-.774-1.078c-1.09-.133-2.42-.306-2.779-.347c-.613-.07-.945.297-.64.61");
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.qww1g7b4f {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M10.141 4.54c.071.239.46 1.111.878 1.604");
}

.qz7bmgb4x {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m10.562 9.404l-.004.004a.273.273 0 0 1-.365-.407h.001l.003-.003l.008-.008a2 2 0 0 1 .134-.105c.09-.066.218-.154.379-.242a2.86 2.86 0 0 1 1.307-.368a.273.273 0 1 1 .01.547a2.3 2.3 0 0 0-1.055.3a3 3 0 0 0-.418.282");
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r22hnp7ou {
  d: path("M17.221 9.3c-.076.012-.131.061-.176.13a1.05 1.05 0 0 1-.687.51a.97.97 0 0 1-.826-.189a.27.27 0 0 0-.212-.05a.254.254 0 0 0-.098.452c.343.264.796.381 1.25.279a1.52 1.52 0 0 0 1.03-.771c.097-.185-.073-.407-.28-.362");
}

.r78w96dej {
  d: path("M7.155 29.97c-1.05 0-1.9-.85-1.89-1.9l.01-2.13c0-5.77 4.79-10.46 10.69-10.46c5.91 0 10.69 4.68 10.69 10.46l.17 4.03z");
}

.r7lliibxj {
  d: path("m15.53 17.836l.554.16a.15.15 0 0 1 .103.185l-.784 2.73a.15.15 0 0 1-.185.102l-.555-.159z");
}

.rehc034in {
  stop-color: var(--svg-color--8356d1, #8356D1);
}

.rk01_7i4j {
  d: path("M15.685 18.5c1.06 0 1.91-.86 1.91-1.91v-2.26a1.91 1.91 0 1 0-3.82 0v2.26c-.01 1.06.85 1.91 1.91 1.91");
}

.rmmi4abgs {
  stop-color: var(--svg-color--371d1f, #371D1F);
  stop-opacity: 0;
}

.rntqzsbvm {
  stop-color: var(--svg-color--925cbe, #925CBE);
}

.s20jr_bro {
  d: path("M8.07 5.517c.45-.71 1.52-.919 2.033-.926l.647 1.214c-.26.01-.469.144-.623.365c-.203 1.348-1.609 2.344-2.287 2.673c-.439-1.464-.354-2.402.23-3.326");
}

.s5p0jt_2h {
  d: path("M19.45 11.191a1.64 1.64 0 1 0-.627-3.22a1.64 1.64 0 0 0 .627 3.22");
}

.s5w7sgqdm {
  stop-color: var(--svg-color--574743, #574743);
  stop-opacity: 0;
}

.s9u3_wbrp {
  stop-color: var(--svg-color--402824, #402824);
}

.sbx2zkbbn {
  stop-color: var(--svg-color--89579c, #89579C);
  stop-opacity: 0;
}

.sdufqstmc {
  stop-color: var(--svg-color--2d181a, #2D181A);
}

.sexb1etbn {
  stop-color: var(--svg-color--472b2b, #472B2B);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sinn-3bvk {
  stop-color: var(--svg-color--6cd8f5, #6CD8F5);
  stop-opacity: 0;
}

.sozlwmb1o {
  stop-color: var(--svg-color--2f2127, #2F2127);
  stop-opacity: 0;
}

.spm60ki7k {
  d: path("m14.826 17.069l-2.636-.735l-1.073 3.895l2.6.734c.408.11.755-.065.85-.394l.78-2.703c.123-.391-.164-.694-.521-.797");
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.t-pst_b0z {
  stop-color: var(--svg-color--422e2b, #422E2B);
}

.t4dyfpxnt {
  stop-color: var(--svg-color--351e25, #351E25);
}

.t5djkhb4t {
  stop-color: var(--svg-color--655251, #655251);
}

.t78i98bfv {
  stop-color: var(--svg-color--735caf, #735CAF);
  stop-opacity: 0;
}

.t8je_6qbh {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M15.024 13.691a3.1 3.1 0 0 1-1.49-.068c-.154-.045-.274.146-.16.26a1.97 1.97 0 0 0 3.25-.633c.063-.153-.119-.28-.245-.18c-.37.3-.83.52-1.355.621");
}

.tbs366q3s {
  stop-color: var(--svg-color--4760c0, #4760C0);
}

.tnk2b_bjh {
  stop-color: var(--svg-color--a078e0, #A078E0);
}

.tomvu1bgl {
  stop-color: var(--svg-color--78e0ff, #78E0FF);
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tryqaac1t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
}

.tzj34xnjq {
  stop-color: var(--svg-color--ffd267, #FFD267);
}

.ua_x0bb_u {
  d: path("M9.848 12.504a1.095 1.095 0 1 0-.418-2.149a1.095 1.095 0 0 0 .418 2.15");
}

.ugbytbngn {
  stop-color: var(--svg-color--ffd267, #FFD267);
  stop-opacity: 0;
}

.umj075h7d {
  fill: var(--svg-color--9c84d0, #9C84D0);
  d: path("m29.145 25.31l-4.94-6.05l-3.16 8.57z");
}

.ut4bgvb0y {
  stop-color: var(--svg-color--8a68c3, #8A68C3);
}

.v2wkn2ras {
  stop-color: var(--svg-color--31ae6a, #31AE6A);
}

.v2xpqhbrh {
  stop-color: var(--svg-color--402a29, #402A29);
}

.v442oubmz {
  stop-color: var(--svg-color--7c4ca4, #7C4CA4);
}

.vgekv3bdy {
  stop-color: var(--svg-color--3e2828, #3E2828);
}

.vkqqj1b4e {
  stop-color: var(--svg-color--3a1a1d, #3A1A1D);
}

.w_57dfb5m {
  stop-color: var(--svg-color--735caf, #735CAF);
}

.w1_1yhbve {
  stop-color: var(--svg-color--564848, #564848);
}

.w212xwb1h {
  d: path("M12.187 2.845c-1.182-.03-1.979 1.3-2.015 1.741c1.742 3.342 4.367 2.63 6.938 1.826c1.54-.48 1.85.203 2.051.523c-.766-3.934-4.255-4.021-6.944-4.089z");
}

.wagk6dfaq {
  stop-color: var(--svg-color--966be0, #966BE0);
}

.wb78_hxsc {
  stop-color: var(--svg-color--6a5956, #6A5956);
}

.wcbvx-n_a {
  stop-color: var(--svg-color--89579c, #89579C);
}

.wi8a08bum {
  stop-color: var(--svg-color--785191, #785191);
  stop-opacity: 0;
}

.x_sue_b_g {
  stop-color: var(--svg-color--634d4b, #634D4B);
}

.x7h3p2bdy {
  stop-color: var(--svg-color--533632, #533632);
  stop-opacity: 0;
}

.x9s6ceaht {
  stop-color: var(--svg-color--b087f9, #B087F9);
  stop-opacity: 0;
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xfmbn4_bb {
  stop-color: var(--svg-color--3a1f30, #3A1F30);
  stop-opacity: 0;
}

.xk654sehy {
  fill: var(--svg-color--4c3637, #4C3637);
  d: path("M19.346 10.656a1.095 1.095 0 1 0-.418-2.15a1.095 1.095 0 0 0 .418 2.15");
}

.xuyenabum {
  stop-color: var(--svg-color--371d1f, #371D1F);
}

.xvchkzb4d {
  fill: var(--svg-color--4a302d, #4A302D);
  d: path("m13.928 10.334l-.201 1.805a.55.55 0 0 0 .657.598l.787-.153a.55.55 0 0 0 .384-.801l-.862-1.598c-.188-.354-.72-.25-.765.15");
}

.y-ymn0bhn {
  stop-color: var(--svg-color--755994, #755994);
}

.y8_rm488v {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M11.993 8.508c-.338-.016-1.133.18-1.594.668");
}

.ybvm9tprh {
  stop-color: var(--svg-color--594d4d, #594D4D);
}

.ydc3b1bgo {
  d: path("M23.445 27.13a4.3 4.3 0 1 0 0-8.6a4.3 4.3 0 0 0 0 8.6");
}

.yxmxw0ard {
  stop-color: var(--svg-color--32996b, #32996B);
}

.yxwqgvbem {
  stop-color: var(--svg-color--594d4d, #594D4D);
  stop-opacity: 0;
}

.yyn9swbvh {
  stop-color: var(--svg-color--784787, #784787);
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z1zjblq2q {
  stop-color: var(--svg-color--8b5dd1, #8B5DD1);
  stop-opacity: 0;
}

.z3zsa5bpu {
  stop-color: var(--svg-color--53f595, #53F595);
}

.z44v3-bta {
  stop-color: var(--svg-color--3b201d, #3B201D);
  stop-opacity: 0;
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.zbexf6jod {
  stop-color: var(--svg-color--564848, #564848);
  stop-opacity: 0;
}

.zbwshaccu {
  stop-color: var(--svg-color--875ab4, #875AB4);
}

.zm6geub_u {
  stop-color: var(--svg-color--441f26, #441F26);
  stop-opacity: 0;
}

.znnnwod6o {
  fill: var(--svg-color--20171a, #20171A);
  d: path("M8.07 5.517c.45-.71 1.52-.919 2.033-.926l.647 1.214c-.26.01-.469.144-.623.365c-.203 1.348-1.609 2.344-2.287 2.673c-.439-1.464-.354-2.402.23-3.326");
}

.zp0o58pil {
  d: path("M9.933 13.043a1.64 1.64 0 1 0-.626-3.22a1.64 1.64 0 0 0 .626 3.22");
}

.zpi5yt9_e {
  stop-color: var(--svg-color--594947, #594947);
  stop-opacity: 0;
}

.zpqiekbmq {
  stop-color: var(--svg-color--543733, #543733);
}

.zz4mcgrzh {
  stop-color: var(--svg-color--59403d, #59403D);
  stop-opacity: 0;
}

</style>
