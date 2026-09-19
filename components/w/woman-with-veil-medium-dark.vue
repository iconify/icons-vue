<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="iqyrKvc" class="n38nmb94x"/></defs><g class="ft5dv1b6b"><g filter="url(#iPUCPse)"><path fill="url(#iyqECnb)" class="rqn5r__rt"/><path fill="url(#iTEIKhe)" class="rqn5r__rt"/><path fill="url(#irLShne)" class="rqn5r__rt"/></g><g filter="url(#igTcX8b)"><path fill="url(#iRujXJe)" class="d4sy-lw5d"/></g><g filter="url(#iR3UCvS)"><path fill="url(#iFnfcRb)" clip-rule="evenodd" class="bzn24qbzw"/><path fill="url(#i1IDEWb)" clip-rule="evenodd" class="bzn24qbzw"/><path fill="url(#iUVfWCc)" clip-rule="evenodd" class="bzn24qbzw"/><path fill="url(#i8Tfrac)" clip-rule="evenodd" class="bzn24qbzw"/><path fill="url(#iydHbMv)" clip-rule="evenodd" class="bzn24qbzw"/><path fill="url(#i8W85pb)" clip-rule="evenodd" class="bzn24qbzw"/><path fill="url(#isvhBjp)" clip-rule="evenodd" class="bzn24qbzw"/><path fill="url(#iv89jJc)" clip-rule="evenodd" class="bzn24qbzw"/><path fill="url(#idF8nkx)" clip-rule="evenodd" class="bzn24qbzw"/><path fill="url(#iniDHNd)" clip-rule="evenodd" class="bzn24qbzw"/><path fill="url(#iPVqL5H)" clip-rule="evenodd" class="bzn24qbzw"/></g><path fill="url(#iJf1iUb)" class="shep8_bdh"/><path fill="url(#i2qypic)" class="shep8_bdh"/><path fill="url(#i8qGVjb)" class="shep8_bdh"/><path fill="url(#i3dimgb)" class="shep8_bdh"/><g filter="url(#ibMFSJc)"><path class="o_rd0acqn"/></g><g filter="url(#ijuXeNe)"><path class="engxb26bh"/></g><g filter="url(#icTmv3P)"><path fill="url(#io4gIPe)" class="ix_9o_9wu"/><path fill="url(#iqMD7gd)" class="ix_9o_9wu"/><path fill="url(#isjlhEd)" class="ix_9o_9wu"/></g><g filter="url(#iucOzsb)"><path fill="url(#ilanV8c)" class="bxy9a_8wa"/><path fill="url(#iNWzONb)" class="bxy9a_8wa"/><path fill="url(#ieXxVFd)" class="bxy9a_8wa"/></g><g filter="url(#iebrsyb)"><path fill="url(#iX2ApPb)" class="dw40nqbxs"/><path fill="url(#iYYACRc)" class="dw40nqbxs"/><path fill="url(#i61pLub)" class="dw40nqbxs"/><path fill="url(#iXj7CGc)" class="dw40nqbxs"/><path fill="url(#iVEfmVd)" class="dw40nqbxs"/></g><path fill="url(#im1Zhlq)" class="fk_o1xs8s"/><path fill="url(#iZeoqdr)" class="fk_o1xs8s"/><g filter="url(#i1mciHK)"><path class="dz5hgfbwb"/></g><g filter="url(#imSYaHX)"><path fill="url(#isd35Ge)" class="k13ak_bzi"/><path fill="url(#iiLdS3c)" class="k13ak_bzi"/></g><g filter="url(#iJdEdLe)"><path fill="url(#iKh9DQb)" class="x0qjlw0mb"/><path fill="url(#iplo2Cc)" class="x0qjlw0mb"/></g><circle fill="url(#i25Pfce)" class="j-elh2uvv"/><circle fill="url(#iZ35ERd)" class="j-elh2uvv"/><circle fill="url(#iAAvyQb)" transform="matrix(-1 0 0 1 22.919 20.427)" class="movji7bnz"/><circle fill="url(#iH86wby)" transform="matrix(-1 0 0 1 22.919 20.427)" class="movji7bnz"/><circle fill="url(#ifbe9cT)" class="brgj7qtnd"/><circle fill="url(#izM6NXd)" transform="matrix(-1 0 0 1 21.97 21.485)" class="movji7bnz"/><circle fill="url(#iGbM8pb)" transform="matrix(-1 0 0 1 21.97 21.485)" class="movji7bnz"/><path fill="url(#i2LQlsd)" class="ccrydivzf"/><g filter="url(#iNaatfd)"><path class="qgxdbybha"/><path fill="url(#iqtwOJc)" class="zpr5v7b1v"/><path fill="url(#iql0KmQ)" class="zpr5v7b1v"/><path fill="url(#iUaS3oc)" class="zpr5v7b1v"/><path fill="url(#iptGC2c)" class="zpr5v7b1v"/><path fill="url(#isTDdze)" class="zpr5v7b1v"/></g><path fill="url(#ibyJhIe)" class="kcwstyspx"/><g filter="url(#iA2YUnb)"><path class="zt2wz-bdr"/><path fill="url(#iYuu2Rd)" class="s44dqacei"/><path fill="url(#iglME4c)" class="s44dqacei"/></g><g filter="url(#iuQvA6b)"><path class="fo-imacds"/><path fill="url(#i84ZkMb)" class="f5jafwbws"/><path fill="url(#iBTolRe)" class="f5jafwbws"/><path fill="url(#iqD660c)" class="f5jafwbws"/><path fill="url(#iVpU4dr)" class="f5jafwbws"/><path fill="url(#iTMsRuF)" class="f5jafwbws"/></g><g filter="url(#ib8lGCb)"><path fill="url(#in15rgd)" clip-rule="evenodd" class="yjp69hbuv"/></g><g filter="url(#i26rwye)"><path class="i4i_2ibui"/></g><g filter="url(#iC2NKCe)"><path fill="url(#iJ6OHFc)" class="z_qiivm8v"/><path fill="url(#ilfRpxc)" class="z_qiivm8v"/></g><g filter="url(#imR5hTQ)"><path stroke="url(#iQzGmee)" class="ki4t9bbhh"/></g><g filter="url(#ip4Mfoj)"><path stroke="url(#iFopDKd)" class="hbyh_lbnn"/></g><g filter="url(#ipBaZce)"><path stroke="url(#io3ge3b)" class="whpxerb5a"/></g><g filter="url(#iEiOwLe)"><path stroke="url(#ipfffHc)" class="ck10erk2j"/></g><g filter="url(#iemu7Ne)"><path fill="url(#iho8cjd)" class="q01y-fb-l"/></g><g filter="url(#iL3Palc)"><path fill="url(#izRp0Pc)" class="k8eqtnbpc"/><path fill="url(#iRO1lGe)" class="k8eqtnbpc"/></g><g filter="url(#iW7uT7d)"><path class="bgy-ndvjc"/><path fill="url(#ipaVHCv)" class="pnga_4b2z"/></g><g filter="url(#ipDEKib)"><path class="waj_poblt"/><path fill="url(#iNp4QCe)" class="h5j39cckv"/></g><g filter="url(#idiZoqe)"><path fill="url(#i0s4xIc)" class="u0w6z5q5o"/><path fill="url(#ipGnWce)" class="u0w6z5q5o"/><path fill="url(#iq2CqJd)" class="u0w6z5q5o"/><path fill="url(#iKXExgc)" class="u0w6z5q5o"/><path fill="url(#i6SgONd)" class="u0w6z5q5o"/><path fill="url(#iPBJ1WJ)" class="u0w6z5q5o"/><path fill="url(#iSD9UFe)" class="u0w6z5q5o"/><path fill="url(#iJoOOHe)" class="u0w6z5q5o"/></g><path fill="url(#ieBUp2d)" class="u0w6z5q5o"/><path fill="url(#i7N5h3N)" class="u0w6z5q5o"/><path fill="url(#ikdgy8c)" class="u0w6z5q5o"/><g filter="url(#iictVGe)"><path class="w4p6edc7q"/></g><g filter="url(#iD50Cve)"><path class="lvw96kbgx"/><path fill="url(#iuUciLb)" class="jidmdqsym"/><path fill="url(#iItTkJr)" class="jidmdqsym"/><path fill="url(#iCWEJwl)" class="jidmdqsym"/><path fill="url(#i0pRKCd)" class="jidmdqsym"/></g><g filter="url(#iYvHNMd)"><use href="#iqyrKvc"/><path stroke="url(#iGOAjmc)" class="le6hrcb_e"/></g><use href="#iqyrKvc"/><g filter="url(#i2nM1Be)"><path class="f-folhbcb"/></g><g filter="url(#ivuSTUb)"><path class="fgurcxbqa"/></g><g filter="url(#iNIQchb)"><path class="f86v59wxs"/></g><g filter="url(#iEO5Lic)"><path clip-rule="evenodd" class="dzmucob_g"/></g><path class="e8znlebid"/><path fill="url(#iiJ4wrc)" class="qo7m0solq"/><path class="eqonf-bpu"/><g filter="url(#ixC0WQd)"><path class="mmje--ohe"/><path fill="url(#iN5IH6d)" class="cir-2tbku"/></g><g filter="url(#iV77CKc)"><path fill="url(#iSVq9xc)" class="bil-gwbpd"/></g><path class="ftopcck0v"/><path fill="url(#iNB1Xmd)" class="xyi13834j"/><path class="bjc-lxiwy"/><g filter="url(#iZjBaND)"><path fill="url(#iJ0N3zb)" class="e1762_b0a"/></g><g filter="url(#iAl0X6m)"><ellipse transform="rotate(-27.914 13.547 9.875)" class="r_thblbtw"/><ellipse fill="url(#ilHvDOd)" transform="rotate(-27.914 13.547 9.875)" class="d0ys9v7ll"/></g><g filter="url(#in9XkZd)"><path class="mrn0x9y7q"/></g><g filter="url(#iIbfV8d)"><path class="ndnnww3sc"/></g><g filter="url(#iTtgHJc)"><path class="alim0f6wa"/><path fill="url(#ivNzQTr)" class="v6xk-qbhz"/></g><g filter="url(#ilV2ale)"><path class="hus9zqvbn"/><path fill="url(#iCJtMYd)" class="d3coa7kai"/><path fill="url(#iIbEJvc)" class="d3coa7kai"/></g><g filter="url(#imNjPAF)"><path stroke="url(#ilTDXKe)" class="pe7y9ky3x"/></g><g filter="url(#i5OXQsd)"><path class="bopproo0p"/></g><g filter="url(#iBNgmWd)"><path fill="url(#iaEU97Y)" clip-rule="evenodd" class="d72oepody"/><path fill="url(#ilvKHwb)" clip-rule="evenodd" class="d72oepody"/></g><defs><radialGradient id="iTEIKhe" cx="0" cy="0" r="1" gradientTransform="rotate(-126.573 19.837 7.03)scale(14.4752 12.6607)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="sa_c7ns7l"/><stop offset="1" class="xflvpmp1u"/></radialGradient><radialGradient id="irLShne" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 -5.375 4.67303 6.03148 5.7 25.649)" gradientUnits="userSpaceOnUse"><stop class="zhj208b_d"/><stop offset="1" class="y32ab_wii"/></radialGradient><radialGradient id="i1IDEWb" cx="0" cy="0" r="1" gradientTransform="matrix(-.60337 4.55908 -5.69522 -.75373 15.699 13.068)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="iUVfWCc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.883 13.336)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="i8Tfrac" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.912 8.15)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iydHbMv" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.348 7.635)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="i8W85pb" cx="0" cy="0" r="1" gradientTransform="rotate(62.272 4.164 11.584)scale(2.95399 4.10059)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="isvhBjp" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.966 6.815)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="iv89jJc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.84482 23.51 9.716)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="idF8nkx" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.644 7.978)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iniDHNd" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 12.97 -3.775)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iPVqL5H" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.858 9.68)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="iJf1iUb" cx="0" cy="0" r="1" gradientTransform="rotate(155.653 10.15 15.742)scale(12.2796 19.1721)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="vc--wpv5i"/><stop offset="1" class="iaefxbcet"/></radialGradient><radialGradient id="i8qGVjb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09375 1.15624 -3.57275 -6.46962 12.762 28.024)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="v9-8bpxan"/><stop offset="1" class="p5ii0k_1a"/></radialGradient><radialGradient id="i3dimgb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.625 0 0 -3.8125 9.856 24.18)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="tv57cl-9q"/><stop offset="1" class="nof2xyhhe"/></radialGradient><radialGradient id="iqMD7gd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26562 -1.93554 2.61071 -1.7071 23.356 25.819)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="isjlhEd" cx="0" cy="0" r="1" gradientTransform="rotate(155.556 9.636 14.638)scale(1.32158 .2597)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="iNWzONb" cx="0" cy="0" r="1" gradientTransform="matrix(.42186 -1.97502 3.24628 .6934 21.762 27.322)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="l9b4opb5t"/><stop offset=".989" class="uaxm8f1hq"/></radialGradient><radialGradient id="ieXxVFd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1139 -.45312 .07627 -.1875 23.728 26.883)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="iX2ApPb" cx="0" cy="0" r="1" gradientTransform="matrix(-7.77323 -2.8082 3.94394 -10.91704 21.531 21.602)" gradientUnits="userSpaceOnUse"><stop class="wso8oqi8u"/><stop offset="1" class="n50qojbrc"/></radialGradient><radialGradient id="iYYACRc" cx="0" cy="0" r="1" gradientTransform="matrix(.0287 2.22817 -1.66026 .02139 16.728 16.65)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="e7aooyb9w"/><stop offset="1" class="t9sj0nb-w"/></radialGradient><radialGradient id="i61pLub" cx="0" cy="0" r="1" gradientTransform="rotate(162.562 7.063 9.07)scale(5.10983 2.2294)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="xnros5bvd"/><stop offset="1" class="jn8k7gbea"/></radialGradient><radialGradient id="iXj7CGc" cx="0" cy="0" r="1" gradientTransform="rotate(-143.653 14.525 6.708)scale(.91393 .73652)" gradientUnits="userSpaceOnUse"><stop class="p7lh-mbjd"/><stop offset="1" class="a0i9ffblh"/></radialGradient><radialGradient id="iVEfmVd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.8125 -.67275 0 14.336 16.717)" gradientUnits="userSpaceOnUse"><stop class="y_9xrnb_b"/><stop offset="1" class="fyyy25bfx"/></radialGradient><radialGradient id="im1Zhlq" cx="0" cy="0" r="1" gradientTransform="rotate(30.491 -40.767 35.894)scale(7.14423 9.27511)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="a805jtb_d"/><stop offset=".81" class="mpfjlio6c"/></radialGradient><radialGradient id="iiLdS3c" cx="0" cy="0" r="1" gradientTransform="rotate(-56.82 28.188 4.92)scale(2.3126 3.1193)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="iplo2Cc" cx="0" cy="0" r="1" gradientTransform="matrix(-.42043 -1.9751 3.23141 -.68786 10.244 27.32)" gradientUnits="userSpaceOnUse"><stop offset=".609" class="o9qsnlb6c"/><stop offset=".948" class="pcz4s2bal"/></radialGradient><radialGradient id="i25Pfce" cx="0" cy="0" r="1" gradientTransform="rotate(141.833 1.312 11.809)scale(1.27689)" gradientUnits="userSpaceOnUse"><stop class="b4of-6bao"/><stop offset="1" class="r3y-39nqq"/></radialGradient><radialGradient id="iZ35ERd" cx="0" cy="0" r="1" gradientTransform="rotate(90 -5.436 14.604)scale(1.25098)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="d5fabsakk"/><stop offset="1" class="ndghkrcwe"/></radialGradient><radialGradient id="iAAvyQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.17188 .58594 -.45305 .9061 .052 .516)" gradientUnits="userSpaceOnUse"><stop class="n0n4e7bnh"/><stop offset="1" class="jm8e13_st"/></radialGradient><radialGradient id="iH86wby" cx="0" cy="0" r="1" gradientTransform="matrix(.66407 -1.01563 1.1175 .73068 .52 1.063)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yhk8aqbmk"/><stop offset="1" class="zxvvm-hti"/></radialGradient><radialGradient id="ifbe9cT" cx="0" cy="0" r="1" gradientTransform="rotate(139.138 1.348 12.664)scale(1.3016)" gradientUnits="userSpaceOnUse"><stop class="eatp636hk"/><stop offset="1" class="tgwkdpbql"/></radialGradient><radialGradient id="izM6NXd" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07031 -1.1661 1.0895 .298 .379)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="zl4k6m5yt"/><stop offset="1" class="j9i7xp3bx"/></radialGradient><radialGradient id="iGbM8pb" cx="0" cy="0" r="1" gradientTransform="matrix(1.07812 -.64844 .589 .9793 .391 .926)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="tqblnl2vv"/><stop offset=".964" class="kv9fthb_h"/></radialGradient><radialGradient id="i2LQlsd" cx="0" cy="0" r="1" gradientTransform="rotate(69.815 -10.378 19.374)scale(2.04763 .82994)" gradientUnits="userSpaceOnUse"><stop class="z87kcgb7t"/><stop offset=".853" class="r_s898b6a"/></radialGradient><radialGradient id="iqtwOJc" cx="0" cy="0" r="1" gradientTransform="rotate(67.353 -9.301 20.23)scale(4.0633 .80773)" gradientUnits="userSpaceOnUse"><stop class="i7kjncbis"/><stop offset="1" class="wkalc4bst"/></radialGradient><radialGradient id="iql0KmQ" cx="0" cy="0" r="1" gradientTransform="matrix(1.97895 1.21874 -.15017 .24384 9.481 23.024)" gradientUnits="userSpaceOnUse"><stop class="ddg3g7pcd"/><stop offset="1" class="ejr-khbri"/></radialGradient><radialGradient id="iUaS3oc" cx="0" cy="0" r="1" gradientTransform="rotate(-118.794 14.179 9.23)scale(2.33566 5.83179)" gradientUnits="userSpaceOnUse"><stop offset=".268" class="isiq9yb3m"/><stop offset="1" class="uq7zq9b9u"/></radialGradient><radialGradient id="iptGC2c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12499 1.3125 -.4864 -.4169 14.278 24.821)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="ehlybtbyr"/><stop offset="1" class="pbh041bmy"/></radialGradient><radialGradient id="isTDdze" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64063 -.62499 .30595 -.80313 14.309 24.601)" gradientUnits="userSpaceOnUse"><stop class="u3ly29i0x"/><stop offset="1" class="k1xxa4bqz"/></radialGradient><radialGradient id="ibyJhIe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03126 2.5625 -1.3029 -.52434 21.528 21.82)" gradientUnits="userSpaceOnUse"><stop class="rau9skumu"/><stop offset="1" class="obmju7b-z"/></radialGradient><radialGradient id="iYuu2Rd" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 .51562 -.16532 -.21542 23.294 22.727)" gradientUnits="userSpaceOnUse"><stop class="m92tte26k"/><stop offset="1" class="ty1ewib_q"/></radialGradient><radialGradient id="iglME4c" cx="0" cy="0" r="1" gradientTransform="matrix(.58243 3.00041 -1.02662 .19928 19.588 20.74)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="l33l9dqgq"/><stop offset="1" class="fjji9zbbw"/></radialGradient><radialGradient id="i84ZkMb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 2.3125 -1.56386 -.69739 16.794 21.305)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="iBTolRe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96008 .75001 -.74136 -1.93748 19.285 22.992)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="in15rgd" cx="0" cy="0" r="1" gradientTransform="rotate(111.14 1.302 16.642)scale(6.15203 6.32964)" gradientUnits="userSpaceOnUse"><stop class="hr9jc16ta"/><stop offset="1" class="f_r_72dts"/></radialGradient><radialGradient id="iJ6OHFc" cx="0" cy="0" r="1" gradientTransform="matrix(-.8047 .60938 -.52546 -.69388 16.387 23.867)" gradientUnits="userSpaceOnUse"><stop class="ifzr0vvcb"/><stop offset=".808" class="he14dbbbc"/></radialGradient><radialGradient id="ilfRpxc" cx="0" cy="0" r="1" gradientTransform="matrix(.17187 -1.1 1.36133 .2127 15.731 25.254)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="xo240subg"/><stop offset="1" class="ruz641x6w"/></radialGradient><radialGradient id="izRp0Pc" cx="0" cy="0" r="1" gradientTransform="matrix(2.48905 -1.13139 1.38138 3.03902 20.04 11.006)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="olqyf7fmb"/><stop offset=".944" class="hpeo8yzih"/></radialGradient><radialGradient id="iRO1lGe" cx="0" cy="0" r="1" gradientTransform="matrix(1.31577 .7375 -.2085 .37199 21.07 8.886)" gradientUnits="userSpaceOnUse"><stop class="mt9k2qzvi"/><stop offset="1" class="fx1tjiblm"/></radialGradient><radialGradient id="ipaVHCv" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.392 10.68)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="l__dw9bpv"/><stop offset="1" class="wrh2b4bbx"/></radialGradient><radialGradient id="iNp4QCe" cx="0" cy="0" r="1" gradientTransform="rotate(180 5.7 5.284)scale(1.05596)" gradientUnits="userSpaceOnUse"><stop offset=".722" class="o3wo53bzp"/><stop offset="1" class="eo_7g0bzd"/></radialGradient><radialGradient id="i0s4xIc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50358 2.99902 -4.01413 -8.70492 18.86 10.03)" gradientUnits="userSpaceOnUse"><stop class="crj44uotj"/><stop offset="1" class="yamoh3dov"/></radialGradient><radialGradient id="ipGnWce" cx="0" cy="0" r="1" gradientTransform="rotate(156.249 7.841 7.331)scale(2.38203 1.65881)" gradientUnits="userSpaceOnUse"><stop class="up8l18w-p"/><stop offset="1" class="ai95fabuh"/></radialGradient><radialGradient id="iq2CqJd" cx="0" cy="0" r="1" gradientTransform="matrix(1.28915 -3.92836 4.98436 1.6357 13.838 16.538)" gradientUnits="userSpaceOnUse"><stop class="osxg47drp"/><stop offset="1" class="da7h3oe0u"/></radialGradient><radialGradient id="iKXExgc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.1875 -8.98428 0 16 9.67)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="mg10me7tz"/><stop offset=".961" class="kitn3twkh"/></radialGradient><radialGradient id="i6SgONd" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.334 6.746)scale(7.03739 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="opgioqbtx"/><stop offset="1" class="wg3eepbwp"/></radialGradient><radialGradient id="iPBJ1WJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.301 9.612)" gradientUnits="userSpaceOnUse"><stop class="t9k87pm2r"/><stop offset="1" class="ax9af2vtk"/></radialGradient><radialGradient id="iSD9UFe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.924 9.383)" gradientUnits="userSpaceOnUse"><stop class="x_ik4kbfh"/><stop offset="1" class="gcfqr7bfg"/></radialGradient><radialGradient id="iJoOOHe" cx="0" cy="0" r="1" gradientTransform="matrix(-.87016 3.22674 -2.58193 -.69627 17.383 7.296)" gradientUnits="userSpaceOnUse"><stop class="uj7hgsb3u"/><stop offset="1" class="p88c31myn"/></radialGradient><radialGradient id="ieBUp2d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.095 11.099)" gradientUnits="userSpaceOnUse"><stop class="zoq8fuaif"/><stop offset="1" class="ycrcotb4u"/></radialGradient><radialGradient id="i7N5h3N" cx="0" cy="0" r="1" gradientTransform="rotate(-121.569 14.229 2.397)scale(1.52213 1.61741)" gradientUnits="userSpaceOnUse"><stop class="ni-4se4rm"/><stop offset="1" class="wsh5tsbcf"/></radialGradient><radialGradient id="ikdgy8c" cx="0" cy="0" r="1" gradientTransform="matrix(1.75 -1.5625 1.85526 2.0779 11.964 15.759)" gradientUnits="userSpaceOnUse"><stop class="z26rrllgi"/><stop offset="1" class="fs9pa7bci"/></radialGradient><radialGradient id="iuUciLb" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.784 11.825)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="i0pRKCd" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.545 12.037)" gradientUnits="userSpaceOnUse"><stop class="bof3uzbpf"/><stop offset="1" class="jaf6nfbfs"/></radialGradient><radialGradient id="iiJ4wrc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.182 9.97)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iN5IH6d" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.954 10.054)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iNB1Xmd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.818 9.97)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ilHvDOd" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.781 -1.566)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ivNzQTr" cx="0" cy="0" r="1" gradientTransform="matrix(1.26205 -2.75541 1.4096 .64564 10.342 7.85)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="iCJtMYd" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.125 6.952)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="iIbEJvc" cx="0" cy="0" r="1" gradientTransform="matrix(-.21033 1.3672 -2.94145 -.45252 16.21 3.013)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="ilvKHwb" cx="0" cy="0" r="1" gradientTransform="rotate(118.072 9.661 8.597)scale(.92969 16.1409)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="al0tyek2y"/><stop offset="1" class="nbz8snbyn"/></radialGradient><filter id="iPUCPse" width="21.944" height="26.818" x="4.962" y="3.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.952941 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3413"/></filter><filter id="igTcX8b" width="12.631" height="14.916" x="9.484" y="8.503" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.811765 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3413"/><feGaussianBlur result="effect2_foregroundBlur_4002_3413" stdDeviation=".05"/></filter><filter id="iR3UCvS" width="15.268" height="15.768" x="8.491" y="1.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3413"/></filter><filter id="ibMFSJc" width="5.874" height="5.537" x="6.993" y="23.17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3413" stdDeviation=".5"/></filter><filter id="ijuXeNe" width="4.979" height="4.054" x="18.51" y="24.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3413" stdDeviation=".5"/></filter><filter id="icTmv3P" width="2.973" height="2.006" x="21.47" y="23.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3413"/></filter><filter id="iucOzsb" width="3.281" height="2" x="20.468" y="25.323" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3413"/></filter><filter id="iebrsyb" width="13.965" height="11.381" x="9.149" y="12.631" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.286275 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3413"/></filter><filter id="i1mciHK" width="10.996" height="6.432" x="11.932" y="21.998" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3413" stdDeviation=".5"/></filter><filter id="imSYaHX" width="2.973" height="2.006" x="7.658" y="23.687" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3413"/></filter><filter id="iJdEdLe" width="3.266" height="2" x="8.366" y="25.323" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3413"/></filter><filter id="iNaatfd" width="6.218" height="6.789" x="8.343" y="20.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.227451 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3413"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.141176 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3413" result="effect2_innerShadow_4002_3413"/></filter><filter id="iA2YUnb" width="6.218" height="6.639" x="17.574" y="20.02" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.239216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3413"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.301961 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3413" result="effect2_innerShadow_4002_3413"/></filter><filter id="iuQvA6b" width="6.702" height="6.417" x="12.683" y="20.751" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.619608 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3413"/></filter><filter id="ib8lGCb" width="6.703" height="6.517" x="12.633" y="20.701" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3413" stdDeviation=".15"/></filter><filter id="i26rwye" width="3.2" height="3.2" x="14.271" y="22.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3413" stdDeviation=".25"/></filter><filter id="iC2NKCe" width="2.35" height="2.35" x="14.893" y="23.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.521569 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3413"/></filter><filter id="imR5hTQ" width="1.458" height="2.505" x="15.848" y="20.605" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3413" stdDeviation=".125"/></filter><filter id="ip4Mfoj" width="1.723" height="1.924" x="16.94" y="24.449" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3413" stdDeviation=".125"/></filter><filter id="ipBaZce" width="1.368" height="2.217" x="18.104" y="22.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3413" stdDeviation=".125"/></filter><filter id="iEiOwLe" width="3.55" height="1.942" x="15.171" y="17.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3413" stdDeviation=".25"/></filter><filter id="iemu7Ne" width="3.368" height="3.218" x="9.705" y="8.958" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.376471 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3413"/></filter><filter id="iL3Palc" width="3.218" height="3.468" x="19.218" y="8.708" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.431373 0 0 0 0 0.243137 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3413"/></filter><filter id="iW7uT7d" width="3.148" height="3.148" x="19.253" y="8.993" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3413" stdDeviation=".25"/></filter><filter id="ipDEKib" width="2.648" height="2.648" x="10.009" y="9.243" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3413" stdDeviation=".125"/></filter><filter id="idiZoqe" width="10.191" height="11.127" x="10.905" y="5.661" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.223529 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3413"/></filter><filter id="iictVGe" width="2.877" height="3.682" x="14.399" y="9.562" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3413" stdDeviation=".25"/></filter><filter id="iD50Cve" width="2.377" height="3.182" x="14.812" y="9.674" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3413" stdDeviation=".125"/></filter><filter id="iYvHNMd" width="3.702" height="1.526" x="14.149" y="12.916" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3413" stdDeviation=".05"/></filter><filter id="i2nM1Be" width="3.001" height="1.286" x="16.942" y="9.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3413"/></filter><filter id="ivuSTUb" width="3.001" height="1.286" x="12.057" y="9.163" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3413"/></filter><filter id="iNIQchb" width="2.453" height="1.091" x="12.192" y="7.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3413"/></filter><filter id="iEO5Lic" width="2.453" height="1.091" x="17.609" y="7.739" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0901961 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3413"/></filter><filter id="ixC0WQd" width=".787" height=".696" x="17.448" y="9.53" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3413" stdDeviation=".05"/></filter><filter id="iV77CKc" width=".891" height=".913" x="18.288" y="9.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3413" stdDeviation=".1"/></filter><filter id="iZjBaND" width=".986" height="1.04" x="13.845" y="9.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3413" stdDeviation=".1"/></filter><filter id="iAl0X6m" width=".913" height=".704" x="13.09" y="9.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3413" stdDeviation=".05"/></filter><filter id="in9XkZd" width="2.261" height=".978" x="17.64" y="7.861" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3413" stdDeviation=".1"/></filter><filter id="iIbfV8d" width="2.261" height=".978" x="12.188" y="7.861" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3413" stdDeviation=".1"/></filter><filter id="iTtgHJc" width="4.312" height="4.613" x="9.646" y="3.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.294118 0 0 0 0 0.262745 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3413"/><feGaussianBlur result="effect2_foregroundBlur_4002_3413" stdDeviation=".2"/></filter><filter id="ilV2ale" width="8.767" height="5.782" x="12.83" y="2.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3413"/><feGaussianBlur result="effect2_foregroundBlur_4002_3413" stdDeviation=".125"/></filter><filter id="imNjPAF" width="1.145" height="2.31" x="12.809" y="3.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3413" stdDeviation=".1"/></filter><filter id="i5OXQsd" width="6.927" height="3.872" x="15.168" y="4.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3413" stdDeviation=".5"/></filter><filter id="iBNgmWd" width="15.448" height="4.54" x="8.283" y="2.493" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.694118 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3413"/></filter><linearGradient id="iyqECnb" x1="26.906" x2="11.7" y1="11.524" y2="21.524" gradientUnits="userSpaceOnUse"><stop class="fzn5p4bte"/><stop offset="1" class="mu5z5titl"/></linearGradient><linearGradient id="iRujXJe" x1="20.7" x2="10.387" y1="17.43" y2="17.43" gradientUnits="userSpaceOnUse"><stop class="ct82q_bbh"/><stop offset="1" class="gi1yleb5l"/></linearGradient><linearGradient id="iFnfcRb" x1="20.693" x2="13.888" y1="3.615" y2="16.219" gradientUnits="userSpaceOnUse"><stop class="c1nwhtznm"/><stop offset="1" class="ogqxd-bue"/></linearGradient><linearGradient id="i2qypic" x1="14.887" x2="14.887" y1="30.899" y2="29.617" gradientUnits="userSpaceOnUse"><stop class="ujdq-6enc"/><stop offset="1" class="hpzv-ab9a"/></linearGradient><linearGradient id="io4gIPe" x1="23.649" x2="21.867" y1="25.822" y2="24.411" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="ilanV8c" x1="22.95" x2="21.169" y1="27.405" y2="25.711" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="iZeoqdr" x1="12.653" x2="13.255" y1="29.29" y2="28.946" gradientUnits="userSpaceOnUse"><stop class="jih6tvbze"/><stop offset="1" class="g22d_bc_z"/></linearGradient><linearGradient id="isd35Ge" x1="7.856" x2="9.361" y1="24.305" y2="26.125" gradientUnits="userSpaceOnUse"><stop class="n1imc2b4i"/><stop offset="1" class="dz0-61bre"/></linearGradient><linearGradient id="iKh9DQb" x1="9.062" x2="10.843" y1="27.404" y2="25.72" gradientUnits="userSpaceOnUse"><stop class="cnrgi8b1a"/><stop offset="1" class="y8qpet1tz"/></linearGradient><linearGradient id="iqD660c" x1="14.919" x2="16.7" y1="27.168" y2="22.899" gradientUnits="userSpaceOnUse"><stop class="i1hqu4kst"/><stop offset="1" class="k_kfijbew"/></linearGradient><linearGradient id="iVpU4dr" x1="13.356" x2="16.981" y1="22.93" y2="23.617" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="iTMsRuF" x1="17.231" x2="16.325" y1="26.93" y2="25.18" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="iQzGmee" x1="16.477" x2="16.477" y1="20.852" y2="22.86" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="iFopDKd" x1="17.286" x2="18.153" y1="24.907" y2="26.11" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset="0" class="gn67s1beu"/><stop offset=".739" class="gn67s1beu"/><stop offset="1" class="o38c5rykb"/></linearGradient><linearGradient id="io3ge3b" x1="18.728" x2="18.728" y1="22.439" y2="24.055" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="ipfffHc" x1="16.132" x2="20.117" y1="19.05" y2="17.878" gradientUnits="userSpaceOnUse"><stop class="dg0-lwyyf"/><stop offset="1" class="d94uojbbb"/></linearGradient><linearGradient id="iho8cjd" x1="9.756" x2="10.997" y1="10.654" y2="10.654" gradientUnits="userSpaceOnUse"><stop class="b9k-3ybvb"/><stop offset="1" class="vbw-bobru"/></linearGradient><linearGradient id="iItTkJr" x1="15.062" x2="16" y1="11.899" y2="11.899" gradientUnits="userSpaceOnUse"><stop class="rby1z7ber"/><stop offset="1" class="dl0nwov2w"/></linearGradient><linearGradient id="iCWEJwl" x1="16" x2="16" y1="12.698" y2="12.087" gradientUnits="userSpaceOnUse"><stop class="cyl8wapbv"/><stop offset="1" class="jplc2lvem"/></linearGradient><linearGradient id="iGOAjmc" x1="14.936" x2="15.397" y1="14.107" y2="13.395" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="iSVq9xc" x1="18.96" x2="18.646" y1="10.024" y2="10.218" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iJ0N3zb" x1="14.562" x2="14.248" y1="10.024" y2="10.218" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ilTDXKe" x1="13.109" x2="13.654" y1="4.369" y2="5.643" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="iaEU97Y" x1="20.481" x2="8.544" y1="3.68" y2="7.368" gradientUnits="userSpaceOnUse"><stop class="muovvys4e"/><stop offset="1" class="bvsk-i9dj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-with-veil-medium-dark" /></template>
<style>
.a0i9ffblh {
  stop-color: var(--svg-color--7c4f3f, #7C4F3F);
  stop-opacity: 0;
}

.a805jtb_d {
  stop-color: var(--svg-color--365c3e, #365C3E);
}

.ai95fabuh {
  stop-color: var(--svg-color--986b5a, #986B5A);
  stop-opacity: 0;
}

.al0tyek2y {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
}

.alim0f6wa {
  fill: var(--svg-color--2a191e, #2A191E);
  d: path("M10.93 4.579c.567-.6 1.637-.6 2.132-.51l.396 1.29c-.253-.04-.479.05-.668.234c-.449 1.26-1.99 1.956-2.704 2.146c-.148-1.492.109-2.38.845-3.16");
}

.ax9af2vtk {
  stop-color: var(--svg-color--875555, #875555);
  stop-opacity: 0;
}

.b4of-6bao {
  stop-color: var(--svg-color--e5d7d2, #E5D7D2);
}

.b9k-3ybvb {
  stop-color: var(--svg-color--6a4745, #6A4745);
}

.bgy-ndvjc {
  fill: var(--svg-color--845f59, #845F59);
  d: path("M20.827 11.641a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.bil-gwbpd {
  d: path("M18.979 10.268a.84.84 0 0 0-.231-.462l-.26.285l.117.228z");
}

.bjc-lxiwy {
  fill: var(--svg-color--000, #000);
  d: path("M14.327 10.386a.51.51 0 0 0-.51-.511a.51.51 0 0 0-.455.746h.904a.5.5 0 0 0 .061-.235");
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.bof3uzbpf {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
}

.bopproo0p {
  fill: var(--svg-color--47383d, #47383D);
  d: path("m18.406 6.386l-1.425.263a.688.688 0 1 1-.125-1.365h2.34c1.385 0 1.843 1.395 1.9 1.872a3.15 3.15 0 0 0-2.69-.77");
}

.brgj7qtnd {
  cx: 10.18px;
  cy: 21.606px;
  r: 0.762px;
}

.bvsk-i9dj {
  stop-color: var(--svg-color--cdc8ce, #CDC8CE);
}

.bxy9a_8wa {
  d: path("M20.61 25.837c.678-.6 1.716-.536 2.297.111l.69.735c.063.067.083.205-.023.27c-.91.563-1.996.492-2.66-.27l-.42-.583a.11.11 0 0 1 .009-.15z");
}

.bzn24qbzw {
  fill-rule: evenodd;
  d: path("M23.185 11.977c.213-.435.324-.921.324-1.427a3.3 3.3 0 0 0-.268-1.305h.005a3 3 0 0 0-.281-.513l-.002-.004a3.24 3.24 0 0 1-.527-1.77v-.01a3.3 3.3 0 0 0-3.299-3.3a.54.54 0 0 1-.455-.233A3.3 3.3 0 0 0 16 2.04a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233l-.085.001a3.3 3.3 0 0 0-3.214 3.298v.01a3.24 3.24 0 0 1-.527 1.771l-.002.004a3.3 3.3 0 0 0-.22 3.245a.52.52 0 0 1 0 .455a3.26 3.26 0 0 0-.324 1.407a3.213 3.213 0 0 0 3.218 3.218h8.582a3.213 3.213 0 0 0 3.218-3.218c0-.506-.121-.982-.324-1.407a.51.51 0 0 1 0-.455m-12.26-2.672h-.012l1.198 2.355c.124 2.803 1.217 0 3.889 0s3.836 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.674a.264.264 0 0 0-.461.051l-.082.194a2.3 2.3 0 0 1-1.292 1.276c-.236.122-.79.49-.81 1.438l.01.306z");
}

.c1nwhtznm {
  stop-color: var(--svg-color--45363a, #45363A);
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.ccrydivzf {
  d: path("m11.186 26.33l2.71-1.12l-.67-1.62c-.41-1-1.1-1.691-1.988-2.11c-.465-.19-.717.06-.797.24c-.3.82-.081 2.136.085 3z");
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cir-2tbku {
  d: path("M18.119 9.682c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.246.159-.359s.325-.135.389-.05");
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ck10erk2j {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M15.92 18.875c.395.01 1.357-.063 2.05-.442");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnrgi8b1a {
  stop-color: var(--svg-color--58843a, #58843A);
}

.crj44uotj {
  stop-color: var(--svg-color--996b5e, #996B5E);
}

.ct82q_bbh {
  stop-color: var(--svg-color--cac2c0, #CAC2C0);
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cyl8wapbv {
  stop-color: var(--svg-color--7c455c, #7C455C);
}

.d0ys9v7ll {
  cx: 13.547px;
  cy: 9.875px;
  rx: 0.39px;
  ry: 0.197px;
}

.d3coa7kai {
  d: path("M15.397 2.777c-1.133-.25-2.15.88-2.267 1.299c1.051 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.542 1.877.888c0-3.932-3.344-4.67-5.922-5.24z");
}

.d4sy-lw5d {
  d: path("M9.984 15.884c0-4.854 2.694-7.281 6.016-7.281s6.016 2.324 6.016 7.28v7.436H9.984z");
}

.d5fabsakk {
  stop-color: var(--svg-color--d7cfcf, #D7CFCF);
  stop-opacity: 0;
}

.d72oepody {
  fill-rule: evenodd;
  d: path("M15.972 4.393c-3.812 0-5.694 1.656-6.334 2.379a.775.775 0 0 1-1.16-1.027c.88-.996 3.165-2.902 7.494-2.902c4.41 0 6.608 1.915 7.54 2.876A.775.775 0 1 1 22.4 6.798c-.735-.757-2.556-2.405-6.428-2.405");
}

.d94uojbbb {
  stop-color: var(--svg-color--98766e, #98766E);
  stop-opacity: 0;
}

.da7h3oe0u {
  stop-color: var(--svg-color--743f5a, #743F5A);
  stop-opacity: 0;
}

.ddg3g7pcd {
  stop-color: var(--svg-color--cb5996, #CB5996);
}

.dg0-lwyyf {
  stop-color: var(--svg-color--98766e, #98766E);
}

.dl0nwov2w {
  stop-color: var(--svg-color--744c45, #744C45);
  stop-opacity: 0;
}

.dw40nqbxs {
  d: path("M9.15 20.494a11.2 11.2 0 0 1 4.31-2.048c.28-.06.48-.32.48-.61v-3.145c0-1.13.9-2.04 2.02-2.06c1.16-.02 2.1.95 2.1 2.1v3.105c0 .29.2.54.48.61a11.3 11.3 0 0 1 4.325 2.063a8.44 8.44 0 0 1-6.852 3.503a8.44 8.44 0 0 1-6.864-3.518");
}

.dz0-61bre {
  stop-color: var(--svg-color--487a38, #487A38);
}

.dz5hgfbwb {
  fill: var(--svg-color--3f6834, #3F6834);
  d: path("M21.819 23.438c.096.053.144.219.081.348l-.668 1.39c-.181.388-.526.926-.809 1.177c-.687.638-1.466.646-2.21.3a2.4 2.4 0 0 1-.481-.291a.97.97 0 0 1-.407.892c-.466.325-1.079.16-1.39-.3l-.258-.344a.042.042 0 0 0-.068.003l-.201.312a.966.966 0 0 1-1.374.35a.97.97 0 0 1-.241-1.415l.298-.438a.042.042 0 0 0-.027-.064l-.308-.056a.97.97 0 0 1-.799-1.173a.97.97 0 0 1 1.248-.708l.516.176a.042.042 0 0 0 .055-.042l-.025-.403c-.05-.558.514 1.048 1.08 1.04c.574-.009.81-1.664.81-1.062v.467c0 .028.028.048.055.04l.458-.157q.112-.041.223-.057l.036-.085l1.043.854c.063-.13.19-.198.295-.152c.711.327.494-.417.288.728c-.022.122.015.129.098.029c.74-.9 1.97-1.695 2.682-1.36");
}

.dzmucob_g {
  fill: var(--svg-color--352827, #352827);
  fill-rule: evenodd;
  d: path("m19.732 8.332l-.138.23za.268.268 0 0 1-.275.46l-.005-.003a1 1 0 0 0-.113-.058a3 3 0 0 0-.342-.135a2.3 2.3 0 0 0-1.072-.092a.268.268 0 1 1-.093-.528c.513-.09.988 0 1.328.11a3.3 3.3 0 0 1 .559.238l.009.005z");
}

.e-0jmrbwd {
  stop-color: var(--svg-color--fff967, #FFF967);
}

.e-twaac7b {
  stop-color: var(--svg-color--575455, #575455);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1762_b0a {
  d: path("M14.631 10.281c0-.288-.234-.48-.298-.539l-.288.28l.177.36z");
}

.e7aooyb9w {
  stop-color: var(--svg-color--825d5b, #825D5B);
}

.e8znlebid {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.391 9.222c.653 0 1.205.45 1.355 1.058a.274.274 0 0 1-.268.341h-2.23a.23.23 0 0 1-.228-.272c.126-.64.69-1.127 1.371-1.127");
}

.eatp636hk {
  stop-color: var(--svg-color--eee1dd, #EEE1DD);
}

.ehlybtbyr {
  stop-color: var(--svg-color--af3465, #AF3465);
}

.ejr-khbri {
  stop-color: var(--svg-color--cb5996, #CB5996);
  stop-opacity: 0;
}

.engxb26bh {
  fill: var(--svg-color--aaaeae, #AAAEAE);
  d: path("M19.688 26.002c.78-.46 1.787-.2 2.235.545l.538.852c.048.078.043.217-.074.261c-1 .38-2.053.105-2.561-.77l-.302-.651a.11.11 0 0 1 .037-.146z");
}

.eo_7g0bzd {
  stop-color: var(--svg-color--5a3638, #5A3638);
}

.eqonf-bpu {
  fill: var(--svg-color--000, #000);
  d: path("M17.673 10.386c0-.284.227-.511.511-.511a.51.51 0 0 1 .455.746h-.905a.46.46 0 0 1-.06-.235");
}

.f_r_72dts {
  stop-color: var(--svg-color--facc4a, #FACC4A);
}

.f-folhbcb {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.142 9.998c.266-.467.67-.835 1.538-.835c.38 0 .747.105 1.072.368c.27.218.233.495.025.6l-.556.317c-.652-.21-1.373-.24-2.079-.45");
}

.f5jafwbws {
  d: path("M12.712 23.201c.15-.67.84-1.06 1.5-.85l.62.211a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.267 1.09-1.277c.69-.01 1.18.527 1.18 1.25v.561a.05.05 0 0 0 .066.048l.55-.188c.64-.24 1.31.06 1.49.73c.17.65-.214 1.373-.884 1.493l-.457.1a.05.05 0 0 0-.03.079l.307.422c.44.52.34 1.32-.22 1.71s-1.296.193-1.67-.36l-.31-.413a.05.05 0 0 0-.081.003l-.242.375c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.526a.05.05 0 0 0-.032-.078l-.37-.066c-.67-.1-1.11-.75-.96-1.41");
}

.f86v59wxs {
  fill: var(--svg-color--352827, #352827);
  d: path("m12.602 8.79l-.004.002a.268.268 0 0 1-.276-.46l.002-.001l.003-.002l.01-.005a2 2 0 0 1 .148-.077c.098-.047.239-.107.41-.162c.34-.108.815-.2 1.328-.11a.268.268 0 1 1-.093.53a2.3 2.3 0 0 0-1.072.091a3 3 0 0 0-.434.181z");
}

.felc_fb-i {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
}

.fgurcxbqa {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.858 9.998c-.265-.467-.669-.835-1.537-.835c-.38 0-.747.105-1.073.368c-.269.218-.233.495-.024.6l.556.317c.651-.21 1.372-.24 2.078-.45");
}

.fjji9zbbw {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
  stop-opacity: 0;
}

.fk_o1xs8s {
  d: path("m13.196 29.961l-2.547-3.837l5.25-3.475l5.828 2.909l-2.922 4.403z");
}

.fo-imacds {
  fill: var(--svg-color--ffdd2c, #FFDD2C);
  d: path("M12.712 23.201c.15-.67.84-1.06 1.5-.85l.62.211a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.267 1.09-1.277c.69-.01 1.18.527 1.18 1.25v.561a.05.05 0 0 0 .066.048l.55-.188c.64-.24 1.31.06 1.49.73c.17.65-.214 1.373-.884 1.493l-.457.1a.05.05 0 0 0-.03.079l.307.422c.44.52.34 1.32-.22 1.71s-1.296.193-1.67-.36l-.31-.413a.05.05 0 0 0-.081.003l-.242.375c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.526a.05.05 0 0 0-.032-.078l-.37-.066c-.67-.1-1.11-.75-.96-1.41");
}

.fs9pa7bci {
  stop-color: var(--svg-color--6e494b, #6E494B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ftopcck0v {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.61 9.222c-.654 0-1.206.45-1.356 1.059c-.044.174.09.34.268.34h2.231a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.37-1.127");
}

.fx1tjiblm {
  stop-color: var(--svg-color--755041, #755041);
  stop-opacity: 0;
}

.fyyy25bfx {
  stop-color: var(--svg-color--7b5852, #7B5852);
  stop-opacity: 0;
}

.fzn5p4bte {
  stop-color: var(--svg-color--e7dedd, #E7DEDD);
}

.g0r7omboq {
  stop-color: var(--svg-color--474445, #474445);
  stop-opacity: 0;
}

.g22d_bc_z {
  stop-color: var(--svg-color--416b43, #416B43);
  stop-opacity: 0;
}

.g5d3hjacf {
  stop-color: var(--svg-color--4c4749, #4C4749);
}

.gcfqr7bfg {
  stop-color: var(--svg-color--714350, #714350);
  stop-opacity: 0;
}

.gi1yleb5l {
  stop-color: var(--svg-color--aca4a1, #ACA4A1);
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gn67s1beu {
  stop-color: var(--svg-color--ffef65, #FFEF65);
}

.h5j39cckv {
  d: path("M11.334 11.641a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.hbyh_lbnn {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m17.348 24.82l.907 1.18");
}

.he14dbbbc {
  stop-color: var(--svg-color--f38330, #F38330);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hpeo8yzih {
  stop-color: var(--svg-color--9d7e72, #9D7E72);
}

.hpzv-ab9a {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
  stop-opacity: 0;
}

.hr9jc16ta {
  stop-color: var(--svg-color--ffe24b, #FFE24B);
}

.hus9zqvbn {
  fill: var(--svg-color--2f1920, #2F1920);
  d: path("M15.397 2.777c-1.133-.25-2.15.88-2.267 1.299c1.051 3.545 3.713 3.35 6.34 3.059c1.572-.175 1.743.542 1.877.888c0-3.932-3.344-4.67-5.922-5.24z");
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i1hqu4kst {
  stop-color: var(--svg-color--ca992e, #CA992E);
}

.i4i_2ibui {
  fill: var(--svg-color--dca238, #DCA238);
  d: path("M15.87 25.387a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.i7kjncbis {
  stop-color: var(--svg-color--d35897, #D35897);
}

.iaefxbcet {
  stop-color: var(--svg-color--c9c5cd, #C9C5CD);
}

.ifzr0vvcb {
  stop-color: var(--svg-color--ffad67, #FFAD67);
}

.isiq9yb3m {
  stop-color: var(--svg-color--c46399, #C46399);
}

.ix_9o_9wu {
  d: path("M21.48 25.324c.063-.898.843-1.586 1.721-1.535l.99.06c.121 0 .162.157.149.206c-.176.967-.961 1.703-2 1.633l-.768-.097a.11.11 0 0 1-.102-.118z");
}

.j-elh2uvv {
  cx: 9.168px;
  cy: 20.528px;
  r: 0.762px;
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j9i7xp3bx {
  stop-color: var(--svg-color--cdc7c8, #CDC7C8);
}

.jaf6nfbfs {
  stop-color: var(--svg-color--a07a6f, #A07A6F);
  stop-opacity: 0;
}

.jidmdqsym {
  d: path("m15.618 10.206l-.532 1.7a.54.54 0 0 0 .521.7h.786a.54.54 0 0 0 .521-.7l-.532-1.7c-.113-.376-.645-.376-.764 0");
}

.jih6tvbze {
  stop-color: var(--svg-color--3e5d50, #3E5D50);
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jm8e13_st {
  stop-color: var(--svg-color--e1d6d3, #E1D6D3);
}

.jn8k7gbea {
  stop-color: var(--svg-color--693e41, #693E41);
  stop-opacity: 0;
}

.jplc2lvem {
  stop-color: var(--svg-color--7c455c, #7C455C);
  stop-opacity: 0;
}

.k_kfijbew {
  stop-color: var(--svg-color--ca992e, #CA992E);
  stop-opacity: 0;
}

.k13ak_bzi {
  d: path("M10.52 25.324c-.063-.898-.843-1.586-1.721-1.535l-.99.06c-.121 0-.162.157-.149.206c.176.967.961 1.703 2 1.633l.768-.097a.11.11 0 0 0 .102-.118z");
}

.k1xxa4bqz {
  stop-color: var(--svg-color--af246b, #AF246B);
  stop-opacity: 0;
}

.k8eqtnbpc {
  d: path("M20.827 12.176a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kcwstyspx {
  d: path("m20.799 26.33l-2.71-1.12l.67-1.62c.41-1 1.1-1.691 1.987-2.11c.466-.19.718.06.798.24c.3.82.081 2.136-.085 3z");
}

.ki4t9bbhh {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.098 21.055c.324 0 .758.376.758.86v.945");
}

.kitn3twkh {
  stop-color: var(--svg-color--5f363f, #5F363F);
}

.kv9fthb_h {
  stop-color: var(--svg-color--dfc7b5, #DFC7B5);
}

.l__dw9bpv {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
  stop-opacity: 0;
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l33l9dqgq {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l9b4opb5t {
  stop-color: var(--svg-color--338e58, #338E58);
  stop-opacity: 0;
}

.le6hrcb_e {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M16 13.479c-.52 0-1.01-.125-1.421-.345c-.141-.073-.292.09-.203.22a1.932 1.932 0 0 0 3.249 0c.088-.136-.063-.293-.203-.22c-.412.22-.896.345-1.422.345Z");
}

.lgjudcrkd {
  stop-color: var(--svg-color--413733, #413733);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ll4sw0vun {
  stop-color: var(--svg-color--24182d, #24182D);
}

.lvw96kbgx {
  fill: var(--svg-color--8a6058, #8A6058);
  d: path("m15.618 10.206l-.532 1.7a.54.54 0 0 0 .521.7h.786a.54.54 0 0 0 .521-.7l-.532-1.7c-.113-.376-.645-.376-.764 0");
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.m92tte26k {
  stop-color: var(--svg-color--e170ad, #E170AD);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg10me7tz {
  stop-color: var(--svg-color--794958, #794958);
  stop-opacity: 0;
}

.mmje--ohe {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.119 9.682c.063.085-.07.189-.22.302c-.152.113-.264.192-.328.107c-.063-.085.008-.246.159-.359s.325-.135.389-.05");
}

.movji7bnz {
  r: 0.762px;
}

.mpfjlio6c {
  stop-color: var(--svg-color--619951, #619951);
}

.mq6wd3bba {
  stop-color: var(--svg-color--433838, #433838);
  stop-opacity: 0;
}

.mrn0x9y7q {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.94 8.195c.322-.079 1.124-.04 1.66.344");
}

.mt9k2qzvi {
  stop-color: var(--svg-color--755041, #755041);
}

.mu5z5titl {
  stop-color: var(--svg-color--c6bebf, #C6BEBF);
}

.muovvys4e {
  stop-color: var(--svg-color--e2dfe3, #E2DFE3);
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.n0n4e7bnh {
  stop-color: var(--svg-color--f3f0ef, #F3F0EF);
}

.n1imc2b4i {
  stop-color: var(--svg-color--4f8436, #4F8436);
}

.n38nmb94x {
  fill: var(--svg-color--88014f, #88014F);
  d: path("M16 13.479c-.52 0-1.01-.125-1.421-.345c-.141-.073-.292.09-.203.22a1.932 1.932 0 0 0 3.249 0c.088-.136-.063-.293-.203-.22c-.412.22-.896.345-1.422.345");
}

.n50qojbrc {
  stop-color: var(--svg-color--734f43, #734F43);
}

.nbz8snbyn {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
  stop-opacity: 0;
}

.ndghkrcwe {
  stop-color: var(--svg-color--c3bbbb, #C3BBBB);
}

.ndnnww3sc {
  stroke: var(--svg-color--473c3c, #473C3C);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.149 8.195c-.323-.079-1.125-.04-1.661.344");
}

.ni-4se4rm {
  stop-color: var(--svg-color--836462, #836462);
}

.nof2xyhhe {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
  stop-opacity: 0;
}

.o_rd0acqn {
  fill: var(--svg-color--9b9da0, #9B9DA0);
  d: path("M9.134 24.173c.879-.051 1.658.636 1.72 1.534l.009.116c.31.044.61.175.862.397l.107.114a.11.11 0 0 1 .01.15l-.42.583c-.665.762-1.75.833-2.66.27c-.064-.05-.086-.203-.024-.27l.69-.735q.136-.151.302-.26c-.906-.06-1.574-.75-1.735-1.633c-.013-.05.028-.207.15-.207z");
}

.o38c5rykb {
  stop-color: var(--svg-color--ffef65, #FFEF65);
  stop-opacity: 0;
}

.o3wo53bzp {
  stop-color: var(--svg-color--5a3638, #5A3638);
  stop-opacity: 0;
}

.o9qsnlb6c {
  stop-color: var(--svg-color--1b572f, #1B572F);
  stop-opacity: 0;
}

.obmju7b-z {
  stop-color: var(--svg-color--d0246b, #D0246B);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ogqxd-bue {
  stop-color: var(--svg-color--1c151f, #1C151F);
}

.olqyf7fmb {
  stop-color: var(--svg-color--875e5e, #875E5E);
}

.opgioqbtx {
  stop-color: var(--svg-color--805c54, #805C54);
  stop-opacity: 0;
}

.osxg47drp {
  stop-color: var(--svg-color--743f5a, #743F5A);
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.p5ii0k_1a {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
  stop-opacity: 0;
}

.p7lh-mbjd {
  stop-color: var(--svg-color--7c4f3f, #7C4F3F);
}

.p88c31myn {
  stop-color: var(--svg-color--815a5b, #815A5B);
  stop-opacity: 0;
}

.paonnib9g {
  stop-color: var(--svg-color--474445, #474445);
}

.pbh041bmy {
  stop-color: var(--svg-color--af3465, #AF3465);
  stop-opacity: 0;
}

.pcz4s2bal {
  stop-color: var(--svg-color--1b572f, #1B572F);
}

.pe7y9ky3x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.109 4.025c.023.243.235 1.157.545 1.71");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pnga_4b2z {
  d: path("M20.827 11.641a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.pzpwlzysi {
  stop-color: var(--svg-color--8bc659, #8BC659);
  stop-opacity: 0;
}

.q01y-fb-l {
  d: path("M11.314 12.176a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.qgxdbybha {
  fill: var(--svg-color--c55496, #C55496);
  d: path("M8.528 22.79c-.076-.156-.018-.354.098-.419c.854-.403 2.333.553 3.222 1.633c.099.12.144.112.117-.035c-.248-1.376-.009-3.138.846-3.532c.126-.055.278.028.355.183l.753 1.631l.133.312c.111.292.303.838.336 1.134c.152 1.232-.46 2.09-1.43 2.538c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.949-.972-1.415z");
}

.qo7m0solq {
  d: path("M18.184 9.493a.892.892 0 0 1 .86 1.128H17.32a.896.896 0 0 1 .864-1.128");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.r_s898b6a {
  stop-color: var(--svg-color--b81560, #B81560);
}

.r_thblbtw {
  cx: 13.547px;
  cy: 9.875px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.r_v2kebuk {
  stop-color: var(--svg-color--181518, #181518);
  stop-opacity: 0;
}

.r3y-39nqq {
  stop-color: var(--svg-color--cbc7ca, #CBC7CA);
}

.rau9skumu {
  stop-color: var(--svg-color--de5390, #DE5390);
}

.rby1z7ber {
  stop-color: var(--svg-color--744c45, #744C45);
}

.rqn5r__rt {
  d: path("M5.062 16.461c0-8.812 4.89-13.218 10.922-13.218S26.906 7.46 26.906 16.46v13.5H5.062z");
}

.rsfcoybzb {
  stop-color: var(--svg-color--64a25a, #64A25A);
}

.ruz641x6w {
  stop-color: var(--svg-color--d76316, #D76316);
  stop-opacity: 0;
}

.s44dqacei {
  d: path("M23.457 22.79c.076-.156.018-.354-.098-.419c-.854-.403-2.334.553-3.222 1.633c-.099.12-.144.112-.117-.035c.247-1.376.009-3.138-.846-3.532c-.127-.055-.279.028-.355.183l-.754 1.631c-.044.107-.088.205-.132.312c-.111.292-.303.838-.336 1.134c-.152 1.232.46 2.09 1.43 2.538c.894.415 1.83.406 2.656-.36c.34-.303.754-.949.972-1.415z");
}

.sa_c7ns7l {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
}

.shep8_bdh {
  d: path("M27 29.961v-1c0-5.2-3.61-9.365-8.46-10.515a.63.63 0 0 1-.48-.61v-3.105c0-1.15-.94-2.12-2.1-2.1c-1.12.02-2.02.93-2.02 2.06v3.145c0 .29-.2.55-.48.61C8.61 19.586 5 23.761 5 28.961v1z");
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.t-y5i3b_t {
  stop-color: var(--svg-color--8ac463, #8AC463);
}

.t9k87pm2r {
  stop-color: var(--svg-color--875555, #875555);
}

.t9sj0nb-w {
  stop-color: var(--svg-color--825d5b, #825D5B);
  stop-opacity: 0;
}

.tgwkdpbql {
  stop-color: var(--svg-color--bab5b4, #BAB5B4);
}

.tqblnl2vv {
  stop-color: var(--svg-color--e3dede, #E3DEDE);
  stop-opacity: 0;
}

.tr7czpf3k {
  stop-color: var(--svg-color--413733, #413733);
  stop-opacity: 0;
}

.tv57cl-9q {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
}

.ty1ewib_q {
  stop-color: var(--svg-color--e170ad, #E170AD);
  stop-opacity: 0;
}

.u0w6z5q5o {
  d: path("M10.913 9.305h.012l-.01-.265l-.01-.307c.02-.948.574-1.316.81-1.438l.05-.02l.052-.021a2.3 2.3 0 0 0 1.19-1.235l.082-.193a.264.264 0 0 1 .461-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.082.087 1.135 1.332l-.118 3.073c-.124 2.803-2.312 4.685-4.984 4.685c-2.671 0-4.86-1.882-4.983-4.685z");
}

.u3ly29i0x {
  stop-color: var(--svg-color--af246b, #AF246B);
}

.uaxm8f1hq {
  stop-color: var(--svg-color--338e58, #338E58);
}

.uj7hgsb3u {
  stop-color: var(--svg-color--815a5b, #815A5B);
}

.ujdq-6enc {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
}

.up8l18w-p {
  stop-color: var(--svg-color--986b5a, #986B5A);
}

.uq7zq9b9u {
  stop-color: var(--svg-color--c46399, #C46399);
  stop-opacity: 0;
}

.uy9-hlbji {
  stop-color: var(--svg-color--fff967, #FFF967);
  stop-opacity: 0;
}

.v6xk-qbhz {
  d: path("M10.93 4.579c.567-.6 1.637-.6 2.132-.51l.396 1.29c-.253-.04-.479.05-.668.234c-.449 1.26-1.99 1.956-2.704 2.146c-.148-1.492.109-2.38.845-3.16");
}

.v9-8bpxan {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
}

.vbw-bobru {
  stop-color: var(--svg-color--533335, #533335);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.w4p6edc7q {
  fill: var(--svg-color--70404a, #70404A);
  d: path("m15.608 10.344l-.684 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.115-.376-.494-.376-.613 0");
}

.wa496n4py {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
  stop-opacity: 0;
}

.waj_poblt {
  fill: var(--svg-color--5f3c45, #5F3C45);
  d: path("M11.334 11.641a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.wg3eepbwp {
  stop-color: var(--svg-color--805c54, #805C54);
}

.wh23x9bjk {
  stop-color: var(--svg-color--fff763, #FFF763);
}

.whpxerb5a {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.434 22.602c.307.136.83.616.461 1.453");
}

.wkalc4bst {
  stop-color: var(--svg-color--d35897, #D35897);
  stop-opacity: 0;
}

.wrh2b4bbx {
  stop-color: var(--svg-color--7d4d48, #7D4D48);
}

.wsh5tsbcf {
  stop-color: var(--svg-color--836462, #836462);
  stop-opacity: 0;
}

.wso8oqi8u {
  stop-color: var(--svg-color--946c5d, #946C5D);
}

.wsyd1pyom {
  stop-color: var(--svg-color--fff763, #FFF763);
  stop-opacity: 0;
}

.x_ik4kbfh {
  stop-color: var(--svg-color--714350, #714350);
}

.x0qjlw0mb {
  d: path("M11.39 25.837c-.678-.6-1.716-.536-2.298.111l-.69.735c-.062.067-.04.22.024.27c.91.563 1.996.492 2.66-.27l.42-.583a.11.11 0 0 0-.009-.15z");
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xflvpmp1u {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
  stop-opacity: 0;
}

.xnros5bvd {
  stop-color: var(--svg-color--6a3842, #6A3842);
}

.xo240subg {
  stop-color: var(--svg-color--d76316, #D76316);
}

.xyi13834j {
  d: path("M13.816 9.493a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.y_9xrnb_b {
  stop-color: var(--svg-color--7b5852, #7B5852);
}

.y32ab_wii {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
  stop-opacity: 0;
}

.y8qpet1tz {
  stop-color: var(--svg-color--34673c, #34673C);
}

.yamoh3dov {
  stop-color: var(--svg-color--764e4c, #764E4C);
}

.ycrcotb4u {
  stop-color: var(--svg-color--986f60, #986F60);
  stop-opacity: 0;
}

.yhk8aqbmk {
  stop-color: var(--svg-color--e6dcda, #E6DCDA);
  stop-opacity: 0;
}

.yjp69hbuv {
  fill-rule: evenodd;
  d: path("M13.709 24.364a.913.913 0 0 1-.753-1.108a.91.91 0 0 1 1.178-.667l.617.21a.3.3 0 0 0 .396-.303l-.03-.484v-.007q-.019-.216.044-.404a.85.85 0 0 1 .8-.6c.532-.008.927.396.927 1v.561a.3.3 0 0 0 .396.284l.551-.187l.007-.003c.516-.193 1.023.047 1.16.56c.14.531-.183 1.092-.687 1.182l-.466.103a.3.3 0 0 0-.178.47l.312.43l.006.007a.92.92 0 0 1-.172 1.343c-.429.299-1.012.16-1.32-.295l-.316-.423a.3.3 0 0 0-.493.017l-.247.384l-.005.008a.91.91 0 0 1-1.294.33l-.001-.002a.92.92 0 0 1-.227-1.335l.005-.007l.362-.533a.3.3 0 0 0-.196-.464l-.369-.066z");
}

.z_qiivm8v {
  d: path("M15.993 25.254a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.z26rrllgi {
  stop-color: var(--svg-color--6e494b, #6E494B);
}

.z3hpt3mcq {
  stop-color: var(--svg-color--8bc659, #8BC659);
}

.z66p5h_5k {
  stop-color: var(--svg-color--1a1316, #1A1316);
}

.z87kcgb7t {
  stop-color: var(--svg-color--c23471, #C23471);
}

.zhj208b_d {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
}

.zl4k6m5yt {
  stop-color: var(--svg-color--f1eceb, #F1ECEB);
}

.zoq8fuaif {
  stop-color: var(--svg-color--986f60, #986F60);
}

.zpr5v7b1v {
  d: path("M8.528 22.79c-.076-.156-.018-.354.098-.419c.854-.403 2.333.553 3.222 1.633c.099.12.144.112.117-.035c-.248-1.376-.009-3.138.846-3.532c.126-.055.278.028.355.183l.753 1.631l.133.312c.111.292.303.838.336 1.134c.152 1.232-.46 2.09-1.43 2.538c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.949-.972-1.415z");
}

.zt2wz-bdr {
  fill: var(--svg-color--dc62a7, #DC62A7);
  d: path("M23.457 22.79c.076-.156.018-.354-.098-.419c-.854-.403-2.334.553-3.222 1.633c-.099.12-.144.112-.117-.035c.247-1.376.009-3.138-.846-3.532c-.127-.055-.279.028-.355.183l-.754 1.631c-.044.107-.088.205-.132.312c-.111.292-.303.838-.336 1.134c-.152 1.232.46 2.09 1.43 2.538c.894.415 1.83.406 2.656-.36c.34-.303.754-.949.972-1.415z");
}

.zxvvm-hti {
  stop-color: var(--svg-color--d9cabf, #D9CABF);
}

</style>
