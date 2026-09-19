<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iPscYib)"><path fill="url(#iRYUitd)" class="gs-o-sbpb"/><path fill="url(#irlzODe)" class="gs-o-sbpb"/><path fill="url(#iCcObzb)" class="gs-o-sbpb"/></g><g filter="url(#i88b3hI)"><path fill="url(#iDeIgBc)" class="hf78f8bed"/></g><path fill="url(#iC6kM0b)" class="fni0kxmoh"/><path fill="url(#in6Wedd)" class="fni0kxmoh"/><path fill="url(#itiuWqe)" class="fni0kxmoh"/><path fill="url(#i20UJye)" class="fni0kxmoh"/><g filter="url(#isSFdhC)"><path class="gxsh2bbec"/></g><g filter="url(#iCL2MGi)"><path class="fbklj41gq"/></g><g filter="url(#i4nzFDe)"><path fill="url(#ijg4mdd)" class="zac6tac9t"/><path fill="url(#irudRWB)" class="zac6tac9t"/><path fill="url(#iCGD3td)" class="zac6tac9t"/></g><g filter="url(#iyC0aQN)"><path fill="url(#ib1uGed)" class="ej7aivxnz"/><path fill="url(#iXjhv1c)" class="ej7aivxnz"/><path fill="url(#i8HyJQc)" class="ej7aivxnz"/></g><g filter="url(#i4MOibc)"><path fill="url(#i96o1xe)" class="p5z8qs95p"/><path fill="url(#iZtWsQc)" class="p5z8qs95p"/><path fill="url(#iR3AZ6n)" class="p5z8qs95p"/><path fill="url(#iK7cBxF)" class="p5z8qs95p"/><path fill="url(#ijwLbvc)" class="p5z8qs95p"/></g><path fill="url(#ijh0eju)" class="o33h0jnse"/><path fill="url(#imhF9we)" class="o33h0jnse"/><g filter="url(#i0oRkAc)"><path class="rv-oa3bkx"/></g><g filter="url(#iTe67je)"><path fill="url(#iNaiB9c)" class="teb498btn"/><path fill="url(#iii1Syd)" class="teb498btn"/></g><g filter="url(#iR9Yinb)"><path fill="url(#iB8iDnc)" class="oi7qg9buh"/><path fill="url(#iHSGUFg)" class="oi7qg9buh"/></g><circle fill="url(#ievWZMX)" class="qnto_7byk"/><circle fill="url(#i5lEzJc)" class="qnto_7byk"/><circle fill="url(#iAAvyQb)" transform="matrix(-1 0 0 1 22.919 20.326)" class="movji7bnz"/><circle fill="url(#iH86wby)" transform="matrix(-1 0 0 1 22.919 20.326)" class="movji7bnz"/><circle fill="url(#iircDge)" class="hbty0cbru"/><circle fill="url(#izM6NXd)" transform="matrix(-1 0 0 1 21.97 21.385)" class="movji7bnz"/><circle fill="url(#iGbM8pb)" transform="matrix(-1 0 0 1 21.97 21.385)" class="movji7bnz"/><path fill="url(#iq0hsBd)" class="z5jverbbh"/><g filter="url(#iYdyGLe)"><path class="wuj-im25o"/><path fill="url(#iaMGBse)" class="ink9qmy7e"/><path fill="url(#ivL5fud)" class="ink9qmy7e"/><path fill="url(#igGYCkd)" class="ink9qmy7e"/><path fill="url(#ifoxoyb)" class="ink9qmy7e"/><path fill="url(#i8N03tb)" class="ink9qmy7e"/></g><path fill="url(#iLp8SGd)" class="um-_idbbv"/><g filter="url(#iwSOwce)"><path class="zrnfx80km"/><path fill="url(#iw7V2Ob)" class="ujizhjb0v"/><path fill="url(#iV3Cxye)" class="ujizhjb0v"/></g><g filter="url(#iaecNre)"><path class="fgtpn31iv"/><path fill="url(#iBhyiGb)" class="ca-k7iojk"/><path fill="url(#iJXqXUc)" class="ca-k7iojk"/><path fill="url(#io5SzsN)" class="ca-k7iojk"/><path fill="url(#iBujZvb)" class="ca-k7iojk"/><path fill="url(#ijVAuhb)" class="ca-k7iojk"/></g><g filter="url(#ibna1Uc)"><path fill="url(#ijqiAie)" clip-rule="evenodd" class="pr83zn9it"/></g><g filter="url(#i76UZLc)"><path class="leqo8fosm"/></g><g filter="url(#inNzrjd)"><path fill="url(#iw9S2Rb)" class="tw5q5pbyq"/><path fill="url(#iowCoec)" class="tw5q5pbyq"/></g><g filter="url(#idLIBme)"><path stroke="url(#iekVMsr)" class="u4vifspin"/></g><g filter="url(#iXGbvRt)"><path stroke="url(#iqZMaUb)" class="g7ukm2_ss"/></g><g filter="url(#ii3Ztxd)"><path stroke="url(#iE3yUde)" class="uo7o7sb7z"/></g><g filter="url(#iphGu4c)"><path stroke="url(#iLT3ded)" class="fktoll--q"/></g><g filter="url(#iKlIyyR)"><circle fill="url(#il7cwXP)" class="gn6w60u5d"/></g><g filter="url(#iJornob)"><circle fill="url(#i7woutb)" class="fq6w-ob_b"/></g><g filter="url(#iuhbF4c)"><circle fill="url(#irjtxmb)" class="dpzh1bb9v"/><circle fill="url(#ikTMWFc)" class="dpzh1bb9v"/></g><g filter="url(#iP6Yvje)"><circle class="yif-93b_l"/><circle fill="url(#ijGPBXL)" class="l556c4wxv"/><circle fill="url(#iCqqOCe)" class="l556c4wxv"/></g><g filter="url(#itpNz1d)"><path fill="url(#iQKoKjc)" class="o2lee7bjg"/><path fill="url(#ibY1UBc)" class="o2lee7bjg"/><path fill="url(#ixJy0bc)" class="o2lee7bjg"/><path fill="url(#iHWGwwc)" class="o2lee7bjg"/><path fill="url(#iGRwNhD)" class="o2lee7bjg"/><path fill="url(#iKL2nUr)" class="o2lee7bjg"/></g><g filter="url(#iS0p6VB)"><path fill="url(#iXpVvfG)" class="gma_0ac5c"/></g><g filter="url(#iZw0OJb)"><path class="bck_6ub_m"/><path fill="url(#idE3eMd)" class="ek7x7ccll"/><path fill="url(#irRziUd)" class="ek7x7ccll"/><path fill="url(#ibbmBWn)" class="ek7x7ccll"/><path fill="url(#ihTfTDe)" class="ek7x7ccll"/></g><g filter="url(#iXj7LEH)"><path class="yf4d67bjr"/></g><g filter="url(#iwpk7bd)"><path class="ylcb9tbto"/><path fill="url(#iJAvRMd)" class="zv3wqwqhr"/><path fill="url(#iuqbnod)" class="zv3wqwqhr"/><path fill="url(#ihptwrE)" class="zv3wqwqhr"/><path fill="url(#iT8vFEd)" class="zv3wqwqhr"/></g><g filter="url(#iEmRgPb)"><path fill="url(#i2qoqie)" class="vzukf6b2o"/></g><g filter="url(#ivBuluc)"><path stroke="url(#iiVlttg)" class="jffzfdc1k"/></g><path class="uqobvi_6e"/><g filter="url(#iVLh2sc)"><path class="t_ye_u0tg"/></g><g filter="url(#ibdc3xd)"><path class="cjelnlzle"/></g><path class="xiwsuvb3u"/><path fill="url(#ipITzfK)" class="herc_pb_k"/><path class="yoe1cjj0j"/><g filter="url(#iveGCsc)"><path class="vta0pui_z"/><path fill="url(#iqPAYfb)" class="jdz_80b2w"/></g><g filter="url(#ignrlSc)"><path fill="url(#iE9tUnd)" class="g-k0mcb6t"/></g><path class="d_ojwwbxu"/><path fill="url(#ihh8Oce)" class="d2xv2f4xu"/><path class="rid712b8b"/><g filter="url(#iMkJWab)"><path fill="url(#iWAiPyc)" class="ky8zaobtn"/></g><g filter="url(#i3bGpFb)"><ellipse transform="rotate(-27.914 13.515 9.962)" class="x977d-55d"/><ellipse fill="url(#iZrVB5b)" transform="rotate(-27.914 13.515 9.962)" class="t6_s8eb8a"/></g><g filter="url(#iG1plBQ)"><path stroke="url(#ix9hHBd)" class="c--op8bwm"/></g><g filter="url(#iOM8cUb)"><path stroke="url(#iBwNvkd)" class="i20nf997e"/></g><g filter="url(#i8t3dXb)"><path stroke="url(#iXJUCvb)" class="cslg9yb_i"/></g><g filter="url(#iGO4WSd)"><path fill="url(#ibBZIfd)" clip-rule="evenodd" class="ejwbz2z3n"/><path fill="url(#i3s9rJb)" clip-rule="evenodd" class="ejwbz2z3n"/></g><defs><radialGradient id="irlzODe" cx="0" cy="0" r="1" gradientTransform="rotate(-126.573 19.812 6.979)scale(14.4752 12.6607)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="sa_c7ns7l"/><stop offset="1" class="xflvpmp1u"/></radialGradient><radialGradient id="iCcObzb" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 -5.375 4.67303 6.03148 5.7 25.548)" gradientUnits="userSpaceOnUse"><stop class="zhj208b_d"/><stop offset="1" class="y32ab_wii"/></radialGradient><radialGradient id="iC6kM0b" cx="0" cy="0" r="1" gradientTransform="rotate(155.653 10.161 15.692)scale(12.2796 19.1721)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="vc--wpv5i"/><stop offset="1" class="iaefxbcet"/></radialGradient><radialGradient id="itiuWqe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09375 1.15624 -3.57275 -6.46962 12.762 27.924)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="v9-8bpxan"/><stop offset="1" class="p5ii0k_1a"/></radialGradient><radialGradient id="i20UJye" cx="0" cy="0" r="1" gradientTransform="matrix(-3.625 0 0 -3.8125 9.856 24.08)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="tv57cl-9q"/><stop offset="1" class="nof2xyhhe"/></radialGradient><radialGradient id="irudRWB" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26562 -1.93554 2.61071 -1.7071 23.356 25.718)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="iCGD3td" cx="0" cy="0" r="1" gradientTransform="rotate(155.556 9.647 14.588)scale(1.32158 .2597)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="iXjhv1c" cx="0" cy="0" r="1" gradientTransform="matrix(.42186 -1.97502 3.24628 .6934 21.761 27.22)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="l9b4opb5t"/><stop offset=".989" class="uaxm8f1hq"/></radialGradient><radialGradient id="i8HyJQc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1139 -.45312 .07627 -.1875 23.728 26.783)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="i96o1xe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.95206 -2.46677 3.46444 -9.76378 21.531 21.501)" gradientUnits="userSpaceOnUse"><stop class="mt5e72-yt"/><stop offset="1" class="i_w-uabpc"/></radialGradient><radialGradient id="iZtWsQc" cx="0" cy="0" r="1" gradientTransform="matrix(.0287 2.22817 -1.66026 .02139 16.729 16.55)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="l3byadclu"/><stop offset="1" class="u-l7gqbnl"/></radialGradient><radialGradient id="iR3AZ6n" cx="0" cy="0" r="1" gradientTransform="matrix(-3.10937 .98438 -.41833 -1.3214 16.117 16.575)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="nhvn8xbgd"/><stop offset="1" class="vt544m69k"/></radialGradient><radialGradient id="iK7cBxF" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07223 -.6455 .5202 -.8641 22.585 20.724)" gradientUnits="userSpaceOnUse"><stop class="cyqt__gil"/><stop offset="1" class="yvysc04cm"/></radialGradient><radialGradient id="ijwLbvc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.96875 -.73075 0 14.117 16.567)" gradientUnits="userSpaceOnUse"><stop class="rb6miyacc"/><stop offset="1" class="onrup1btv"/></radialGradient><radialGradient id="ijh0eju" cx="0" cy="0" r="1" gradientTransform="rotate(30.491 -40.582 35.843)scale(7.14423 9.27511)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="a805jtb_d"/><stop offset=".81" class="mpfjlio6c"/></radialGradient><radialGradient id="iii1Syd" cx="0" cy="0" r="1" gradientTransform="rotate(-56.82 28.094 4.869)scale(2.3126 3.1193)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="iHSGUFg" cx="0" cy="0" r="1" gradientTransform="matrix(-.42043 -1.9751 3.23141 -.68786 10.244 27.22)" gradientUnits="userSpaceOnUse"><stop offset=".609" class="o9qsnlb6c"/><stop offset=".948" class="pcz4s2bal"/></radialGradient><radialGradient id="ievWZMX" cx="0" cy="0" r="1" gradientTransform="rotate(141.833 1.33 11.758)scale(1.27689)" gradientUnits="userSpaceOnUse"><stop class="b4of-6bao"/><stop offset="1" class="r3y-39nqq"/></radialGradient><radialGradient id="i5lEzJc" cx="0" cy="0" r="1" gradientTransform="rotate(90 -5.386 14.553)scale(1.25098)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="d5fabsakk"/><stop offset="1" class="ndghkrcwe"/></radialGradient><radialGradient id="iAAvyQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.17188 .58594 -.45305 .9061 .052 .516)" gradientUnits="userSpaceOnUse"><stop class="n0n4e7bnh"/><stop offset="1" class="jm8e13_st"/></radialGradient><radialGradient id="iH86wby" cx="0" cy="0" r="1" gradientTransform="matrix(.66407 -1.01563 1.1175 .73068 .52 1.063)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yhk8aqbmk"/><stop offset="1" class="zxvvm-hti"/></radialGradient><radialGradient id="iircDge" cx="0" cy="0" r="1" gradientTransform="rotate(139.138 1.367 12.614)scale(1.3016)" gradientUnits="userSpaceOnUse"><stop class="eatp636hk"/><stop offset="1" class="tgwkdpbql"/></radialGradient><radialGradient id="izM6NXd" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07031 -1.1661 1.0895 .298 .379)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="zl4k6m5yt"/><stop offset="1" class="j9i7xp3bx"/></radialGradient><radialGradient id="iGbM8pb" cx="0" cy="0" r="1" gradientTransform="matrix(1.07812 -.64844 .589 .9793 .391 .926)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="tqblnl2vv"/><stop offset=".964" class="kv9fthb_h"/></radialGradient><radialGradient id="iq0hsBd" cx="0" cy="0" r="1" gradientTransform="rotate(69.815 -10.306 19.324)scale(2.04763 .82994)" gradientUnits="userSpaceOnUse"><stop class="z87kcgb7t"/><stop offset=".853" class="r_s898b6a"/></radialGradient><radialGradient id="iaMGBse" cx="0" cy="0" r="1" gradientTransform="rotate(67.353 -9.226 20.179)scale(4.0633 .80773)" gradientUnits="userSpaceOnUse"><stop class="i7kjncbis"/><stop offset="1" class="wkalc4bst"/></radialGradient><radialGradient id="ivL5fud" cx="0" cy="0" r="1" gradientTransform="matrix(1.97895 1.21874 -.15017 .24384 9.482 22.923)" gradientUnits="userSpaceOnUse"><stop class="ddg3g7pcd"/><stop offset="1" class="ejr-khbri"/></radialGradient><radialGradient id="igGYCkd" cx="0" cy="0" r="1" gradientTransform="rotate(-118.794 14.149 9.18)scale(2.33566 5.83179)" gradientUnits="userSpaceOnUse"><stop offset=".268" class="isiq9yb3m"/><stop offset="1" class="uq7zq9b9u"/></radialGradient><radialGradient id="ifoxoyb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12499 1.3125 -.4864 -.4169 14.278 24.721)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="ehlybtbyr"/><stop offset="1" class="pbh041bmy"/></radialGradient><radialGradient id="i8N03tb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64063 -.62499 .30595 -.80313 14.31 24.501)" gradientUnits="userSpaceOnUse"><stop class="u3ly29i0x"/><stop offset="1" class="k1xxa4bqz"/></radialGradient><radialGradient id="iLp8SGd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03126 2.5625 -1.3029 -.52434 21.528 21.72)" gradientUnits="userSpaceOnUse"><stop class="rau9skumu"/><stop offset="1" class="obmju7b-z"/></radialGradient><radialGradient id="iw7V2Ob" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 .51562 -.16532 -.21542 23.294 22.626)" gradientUnits="userSpaceOnUse"><stop class="m92tte26k"/><stop offset="1" class="ty1ewib_q"/></radialGradient><radialGradient id="iV3Cxye" cx="0" cy="0" r="1" gradientTransform="matrix(.58243 3.00041 -1.02662 .19928 19.588 20.64)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="l33l9dqgq"/><stop offset="1" class="fjji9zbbw"/></radialGradient><radialGradient id="iBhyiGb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 2.3125 -1.56386 -.69739 16.794 21.205)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="iJXqXUc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96008 .75001 -.74136 -1.93748 19.285 22.892)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="ijqiAie" cx="0" cy="0" r="1" gradientTransform="rotate(111.14 1.336 16.592)scale(6.15203 6.32964)" gradientUnits="userSpaceOnUse"><stop class="hr9jc16ta"/><stop offset="1" class="f_r_72dts"/></radialGradient><radialGradient id="iw9S2Rb" cx="0" cy="0" r="1" gradientTransform="matrix(-.8047 .60938 -.52546 -.69388 16.388 23.767)" gradientUnits="userSpaceOnUse"><stop class="ifzr0vvcb"/><stop offset=".808" class="he14dbbbc"/></radialGradient><radialGradient id="iowCoec" cx="0" cy="0" r="1" gradientTransform="matrix(.17187 -1.1 1.36133 .2127 15.731 25.154)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="xo240subg"/><stop offset="1" class="ruz641x6w"/></radialGradient><radialGradient id="il7cwXP" cx="0" cy="0" r="1" gradientTransform="matrix(1.75471 0 0 3.07077 9.554 10.74)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="ikTMWFc" cx="0" cy="0" r="1" gradientTransform="matrix(.82663 -.60192 .68701 .9435 21.107 10.475)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="ijGPBXL" cx="0" cy="0" r="1" gradientTransform="matrix(.8212 -1.5104 .88405 .48065 20.694 11.562)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="iCqqOCe" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -2.692 30.581)scale(.3648 .47028)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="ibY1UBc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.55886 -11.6182 0 16 8.815)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="shu058b7p"/><stop offset="1" class="r-opspb2k"/></radialGradient><radialGradient id="iGRwNhD" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30697 1.60858 0 18.316 9.468)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="iKL2nUr" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.39075 1.72952 0 13.759 9.435)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="idE3eMd" cx="0" cy="0" r="1" gradientTransform="rotate(-74.899 14.488 -9.945)scale(3.06211 1.13553)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="irRziUd" cx="0" cy="0" r="1" gradientTransform="rotate(5.258 -43.74 205.776)scale(3.84067 2.0651)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="ibbmBWn" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.67903 -2.60035 0 15.97 2.14)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="ihTfTDe" cx="0" cy="0" r="1" gradientTransform="matrix(3.07368 -2.25248 3.5289 4.81545 9.522 8.956)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iT8vFEd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .19688 -.63254 0 16.298 12.347)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="ipITzfK" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81106 -1.29009 0 18.149 10.058)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iqPAYfb" cx="0" cy="0" r="1" gradientTransform="matrix(-.23184 -.29876 .41132 -.3192 17.92 10.142)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ihh8Oce" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8111 -1.29015 0 13.787 10.058)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iZrVB5b" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.809 -1.507)scale(.49399 .59379)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i3s9rJb" cx="0" cy="0" r="1" gradientTransform="rotate(118.072 9.692 8.546)scale(.92969 16.1409)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="al0tyek2y"/><stop offset="1" class="nbz8snbyn"/></radialGradient><filter id="iPscYib" width="21.944" height="26.818" x="4.962" y="3.142" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.952941 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3423"/></filter><filter id="i88b3hI" width="12.631" height="14.916" x="9.484" y="8.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.811765 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3423"/><feGaussianBlur result="effect2_foregroundBlur_4002_3423" stdDeviation=".05"/></filter><filter id="isSFdhC" width="5.874" height="5.537" x="6.993" y="23.07" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3423" stdDeviation=".5"/></filter><filter id="iCL2MGi" width="4.98" height="4.054" x="18.51" y="24.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3423" stdDeviation=".5"/></filter><filter id="i4nzFDe" width="2.973" height="2.006" x="21.47" y="23.585" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3423"/></filter><filter id="iyC0aQN" width="3.281" height="2" x="20.468" y="25.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3423"/></filter><filter id="i4MOibc" width="13.965" height="11.381" x="9.149" y="12.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.623529 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3423"/></filter><filter id="i0oRkAc" width="10.996" height="6.432" x="11.932" y="21.897" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3423" stdDeviation=".5"/></filter><filter id="iTe67je" width="2.973" height="2.006" x="7.658" y="23.585" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3423"/></filter><filter id="iR9Yinb" width="3.266" height="2" x="8.366" y="25.222" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3423"/></filter><filter id="iYdyGLe" width="6.218" height="6.789" x="8.343" y="19.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.227451 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3423"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.141176 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3423" result="effect2_innerShadow_4002_3423"/></filter><filter id="iwSOwce" width="6.218" height="6.639" x="17.574" y="19.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.239216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3423"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.301961 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3423" result="effect2_innerShadow_4002_3423"/></filter><filter id="iaecNre" width="6.702" height="6.417" x="12.683" y="20.651" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.619608 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3423"/></filter><filter id="ibna1Uc" width="6.703" height="6.517" x="12.633" y="20.601" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3423" stdDeviation=".15"/></filter><filter id="i76UZLc" width="3.2" height="3.2" x="14.271" y="22.585" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3423" stdDeviation=".25"/></filter><filter id="inNzrjd" width="2.35" height="2.35" x="14.893" y="22.954" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.521569 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3423"/></filter><filter id="idLIBme" width="1.458" height="2.505" x="15.848" y="20.504" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3423" stdDeviation=".125"/></filter><filter id="iXGbvRt" width="1.724" height="1.924" x="16.94" y="24.348" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3423" stdDeviation=".125"/></filter><filter id="ii3Ztxd" width="1.368" height="2.217" x="18.104" y="22.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3423" stdDeviation=".125"/></filter><filter id="iphGu4c" width="3.55" height="1.942" x="15.171" y="17.582" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3423" stdDeviation=".25"/></filter><filter id="iKlIyyR" width="3.539" height="3.339" x="9.554" y="9.071" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3423"/></filter><filter id="iJornob" width="2.99" height="2.99" x="9.728" y="9.246" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3423" stdDeviation=".25"/></filter><filter id="iuhbF4c" width="3.589" height="3.589" x="19.066" y="8.821" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3423"/></filter><filter id="iP6Yvje" width="2.99" height="2.99" x="19.24" y="9.246" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3423" stdDeviation=".25"/></filter><filter id="itpNz1d" width="10.373" height="12.277" x="10.813" y="5.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3423"/></filter><filter id="iS0p6VB" width="8.246" height="7.066" x="14.14" y="3.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3423" stdDeviation="1"/></filter><filter id="iZw0OJb" width="12.601" height="8.543" x="9.67" y="1.639" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3423"/></filter><filter id="iXj7LEH" width="3.26" height="4.181" x="14.101" y="9.585" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3423" stdDeviation=".375"/></filter><filter id="iwpk7bd" width="2.377" height="3.181" x="14.782" y="9.922" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3423" stdDeviation=".125"/></filter><filter id="iEmRgPb" width="2.377" height="3.181" x="14.782" y="9.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3423" stdDeviation=".125"/></filter><filter id="ivBuluc" width="3.617" height="1.472" x="14.162" y="13.324" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3423" stdDeviation=".05"/></filter><filter id="iVLh2sc" width="2.979" height="1.873" x="17.152" y="7.092" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3423"/></filter><filter id="ibdc3xd" width="2.98" height="1.873" x="12.005" y="7.092" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3423"/></filter><filter id="iveGCsc" width=".787" height=".696" x="17.415" y="9.618" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3423" stdDeviation=".05"/></filter><filter id="ignrlSc" width=".891" height=".913" x="18.255" y="9.693" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3423" stdDeviation=".1"/></filter><filter id="iMkJWab" width=".986" height="1.04" x="13.813" y="9.63" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3423" stdDeviation=".1"/></filter><filter id="i3bGpFb" width=".913" height=".704" x="13.059" y="9.61" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3423" stdDeviation=".05"/></filter><filter id="iG1plBQ" width="3.099" height="1.681" x="17.006" y="7.217" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3423" stdDeviation=".25"/></filter><filter id="iOM8cUb" width="3.177" height="1.738" x="11.787" y="7.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3423" stdDeviation=".25"/></filter><filter id="i8t3dXb" width="1.008" height="2.269" x="10.805" y="5.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3423" stdDeviation=".125"/></filter><filter id="iGO4WSd" width="15.448" height="4.54" x="8.283" y="2.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.694118 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3423"/></filter><linearGradient id="iRYUitd" x1="26.906" x2="11.7" y1="11.423" y2="21.423" gradientUnits="userSpaceOnUse"><stop class="fzn5p4bte"/><stop offset="1" class="mu5z5titl"/></linearGradient><linearGradient id="iDeIgBc" x1="20.7" x2="10.387" y1="17.329" y2="17.329" gradientUnits="userSpaceOnUse"><stop class="ct82q_bbh"/><stop offset="1" class="gi1yleb5l"/></linearGradient><linearGradient id="in6Wedd" x1="14.887" x2="14.887" y1="30.799" y2="29.517" gradientUnits="userSpaceOnUse"><stop class="ujdq-6enc"/><stop offset="1" class="hpzv-ab9a"/></linearGradient><linearGradient id="ijg4mdd" x1="23.649" x2="21.867" y1="25.72" y2="24.31" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="ib1uGed" x1="22.95" x2="21.169" y1="27.305" y2="25.611" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="imhF9we" x1="12.653" x2="13.255" y1="29.189" y2="28.845" gradientUnits="userSpaceOnUse"><stop class="jih6tvbze"/><stop offset="1" class="g22d_bc_z"/></linearGradient><linearGradient id="iNaiB9c" x1="7.856" x2="9.361" y1="24.204" y2="26.024" gradientUnits="userSpaceOnUse"><stop class="n1imc2b4i"/><stop offset="1" class="dz0-61bre"/></linearGradient><linearGradient id="iB8iDnc" x1="9.062" x2="10.843" y1="27.304" y2="25.619" gradientUnits="userSpaceOnUse"><stop class="cnrgi8b1a"/><stop offset="1" class="y8qpet1tz"/></linearGradient><linearGradient id="io5SzsN" x1="14.919" x2="16.7" y1="27.068" y2="22.799" gradientUnits="userSpaceOnUse"><stop class="i1hqu4kst"/><stop offset="1" class="k_kfijbew"/></linearGradient><linearGradient id="iBujZvb" x1="13.356" x2="16.981" y1="22.83" y2="23.517" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="ijVAuhb" x1="17.231" x2="16.325" y1="26.83" y2="25.08" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="iekVMsr" x1="16.477" x2="16.477" y1="20.752" y2="22.759" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="iqZMaUb" x1="17.286" x2="18.153" y1="24.806" y2="26.009" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset="0" class="gn67s1beu"/><stop offset=".739" class="gn67s1beu"/><stop offset="1" class="o38c5rykb"/></linearGradient><linearGradient id="iE3yUde" x1="18.728" x2="18.728" y1="22.338" y2="23.955" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="iLT3ded" x1="16.132" x2="20.117" y1="18.95" y2="17.778" gradientUnits="userSpaceOnUse"><stop class="s_ql7obry"/><stop offset="1" class="zpmzd2b_c"/></linearGradient><linearGradient id="i7woutb" x1="11.223" x2="10.582" y1="11.019" y2="11.019" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="irjtxmb" x1="21.822" x2="21.003" y1="9.649" y2="12.185" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="iQKoKjc" x1="20.006" x2="12.37" y1="11.129" y2="12.267" gradientUnits="userSpaceOnUse"><stop class="z8y6fgvmn"/><stop offset="1" class="tqgh1edwg"/></linearGradient><linearGradient id="ixJy0bc" x1="10.329" x2="13.686" y1="12.656" y2="12.77" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="iHWGwwc" x1="10.575" x2="12.456" y1="13.825" y2="13.758" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="iXpVvfG" x1="15.439" x2="23.582" y1="8.145" y2="5.229" gradientUnits="userSpaceOnUse"><stop class="sbbw_6vcc"/><stop offset="1" class="b7cutjkii"/></linearGradient><linearGradient id="iJAvRMd" x1="15.106" x2="16.044" y1="11.789" y2="11.789" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="iuqbnod" x1="16.909" x2="15.883" y1="12.111" y2="12.096" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="ihptwrE" x1="16.165" x2="16.165" y1="12.853" y2="12.28" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="i2qoqie" x1="15.97" x2="15.97" y1="10.009" y2="11.111" gradientUnits="userSpaceOnUse"><stop class="k7u9-obow"/><stop offset="1" class="y7_wd5mpc"/></linearGradient><linearGradient id="iiVlttg" x1="14.933" x2="15.368" y1="14.469" y2="13.781" gradientUnits="userSpaceOnUse"><stop class="lw4wqxbbr"/><stop offset=".663" class="f_sjqtbko"/></linearGradient><linearGradient id="iE9tUnd" x1="18.927" x2="18.613" y1="10.112" y2="10.305" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iWAiPyc" x1="14.53" x2="14.216" y1="10.112" y2="10.305" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ix9hHBd" x1="18.942" x2="18.522" y1="7.972" y2="7.114" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iBwNvkd" x1="13.638" x2="12.449" y1="7.845" y2="7.346" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="iXJUCvb" x1="11.309" x2="11.309" y1="5.83" y2="7.987" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><linearGradient id="ibBZIfd" x1="20.481" x2="8.544" y1="3.579" y2="7.267" gradientUnits="userSpaceOnUse"><stop class="muovvys4e"/><stop offset="1" class="bvsk-i9dj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-with-veil-light" /></template>
<style>
.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.a805jtb_d {
  stop-color: var(--svg-color--365c3e, #365C3E);
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.al0tyek2y {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.b4of-6bao {
  stop-color: var(--svg-color--e5d7d2, #E5D7D2);
}

.b7cutjkii {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
  stop-opacity: 0;
}

.bck_6ub_m {
  fill: var(--svg-color--242324, #242324);
  d: path("m20.789 4.262l.429.214c.75.373 1.18 1.226 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.054-.907.107-1.44c.044-.433-.032-.565-.429-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.215-.48-.43-.534c-.643-.16-1.984-.426-3.915-.426c-1.93 0-3.271.266-3.915.426a.52.52 0 0 0-.43.534v.853c0 .32-.106.64-.375.853l-.16.16c-.215.16-.322.48-.322.747c.053.586.107 1.44.107 1.44l-.05-.002a.63.63 0 0 1-.594-.532l-.59-3.04c-.107-.853.322-1.706 1.073-2.08l.43-.213c.267-.16.536-.373.804-.586l.965-1.013c.59-.534 1.448-.694 2.2-.32a2.94 2.94 0 0 0 1.662 0c.804-.267 1.716-.054 2.36.533l.804.8c.215.266.483.426.805.586");
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvsk-i9dj {
  stop-color: var(--svg-color--cdc8ce, #CDC8CE);
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
}

.c--op8bwm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.63 7.876c.43-.076 1.27-.054 1.85.397");
}

.ca-k7iojk {
  d: path("M12.712 23.101c.15-.67.84-1.06 1.5-.85l.62.211a.05.05 0 0 0 .066-.05l-.03-.485c-.06-.67.41-1.266 1.09-1.276c.69-.01 1.18.526 1.18 1.25v.561a.05.05 0 0 0 .066.047l.55-.187c.64-.24 1.31.059 1.49.729c.17.65-.214 1.374-.884 1.494l-.457.1a.05.05 0 0 0-.03.079l.307.422c.44.52.34 1.32-.22 1.71s-1.296.193-1.67-.36l-.31-.413a.05.05 0 0 0-.081.003l-.242.375c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.526a.05.05 0 0 0-.032-.078l-.37-.066c-.67-.1-1.11-.75-.96-1.41");
}

.cjelnlzle {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M12.197 8.02h.002l.002-.002l.004-.004l.012-.01a1.4 1.4 0 0 1 .155-.107c.1-.062.24-.14.42-.21a2.83 2.83 0 0 1 1.492-.159a.534.534 0 0 1-.166 1.055a1.77 1.77 0 0 0-.934.096a1.5 1.5 0 0 0-.308.165a.534.534 0 0 1-.679-.823");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnrgi8b1a {
  stop-color: var(--svg-color--58843a, #58843A);
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.cslg9yb_i {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M11.438 5.93v.897c-.008.148-.07.48-.258.621");
}

.ct82q_bbh {
  stop-color: var(--svg-color--cac2c0, #CAC2C0);
}

.cyqt__gil {
  stop-color: var(--svg-color--f3ba97, #F3BA97);
}

.d_ojwwbxu {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.577 9.31c-.652 0-1.204.45-1.354 1.058c-.045.174.09.34.268.34h2.23a.23.23 0 0 0 .227-.271a1.4 1.4 0 0 0-1.37-1.128");
}

.d2xv2f4xu {
  d: path("M13.784 9.582a.892.892 0 0 0-.86 1.127h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.892");
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d5fabsakk {
  stop-color: var(--svg-color--d7cfcf, #D7CFCF);
  stop-opacity: 0;
}

.ddg3g7pcd {
  stop-color: var(--svg-color--cb5996, #CB5996);
}

.dpzh1bb9v {
  cx: 20.735px;
  cy: 10.74px;
  r: 1.669px;
}

.dz0-61bre {
  stop-color: var(--svg-color--487a38, #487A38);
}

.e-0jmrbwd {
  stop-color: var(--svg-color--fff967, #FFF967);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.eatp636hk {
  stop-color: var(--svg-color--eee1dd, #EEE1DD);
}

.ehlybtbyr {
  stop-color: var(--svg-color--af3465, #AF3465);
}

.ej7aivxnz {
  d: path("M20.61 25.736c.678-.6 1.716-.535 2.297.112l.69.734c.063.068.083.205-.023.27c-.91.563-1.996.493-2.66-.27l-.42-.583a.11.11 0 0 1 .009-.15z");
}

.ejr-khbri {
  stop-color: var(--svg-color--cb5996, #CB5996);
  stop-opacity: 0;
}

.ejwbz2z3n {
  fill-rule: evenodd;
  d: path("M15.972 4.292c-3.812 0-5.694 1.656-6.334 2.379a.775.775 0 1 1-1.16-1.027c.88-.996 3.165-2.902 7.494-2.902c4.41 0 6.608 1.914 7.54 2.876A.775.775 0 1 1 22.4 6.697c-.735-.758-2.556-2.405-6.428-2.405");
}

.ek7x7ccll {
  d: path("m20.789 4.262l.429.214c.75.373 1.18 1.226 1.019 2.133l-.59 3.04c-.053.314-.26.525-.572.533h-.018s.054-.907.107-1.44c.044-.433-.032-.565-.429-.96c-.214-.213-.375-.533-.375-.853v-.853c0-.267-.215-.48-.43-.534c-.643-.16-1.984-.426-3.915-.426c-1.93 0-3.271.266-3.915.426a.52.52 0 0 0-.43.534v.853c0 .32-.106.64-.375.853l-.16.16c-.215.16-.322.48-.322.747c.053.586.107 1.44.107 1.44l-.05-.002a.63.63 0 0 1-.594-.532l-.59-3.04c-.107-.853.322-1.706 1.073-2.08l.43-.213c.267-.16.536-.373.804-.586l.965-1.013c.59-.534 1.448-.694 2.2-.32a2.94 2.94 0 0 0 1.662 0c.804-.267 1.716-.054 2.36.533l.804.8c.215.266.483.426.805.586");
}

.f_r_72dts {
  stop-color: var(--svg-color--facc4a, #FACC4A);
}

.f_sjqtbko {
  stop-color: var(--svg-color--ebb2a3, #EBB2A3);
  stop-opacity: 0;
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.fbklj41gq {
  fill: var(--svg-color--aaaeae, #AAAEAE);
  d: path("M19.688 25.902c.78-.46 1.787-.2 2.235.545l.538.852c.048.078.043.216-.074.26c-1 .38-2.053.105-2.561-.769l-.302-.652a.11.11 0 0 1 .037-.145z");
}

.felc_fb-i {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
}

.fgtpn31iv {
  fill: var(--svg-color--ffdd2c, #FFDD2C);
  d: path("M12.712 23.101c.15-.67.84-1.06 1.5-.85l.62.211a.05.05 0 0 0 .066-.05l-.03-.485c-.06-.67.41-1.266 1.09-1.276c.69-.01 1.18.526 1.18 1.25v.561a.05.05 0 0 0 .066.047l.55-.187c.64-.24 1.31.059 1.49.729c.17.65-.214 1.374-.884 1.494l-.457.1a.05.05 0 0 0-.03.079l.307.422c.44.52.34 1.32-.22 1.71s-1.296.193-1.67-.36l-.31-.413a.05.05 0 0 0-.081.003l-.242.375c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.526a.05.05 0 0 0-.032-.078l-.37-.066c-.67-.1-1.11-.75-.96-1.41");
}

.fjji9zbbw {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
  stop-opacity: 0;
}

.fktoll--q {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M15.92 18.774c.395.01 1.357-.063 2.05-.442");
}

.fni0kxmoh {
  d: path("M27 29.861v-1c0-5.2-3.61-9.365-8.46-10.515a.63.63 0 0 1-.48-.61v-3.105c0-1.15-.94-2.12-2.1-2.1c-1.12.02-2.02.93-2.02 2.06v3.145c0 .29-.2.55-.48.61C8.61 19.486 5 23.661 5 28.861v1z");
}

.fq6w-ob_b {
  cx: 11.223px;
  cy: 10.741px;
  r: 0.995px;
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.fzn5p4bte {
  stop-color: var(--svg-color--e7dedd, #E7DEDD);
}

.g-k0mcb6t {
  d: path("M18.946 10.356a.84.84 0 0 0-.232-.463l-.26.285l.118.228z");
}

.g22d_bc_z {
  stop-color: var(--svg-color--416b43, #416B43);
  stop-opacity: 0;
}

.g7ukm2_ss {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m17.348 24.72l.907 1.18");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gi1yleb5l {
  stop-color: var(--svg-color--aca4a1, #ACA4A1);
}

.gma_0ac5c {
  d: path("m19.934 5.116l-3.078 1.026a1.047 1.047 0 0 0 .47 2.03l3.06-.409z");
}

.gn67s1beu {
  stop-color: var(--svg-color--ffef65, #FFEF65);
}

.gn6w60u5d {
  cx: 11.223px;
  cy: 10.74px;
  r: 1.669px;
}

.gs-o-sbpb {
  d: path("M5.062 16.36c0-8.812 4.89-13.218 10.922-13.218s10.922 4.219 10.922 13.219v13.5H5.062z");
}

.gxsh2bbec {
  fill: var(--svg-color--9b9da0, #9B9DA0);
  d: path("M9.134 24.073c.879-.052 1.658.636 1.72 1.534l.009.116c.31.043.61.174.862.397l.107.113a.11.11 0 0 1 .01.15l-.42.583c-.665.762-1.75.833-2.66.27c-.064-.05-.086-.202-.024-.27l.69-.734q.136-.152.302-.26c-.906-.06-1.574-.75-1.735-1.634c-.013-.049.028-.207.15-.207z");
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.hbty0cbru {
  cx: 10.18px;
  cy: 21.506px;
  r: 0.762px;
}

.he14dbbbc {
  stop-color: var(--svg-color--f38330, #F38330);
}

.herc_pb_k {
  d: path("M18.151 9.582a.892.892 0 0 1 .86 1.127h-1.724a.896.896 0 0 1 .864-1.127");
}

.hf78f8bed {
  d: path("M9.984 15.783c0-4.854 2.694-7.28 6.016-7.28s6.016 2.323 6.016 7.28v7.435H9.984z");
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.hpzv-ab9a {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
  stop-opacity: 0;
}

.hr9jc16ta {
  stop-color: var(--svg-color--ffe24b, #FFE24B);
}

.i_w-uabpc {
  stop-color: var(--svg-color--efb59b, #EFB59B);
}

.i1hqu4kst {
  stop-color: var(--svg-color--ca992e, #CA992E);
}

.i20nf997e {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.412 8.394c.327-.29 1.041-.594 1.927-.452");
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

.ink9qmy7e {
  d: path("M8.528 22.689c-.076-.155-.018-.354.098-.419c.854-.403 2.333.553 3.222 1.634c.099.12.144.112.117-.035c-.248-1.376-.009-3.139.846-3.532c.126-.055.278.027.355.182l.753 1.632l.133.311c.111.292.303.839.336 1.134c.152 1.232-.46 2.09-1.43 2.538c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.948-.972-1.414z");
}

.isiq9yb3m {
  stop-color: var(--svg-color--c46399, #C46399);
}

.j9i7xp3bx {
  stop-color: var(--svg-color--cdc7c8, #CDC7C8);
}

.jdz_80b2w {
  d: path("M18.085 9.77c.064.085-.069.188-.22.301s-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.jffzfdc1k {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.97 13.87c-.507 0-.984-.12-1.385-.328c-.137-.07-.284.084-.198.209c.335.507.919.845 1.583.845c.665 0 1.248-.338 1.583-.845c.086-.13-.06-.279-.198-.21c-.4.21-.872.329-1.385.329Z");
}

.jih6tvbze {
  stop-color: var(--svg-color--3e5d50, #3E5D50);
}

.jm8e13_st {
  stop-color: var(--svg-color--e1d6d3, #E1D6D3);
}

.k_kfijbew {
  stop-color: var(--svg-color--ca992e, #CA992E);
  stop-opacity: 0;
}

.k1xxa4bqz {
  stop-color: var(--svg-color--af246b, #AF246B);
  stop-opacity: 0;
}

.k7u9-obow {
  stop-color: var(--svg-color--f3c1ab, #F3C1AB);
}

.kv9fthb_h {
  stop-color: var(--svg-color--dfc7b5, #DFC7B5);
}

.ky8zaobtn {
  d: path("M14.6 10.368c0-.288-.235-.48-.298-.538l-.289.278l.178.362z");
}

.l33l9dqgq {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
}

.l3byadclu {
  stop-color: var(--svg-color--eaa28f, #EAA28F);
}

.l556c4wxv {
  cx: 20.735px;
  cy: 10.741px;
  r: 0.995px;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l9b4opb5t {
  stop-color: var(--svg-color--338e58, #338E58);
  stop-opacity: 0;
}

.leqo8fosm {
  fill: var(--svg-color--dca238, #DCA238);
  d: path("M15.87 25.285a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.lw4wqxbbr {
  stop-color: var(--svg-color--ebb2a3, #EBB2A3);
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.m92tte26k {
  stop-color: var(--svg-color--e170ad, #E170AD);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.movji7bnz {
  r: 0.762px;
}

.mpfjlio6c {
  stop-color: var(--svg-color--619951, #619951);
}

.mt5e72-yt {
  stop-color: var(--svg-color--ffd4b8, #FFD4B8);
}

.mu5z5titl {
  stop-color: var(--svg-color--c6bebf, #C6BEBF);
}

.muovvys4e {
  stop-color: var(--svg-color--e2dfe3, #E2DFE3);
}

.n0n4e7bnh {
  stop-color: var(--svg-color--f3f0ef, #F3F0EF);
}

.n1imc2b4i {
  stop-color: var(--svg-color--4f8436, #4F8436);
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.nbz8snbyn {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
  stop-opacity: 0;
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.ndghkrcwe {
  stop-color: var(--svg-color--c3bbbb, #C3BBBB);
}

.nhvn8xbgd {
  stop-color: var(--svg-color--e19584, #E19584);
}

.nof2xyhhe {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
  stop-opacity: 0;
}

.o2lee7bjg {
  d: path("M10.813 8.689c0-.267.107-.587.322-.747l.16-.16c.269-.213.376-.533.376-.853v-.853c0-.267.16-.48.43-.534c.643-.16 1.984-.426 3.914-.426s3.272.266 3.916.426c.214.054.429.267.429.534v.853c0 .32.16.64.375.853c.502.352.471.545.43.96a46 46 0 0 0-.108 1.44h.018l-.266 3.958c-.16 1.77-1.551 3.003-3.21 3.003h-3.21c-1.712 0-3.05-1.234-3.21-3.003c-.14-1.816-.2-3.638-.366-5.451");
}

.o33h0jnse {
  d: path("m13.196 29.86l-2.547-3.837l5.25-3.475l5.828 2.91l-2.922 4.402z");
}

.o38c5rykb {
  stop-color: var(--svg-color--ffef65, #FFEF65);
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

.oi7qg9buh {
  d: path("M11.39 25.736c-.678-.6-1.716-.535-2.298.112l-.69.734c-.062.068-.04.22.024.27c.91.563 1.996.493 2.66-.27l.42-.583a.11.11 0 0 0-.009-.15z");
}

.onrup1btv {
  stop-color: var(--svg-color--eea990, #EEA990);
  stop-opacity: 0;
}

.p5ii0k_1a {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
  stop-opacity: 0;
}

.p5z8qs95p {
  d: path("M9.15 20.394a11.2 11.2 0 0 1 4.31-2.048c.28-.06.48-.32.48-.61v-3.145c0-1.13.9-2.04 2.02-2.06c1.16-.02 2.1.95 2.1 2.1v3.105c0 .29.2.54.48.61a11.3 11.3 0 0 1 4.325 2.063a8.44 8.44 0 0 1-6.852 3.503a8.44 8.44 0 0 1-6.864-3.518");
}

.pbh041bmy {
  stop-color: var(--svg-color--af3465, #AF3465);
  stop-opacity: 0;
}

.pcz4s2bal {
  stop-color: var(--svg-color--1b572f, #1B572F);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pr83zn9it {
  fill-rule: evenodd;
  d: path("M13.709 24.264a.913.913 0 0 1-.753-1.108a.91.91 0 0 1 1.178-.668l.617.21a.3.3 0 0 0 .396-.302l-.03-.484v-.007q-.019-.216.044-.404a.85.85 0 0 1 .8-.6c.532-.008.927.396.927 1v.561a.3.3 0 0 0 .396.284l.551-.187l.007-.003c.516-.193 1.023.047 1.16.56c.14.531-.183 1.092-.687 1.182l-.466.103a.3.3 0 0 0-.178.47l.312.43l.006.007a.92.92 0 0 1-.172 1.343c-.429.299-1.012.16-1.32-.295l-.316-.423a.3.3 0 0 0-.493.017l-.247.384l-.005.008a.91.91 0 0 1-1.294.33l-.001-.002a.92.92 0 0 1-.227-1.336l.005-.006l.362-.533a.3.3 0 0 0-.196-.464l-.369-.066z");
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.pzpwlzysi {
  stop-color: var(--svg-color--8bc659, #8BC659);
  stop-opacity: 0;
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qnto_7byk {
  cx: 9.168px;
  cy: 20.428px;
  r: 0.762px;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_s898b6a {
  stop-color: var(--svg-color--b81560, #B81560);
}

.r-opspb2k {
  stop-color: var(--svg-color--d68c83, #D68C83);
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.r3y-39nqq {
  stop-color: var(--svg-color--cbc7ca, #CBC7CA);
}

.rau9skumu {
  stop-color: var(--svg-color--de5390, #DE5390);
}

.rb6miyacc {
  stop-color: var(--svg-color--eea990, #EEA990);
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.rid712b8b {
  fill: var(--svg-color--000, #000);
  d: path("M14.295 10.473a.51.51 0 0 0-.51-.51a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.236");
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.rsfcoybzb {
  stop-color: var(--svg-color--64a25a, #64A25A);
}

.ruz641x6w {
  stop-color: var(--svg-color--d76316, #D76316);
  stop-opacity: 0;
}

.rv-oa3bkx {
  fill: var(--svg-color--3f6834, #3F6834);
  d: path("M21.819 23.337c.096.053.144.219.081.348l-.668 1.39c-.181.388-.526.926-.809 1.177c-.687.638-1.466.646-2.21.3a2.4 2.4 0 0 1-.481-.291a.97.97 0 0 1-.407.892c-.466.325-1.079.16-1.39-.3l-.258-.344a.042.042 0 0 0-.068.003l-.201.312a.965.965 0 0 1-1.374.35a.97.97 0 0 1-.241-1.415l.298-.438a.042.042 0 0 0-.027-.065l-.308-.055a.97.97 0 0 1-.799-1.173a.97.97 0 0 1 1.248-.708l.516.176a.042.042 0 0 0 .055-.042l-.025-.403c-.05-.558.514 1.048 1.08 1.04c.574-.009.81-1.664.81-1.062v.467c0 .028.028.049.055.04l.458-.157q.112-.042.223-.058l.036-.084l1.043.854c.063-.13.19-.198.295-.153c.711.328.494-.416.288.729c-.022.122.015.129.098.029c.74-.9 1.97-1.695 2.682-1.36");
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.s_ql7obry {
  stop-color: var(--svg-color--ffceba, #FFCEBA);
}

.sa_c7ns7l {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
}

.sbbw_6vcc {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
}

.shu058b7p {
  stop-color: var(--svg-color--d69993, #D69993);
  stop-opacity: 0;
}

.t_ye_u0tg {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M19.69 8.02h-.002l-.002-.002l-.004-.004l-.012-.01a2 2 0 0 0-.155-.107c-.1-.062-.24-.14-.42-.21a2.83 2.83 0 0 0-1.492-.159a.534.534 0 1 0 .166 1.055c.398-.063.717.01.934.096a1.5 1.5 0 0 1 .308.165a.534.534 0 0 0 .679-.823");
}

.t-y5i3b_t {
  stop-color: var(--svg-color--8ac463, #8AC463);
}

.t6_s8eb8a {
  cx: 13.515px;
  cy: 9.962px;
  rx: 0.389px;
  ry: 0.197px;
}

.teb498btn {
  d: path("M10.52 25.223c-.063-.898-.843-1.586-1.721-1.534l-.99.058c-.121 0-.162.158-.149.207c.176.967.961 1.703 2 1.633l.768-.097a.11.11 0 0 0 .102-.118z");
}

.tgwkdpbql {
  stop-color: var(--svg-color--bab5b4, #BAB5B4);
}

.tqblnl2vv {
  stop-color: var(--svg-color--e3dede, #E3DEDE);
  stop-opacity: 0;
}

.tqgh1edwg {
  stop-color: var(--svg-color--eaab97, #EAAB97);
}

.tv57cl-9q {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
}

.tw5q5pbyq {
  d: path("M15.993 25.154a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.ty1ewib_q {
  stop-color: var(--svg-color--e170ad, #E170AD);
  stop-opacity: 0;
}

.u-l7gqbnl {
  stop-color: var(--svg-color--eaa28f, #EAA28F);
  stop-opacity: 0;
}

.u3ly29i0x {
  stop-color: var(--svg-color--af246b, #AF246B);
}

.u4vifspin {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.098 20.955c.324 0 .758.376.758.859v.945");
}

.uaxm8f1hq {
  stop-color: var(--svg-color--338e58, #338E58);
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.ujdq-6enc {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
}

.ujizhjb0v {
  d: path("M23.457 22.689c.076-.155.018-.354-.098-.419c-.854-.403-2.334.553-3.222 1.634c-.099.12-.144.112-.117-.035c.247-1.376.009-3.139-.846-3.532c-.127-.055-.279.027-.355.182l-.754 1.632c-.044.107-.088.204-.132.311c-.111.292-.303.839-.336 1.134c-.152 1.232.46 2.09 1.43 2.538c.894.415 1.83.406 2.656-.36c.34-.303.754-.948.972-1.414z");
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.um-_idbbv {
  d: path("m20.799 26.23l-2.71-1.12l.67-1.62c.41-1 1.1-1.692 1.987-2.11c.466-.191.718.058.798.238c.3.82.081 2.137-.085 3.002z");
}

.uo7o7sb7z {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.434 22.502c.307.135.83.615.461 1.453");
}

.uq7zq9b9u {
  stop-color: var(--svg-color--c46399, #C46399);
  stop-opacity: 0;
}

.uqobvi_6e {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M15.97 13.87c-.507 0-.984-.12-1.385-.328c-.137-.07-.284.084-.198.209c.335.507.919.845 1.583.845c.665 0 1.248-.338 1.583-.845c.086-.13-.06-.279-.198-.21c-.4.21-.872.329-1.385.329");
}

.uy9-hlbji {
  stop-color: var(--svg-color--fff967, #FFF967);
  stop-opacity: 0;
}

.v9-8bpxan {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vt544m69k {
  stop-color: var(--svg-color--e19584, #E19584);
  stop-opacity: 0;
}

.vta0pui_z {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.085 9.77c.064.085-.069.188-.22.301s-.263.193-.327.108c-.063-.085.008-.246.159-.359c.15-.113.325-.135.388-.05");
}

.vzukf6b2o {
  d: path("m15.588 10.292l-.531 1.7a.538.538 0 0 0 .52.698h.786a.54.54 0 0 0 .521-.699l-.531-1.7c-.114-.376-.646-.376-.765 0");
}

.wa496n4py {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
  stop-opacity: 0;
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wh23x9bjk {
  stop-color: var(--svg-color--fff763, #FFF763);
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.wkalc4bst {
  stop-color: var(--svg-color--d35897, #D35897);
  stop-opacity: 0;
}

.wsyd1pyom {
  stop-color: var(--svg-color--fff763, #FFF763);
  stop-opacity: 0;
}

.wuj-im25o {
  fill: var(--svg-color--c55496, #C55496);
  d: path("M8.528 22.689c-.076-.155-.018-.354.098-.419c.854-.403 2.333.553 3.222 1.634c.099.12.144.112.117-.035c-.248-1.376-.009-3.139.846-3.532c.126-.055.278.027.355.182l.753 1.632l.133.311c.111.292.303.839.336 1.134c.152 1.232-.46 2.09-1.43 2.538c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.948-.972-1.414z");
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.x977d-55d {
  cx: 13.515px;
  cy: 9.962px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.389px;
  ry: 0.197px;
}

.xflvpmp1u {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
  stop-opacity: 0;
}

.xiwsuvb3u {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.358 9.31c.653 0 1.204.45 1.354 1.058a.274.274 0 0 1-.267.341h-2.23a.23.23 0 0 1-.228-.272c.126-.64.69-1.127 1.37-1.127");
}

.xo240subg {
  stop-color: var(--svg-color--d76316, #D76316);
}

.y32ab_wii {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
  stop-opacity: 0;
}

.y7_wd5mpc {
  stop-color: var(--svg-color--f3c1ab, #F3C1AB);
  stop-opacity: 0;
}

.y8qpet1tz {
  stop-color: var(--svg-color--34673c, #34673C);
}

.yf4d67bjr {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m15.695 10.618l-.82 1.7c-.102.349.142.698.488.698h.737c.346 0 .59-.354.488-.699l-.498-1.7c-.107-.376-.283-.376-.395 0");
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yhk8aqbmk {
  stop-color: var(--svg-color--e6dcda, #E6DCDA);
  stop-opacity: 0;
}

.yif-93b_l {
  cx: 20.735px;
  cy: 10.741px;
  r: 0.995px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.ylcb9tbto {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m15.588 10.455l-.531 1.7a.538.538 0 0 0 .52.698h.786a.54.54 0 0 0 .521-.699l-.531-1.7c-.114-.376-.646-.376-.765 0");
}

.yoe1cjj0j {
  fill: var(--svg-color--000, #000);
  d: path("M17.64 10.473c0-.284.227-.51.511-.51a.51.51 0 0 1 .454.746h-.904a.46.46 0 0 1-.061-.236");
}

.yvysc04cm {
  stop-color: var(--svg-color--f3ba97, #F3BA97);
  stop-opacity: 0;
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.z3hpt3mcq {
  stop-color: var(--svg-color--8bc659, #8BC659);
}

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.z5jverbbh {
  d: path("m11.186 26.23l2.71-1.12l-.67-1.62c-.41-1-1.1-1.692-1.988-2.11c-.465-.191-.717.058-.797.238c-.3.82-.081 2.137.085 3.002z");
}

.z87kcgb7t {
  stop-color: var(--svg-color--c23471, #C23471);
}

.z8y6fgvmn {
  stop-color: var(--svg-color--ffdabf, #FFDABF);
}

.zac6tac9t {
  d: path("M21.48 25.223c.063-.898.843-1.586 1.721-1.534l.99.058c.121 0 .162.158.149.207c-.176.967-.961 1.703-2 1.633l-.768-.097a.11.11 0 0 1-.102-.118z");
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zhj208b_d {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
}

.zl4k6m5yt {
  stop-color: var(--svg-color--f1eceb, #F1ECEB);
}

.zpmzd2b_c {
  stop-color: var(--svg-color--ffceba, #FFCEBA);
  stop-opacity: 0;
}

.zrnfx80km {
  fill: var(--svg-color--dc62a7, #DC62A7);
  d: path("M23.457 22.689c.076-.155.018-.354-.098-.419c-.854-.403-2.334.553-3.222 1.634c-.099.12-.144.112-.117-.035c.247-1.376.009-3.139-.846-3.532c-.127-.055-.279.027-.355.182l-.754 1.632c-.044.107-.088.204-.132.311c-.111.292-.303.839-.336 1.134c-.152 1.232.46 2.09 1.43 2.538c.894.415 1.83.406 2.656-.36c.34-.303.754-.948.972-1.414z");
}

.zv3wqwqhr {
  d: path("m15.588 10.455l-.531 1.7a.538.538 0 0 0 .52.698h.786a.54.54 0 0 0 .521-.699l-.531-1.7c-.114-.376-.646-.376-.765 0");
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

.zxvvm-hti {
  stop-color: var(--svg-color--d9cabf, #D9CABF);
}

</style>
