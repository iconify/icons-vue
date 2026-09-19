<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#im11RYb)"><path fill="url(#iwYCaFc)" class="o5a57gb_x"/><path fill="url(#icgmxOc)" class="o5a57gb_x"/><path fill="url(#iOofuRb)" class="o5a57gb_x"/></g><g filter="url(#iNYpTbV)"><path fill="url(#iXM8uDe)" class="l-mrnsw2p"/></g><g filter="url(#iip9Mie)"><path fill="url(#iNLS20a)" clip-rule="evenodd" class="pp_chx--o"/><path fill="url(#iQF4tsc)" clip-rule="evenodd" class="pp_chx--o"/><path fill="url(#ivJerhg)" clip-rule="evenodd" class="pp_chx--o"/><path fill="url(#iV1sALP)" clip-rule="evenodd" class="pp_chx--o"/><path fill="url(#iX3Eene)" clip-rule="evenodd" class="pp_chx--o"/><path fill="url(#iwDEqoh)" clip-rule="evenodd" class="pp_chx--o"/><path fill="url(#iKvbwYb)" clip-rule="evenodd" class="pp_chx--o"/><path fill="url(#igAjNle)" clip-rule="evenodd" class="pp_chx--o"/><path fill="url(#iOw2cCe)" clip-rule="evenodd" class="pp_chx--o"/><path fill="url(#iUVWqJc)" clip-rule="evenodd" class="pp_chx--o"/><path fill="url(#iLIVmDe)" clip-rule="evenodd" class="pp_chx--o"/></g><path fill="url(#i6ksEGc)" class="v3n252bdr"/><path fill="url(#imnSurd)" class="v3n252bdr"/><path fill="url(#idQNiwo)" class="v3n252bdr"/><path fill="url(#i5nbbUh)" class="v3n252bdr"/><g filter="url(#iyiwQ5d)"><path class="vlhzj-bky"/></g><g filter="url(#iUhpdWb)"><path class="rla7irgzy"/></g><g filter="url(#irm8EKb)"><path fill="url(#iL2yTXd)" class="cgwf57bmz"/><path fill="url(#iytoy1d)" class="cgwf57bmz"/><path fill="url(#iApi3uc)" class="cgwf57bmz"/></g><g filter="url(#iMhRmGc)"><path fill="url(#ictvJrb)" class="h1vv8wrrd"/><path fill="url(#i2VZDEM)" class="h1vv8wrrd"/><path fill="url(#iplte6b)" class="h1vv8wrrd"/></g><g filter="url(#ix6tJ0c)"><path fill="url(#iAhCOFd)" class="kk5nghg8x"/><path fill="url(#igQ8ZCb)" class="kk5nghg8x"/><path fill="url(#iagJSIc)" class="kk5nghg8x"/><path fill="url(#irkVAHd)" class="kk5nghg8x"/><path fill="url(#ielCYAd)" class="kk5nghg8x"/></g><path fill="url(#i2PI3xF)" class="a0fnokbdc"/><path fill="url(#iT3Quuy)" class="a0fnokbdc"/><g filter="url(#ig2Q7Mc)"><path class="jjrmf5_5v"/></g><g filter="url(#iR1L1gb)"><path fill="url(#ixwR2od)" class="ip2fbrb5p"/><path fill="url(#iqER5nq)" class="ip2fbrb5p"/></g><g filter="url(#i46Sdxb)"><path fill="url(#i9VKvCc)" class="a5a1u75xf"/><path fill="url(#i7FmYwd)" class="a5a1u75xf"/></g><circle fill="url(#iAqO34b)" class="b8csw2ryl"/><circle fill="url(#i5ycTZb)" class="b8csw2ryl"/><circle fill="url(#iAAvyQb)" transform="matrix(-1 0 0 1 22.919 20.465)" class="movji7bnz"/><circle fill="url(#iH86wby)" transform="matrix(-1 0 0 1 22.919 20.465)" class="movji7bnz"/><circle fill="url(#iQxtjGI)" class="ycdc5fyuc"/><circle fill="url(#izM6NXd)" transform="matrix(-1 0 0 1 21.97 21.524)" class="movji7bnz"/><circle fill="url(#iGbM8pb)" transform="matrix(-1 0 0 1 21.97 21.524)" class="movji7bnz"/><path fill="url(#ifs3aJb)" class="tvt8ccczx"/><g filter="url(#icxJCBe)"><path class="v904-8f9f"/><path fill="url(#ioHNtib)" class="nthvp6bhf"/><path fill="url(#iGviC4d)" class="nthvp6bhf"/><path fill="url(#i6aONjc)" class="nthvp6bhf"/><path fill="url(#i1SdOce)" class="nthvp6bhf"/><path fill="url(#iDNQMzi)" class="nthvp6bhf"/></g><path fill="url(#iqG6CPZ)" class="ga9gd76rf"/><g filter="url(#i5NEHbd)"><path class="plguddvmo"/><path fill="url(#iW6dcKq)" class="m65aglb3j"/><path fill="url(#i1I6Ivc)" class="m65aglb3j"/></g><g filter="url(#ir3Yxre)"><path class="x7zyp6nnz"/><path fill="url(#iVAHnDe)" class="gae5lxbxj"/><path fill="url(#iF4XRMe)" class="gae5lxbxj"/><path fill="url(#iAUaSKd)" class="gae5lxbxj"/><path fill="url(#iY57Xzd)" class="gae5lxbxj"/><path fill="url(#iiD64iq)" class="gae5lxbxj"/></g><g filter="url(#ibNAgdb)"><path fill="url(#itae1Md)" clip-rule="evenodd" class="xevmwcccx"/></g><g filter="url(#ia65ABb)"><path class="jr0kq7b_h"/></g><g filter="url(#i2hXNfe)"><path fill="url(#itOsIRb)" class="xm2ilgmxp"/><path fill="url(#iof0uQc)" class="xm2ilgmxp"/></g><g filter="url(#i1Om6pM)"><path stroke="url(#ioCfISc)" class="qx4s8jbjv"/></g><g filter="url(#iRbVxkI)"><path stroke="url(#i1Jjsyc)" class="ue4tj-40t"/></g><g filter="url(#iIOBXOb)"><path stroke="url(#ixwvrGc)" class="zzvuu8b-w"/></g><g filter="url(#is1lJmO)"><path stroke="url(#i6SbCqJ)" class="xgo5xrbyv"/></g><g filter="url(#ikhA00o)"><path fill="url(#iYpCnAb)" class="es9rdnb2g"/></g><g filter="url(#iHcLued)"><path fill="url(#iC6iWDx)" class="k9-y_ac5p"/><path fill="url(#iUh5lHe)" class="k9-y_ac5p"/></g><g filter="url(#iPXydZj)"><path class="k4o_95-jn"/><path fill="url(#imSLWeb)" class="e8gnj8b4j"/></g><g filter="url(#iKV3LWb)"><path class="sjzpc70ui"/><path fill="url(#iz6VMey)" class="h71xt0usx"/></g><g filter="url(#iFvWVyD)"><path fill="url(#iQzbOGr)" class="b38d6lbic"/><path fill="url(#ihxOpDz)" class="b38d6lbic"/><path fill="url(#iSDRgQd)" class="b38d6lbic"/><path fill="url(#iIoTlDb)" class="b38d6lbic"/><path fill="url(#iRK3eLd)" class="b38d6lbic"/><path fill="url(#in0KWqc)" class="b38d6lbic"/><path fill="url(#iDsDFDe)" class="b38d6lbic"/></g><path fill="url(#ij3mfie)" class="b38d6lbic"/><path fill="url(#i6ROELk)" class="b38d6lbic"/><g filter="url(#i9SpZHz)"><path class="nq8ap6btb"/></g><g filter="url(#iuDzmub)"><path class="e3pms-bdy"/><path fill="url(#izyDZxe)" class="ezs6x-jxc"/><path fill="url(#iALt8Ab)" class="ezs6x-jxc"/><path fill="url(#iFZYkRc)" class="ezs6x-jxc"/><path fill="url(#irgGfme)" class="ezs6x-jxc"/></g><g filter="url(#izaHxze)"><path fill="url(#ipOppDy)" class="o8rnhccaw"/></g><g filter="url(#iGkZZtd)"><path stroke="url(#iNfBGck)" class="lrfw_3buu"/></g><path class="uwzhnobuw"/><g filter="url(#ikM5Bib)"><path class="hcqoaqlig"/></g><g filter="url(#iWVDv9b)"><path class="sfz55pe2y"/></g><g filter="url(#irVpwKe)"><path class="wjaz7obfy"/></g><g filter="url(#i2Ld1jd)"><path clip-rule="evenodd" class="q9uatzb-b"/></g><path class="vgt2qnb2u"/><path fill="url(#iG5spOc)" class="m08rdxbim"/><path class="z6_95pbhj"/><g filter="url(#ixA9l3c)"><path class="ryatr-kxe"/><path fill="url(#i9lOJsc)" class="oujulfp4v"/></g><g filter="url(#iQSM7Tc)"><path fill="url(#iBs0eNe)" class="kfxms3gui"/></g><path class="gic5jpboz"/><path fill="url(#iJZVQbe)" class="ny041mpzr"/><path class="kor6y-bvl"/><g filter="url(#i8Al3Zb)"><path fill="url(#iD2iKYd)" class="myo455mpg"/></g><g filter="url(#iZ0W8Fb)"><ellipse transform="rotate(-27.914 13.54 9.835)" class="w5vkn-xtc"/><ellipse fill="url(#iu6rjgb)" transform="rotate(-27.914 13.54 9.835)" class="l5x2v-b4z"/></g><g filter="url(#iXa4LNc)"><path class="kdxbzbgjp"/></g><g filter="url(#i2mWd3z)"><path class="w13qlvl6z"/></g><g filter="url(#ijJ6YJb)"><path class="mw8ur5bua"/><path fill="url(#iXcfBle)" class="hosbwkb7o"/></g><g filter="url(#iqVzlOY)"><path class="yisy14b-j"/><path fill="url(#ivR99Ie)" class="vba3cacoe"/><path fill="url(#ik3Mqbb)" class="vba3cacoe"/></g><g filter="url(#il5p0Bc)"><path stroke="url(#iYUSOKb)" class="hge7y2igm"/></g><g filter="url(#ir9wVGb)"><path class="cc9ylm0_i"/></g><g filter="url(#iSBZULc)"><path fill="url(#iFmEHve)" clip-rule="evenodd" class="nljy2k17i"/><path fill="url(#i9smCsV)" clip-rule="evenodd" class="nljy2k17i"/></g><defs><radialGradient id="icgmxOc" cx="0" cy="0" r="1" gradientTransform="rotate(-126.573 19.847 7.048)scale(14.4752 12.6607)" gradientUnits="userSpaceOnUse"><stop offset=".27" class="sa_c7ns7l"/><stop offset="1" class="xflvpmp1u"/></radialGradient><radialGradient id="iOofuRb" cx="0" cy="0" r="1" gradientTransform="matrix(6.9375 -5.375 4.67303 6.03148 5.7 25.688)" gradientUnits="userSpaceOnUse"><stop class="zhj208b_d"/><stop offset="1" class="y32ab_wii"/></radialGradient><radialGradient id="iQF4tsc" cx="0" cy="0" r="1" gradientTransform="matrix(-.6034 4.55907 -5.6952 -.75377 15.69 13.029)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="xdn388byj"/><stop offset="1" class="qwp4ni-tf"/></radialGradient><radialGradient id="ivJerhg" cx="0" cy="0" r="1" gradientTransform="matrix(-2.88301 1.94432 -2.5547 -3.78806 12.875 13.297)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="bl7uysvvb"/><stop offset="1" class="r_v2kebuk"/></radialGradient><radialGradient id="iV1sALP" cx="0" cy="0" r="1" gradientTransform="rotate(127.405 2.918 8.13)scale(2.15225 1.65263)" gradientUnits="userSpaceOnUse"><stop offset=".334" class="l0xg-rbdf"/><stop offset="1" class="chj8m5e2t"/></radialGradient><radialGradient id="iX3Eene" cx="0" cy="0" r="1" gradientTransform="rotate(121.43 3.355 7.614)scale(2.47506 1.74346)" gradientUnits="userSpaceOnUse"><stop offset=".321" class="kbl3igr5c"/><stop offset="1" class="glo437b-m"/></radialGradient><radialGradient id="iwDEqoh" cx="0" cy="0" r="1" gradientTransform="matrix(1.37443 2.61477 -3.62969 1.90792 12.473 2.47)" gradientUnits="userSpaceOnUse"><stop class="paonnib9g"/><stop offset="1" class="g0r7omboq"/></radialGradient><radialGradient id="iKvbwYb" cx="0" cy="0" r="1" gradientTransform="rotate(134.998 9.97 6.794)scale(2.03849 2.84876)" gradientUnits="userSpaceOnUse"><stop class="hx66smwtj"/><stop offset="1" class="c9_6uxbfa"/></radialGradient><radialGradient id="igAjNle" cx="0" cy="0" r="1" gradientTransform="matrix(-1.84366 .53637 -1.11855 -3.8448 23.502 9.677)" gradientUnits="userSpaceOnUse"><stop class="cj4rfmfkx"/><stop offset="1" class="silozpblh"/></radialGradient><radialGradient id="iOw2cCe" cx="0" cy="0" r="1" gradientTransform="rotate(165.963 10.643 7.958)scale(2.90248 3.69733)" gradientUnits="userSpaceOnUse"><stop class="mxnnm4bur"/><stop offset="1" class="jk5udqbyz"/></radialGradient><radialGradient id="iUVWqJc" cx="0" cy="0" r="1" gradientTransform="rotate(-108.843 12.953 -3.792)scale(2.80034 2.21491)" gradientUnits="userSpaceOnUse"><stop class="hkormb2xp"/><stop offset="1" class="e-twaac7b"/></radialGradient><radialGradient id="iLIVmDe" cx="0" cy="0" r="1" gradientTransform="matrix(1.50392 .15775 -.2556 2.43678 9.85 9.64)" gradientUnits="userSpaceOnUse"><stop class="lgjudcrkd"/><stop offset="1" class="tr7czpf3k"/></radialGradient><radialGradient id="i6ksEGc" cx="0" cy="0" r="1" gradientTransform="rotate(155.653 10.146 15.761)scale(12.2796 19.1721)" gradientUnits="userSpaceOnUse"><stop offset=".111" class="vc--wpv5i"/><stop offset="1" class="iaefxbcet"/></radialGradient><radialGradient id="idQNiwo" cx="0" cy="0" r="1" gradientTransform="matrix(-2.09375 1.15624 -3.57275 -6.46962 12.762 28.063)" gradientUnits="userSpaceOnUse"><stop offset=".045" class="v9-8bpxan"/><stop offset="1" class="p5ii0k_1a"/></radialGradient><radialGradient id="i5nbbUh" cx="0" cy="0" r="1" gradientTransform="matrix(-3.625 0 0 -3.8125 9.856 24.219)" gradientUnits="userSpaceOnUse"><stop offset=".302" class="tv57cl-9q"/><stop offset="1" class="nof2xyhhe"/></radialGradient><radialGradient id="iytoy1d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26562 -1.93554 2.61071 -1.7071 23.356 25.857)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="iApi3uc" cx="0" cy="0" r="1" gradientTransform="rotate(155.556 9.632 14.657)scale(1.32158 .2597)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="i2VZDEM" cx="0" cy="0" r="1" gradientTransform="matrix(.42186 -1.97502 3.24628 .6934 21.762 27.36)" gradientUnits="userSpaceOnUse"><stop offset=".705" class="l9b4opb5t"/><stop offset=".989" class="uaxm8f1hq"/></radialGradient><radialGradient id="iplte6b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1139 -.45312 .07627 -.1875 23.728 26.922)" gradientUnits="userSpaceOnUse"><stop offset=".162" class="z3hpt3mcq"/><stop offset="1" class="pzpwlzysi"/></radialGradient><radialGradient id="iAhCOFd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.95206 -2.46677 3.46444 -9.76378 21.531 21.64)" gradientUnits="userSpaceOnUse"><stop class="mt5e72-yt"/><stop offset="1" class="i_w-uabpc"/></radialGradient><radialGradient id="igQ8ZCb" cx="0" cy="0" r="1" gradientTransform="matrix(.0287 2.22817 -1.66026 .02139 16.729 16.688)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="gpoq-dbst"/><stop offset="1" class="c06i-_swg"/></radialGradient><radialGradient id="iagJSIc" cx="0" cy="0" r="1" gradientTransform="rotate(162.431 6.768 9.23)scale(3.67056 1.55988)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="nhvn8xbgd"/><stop offset="1" class="vt544m69k"/></radialGradient><radialGradient id="irkVAHd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.07223 -.6455 .5202 -.8641 22.585 20.863)" gradientUnits="userSpaceOnUse"><stop class="cyqt__gil"/><stop offset="1" class="yvysc04cm"/></radialGradient><radialGradient id="ielCYAd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.96875 -.73075 0 14.117 16.706)" gradientUnits="userSpaceOnUse"><stop class="rb6miyacc"/><stop offset="1" class="onrup1btv"/></radialGradient><radialGradient id="i2PI3xF" cx="0" cy="0" r="1" gradientTransform="rotate(30.491 -40.838 35.913)scale(7.14423 9.27511)" gradientUnits="userSpaceOnUse"><stop offset=".06" class="a805jtb_d"/><stop offset=".81" class="mpfjlio6c"/></radialGradient><radialGradient id="iqER5nq" cx="0" cy="0" r="1" gradientTransform="rotate(-56.82 28.223 4.939)scale(2.3126 3.1193)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="l9b4opb5t"/><stop offset=".919" class="uaxm8f1hq"/></radialGradient><radialGradient id="i7FmYwd" cx="0" cy="0" r="1" gradientTransform="matrix(-.42043 -1.9751 3.23141 -.68786 10.244 27.359)" gradientUnits="userSpaceOnUse"><stop offset=".609" class="o9qsnlb6c"/><stop offset=".948" class="pcz4s2bal"/></radialGradient><radialGradient id="iAqO34b" cx="0" cy="0" r="1" gradientTransform="rotate(141.833 1.306 11.828)scale(1.27689)" gradientUnits="userSpaceOnUse"><stop class="b4of-6bao"/><stop offset="1" class="r3y-39nqq"/></radialGradient><radialGradient id="i5ycTZb" cx="0" cy="0" r="1" gradientTransform="rotate(90 -5.455 14.623)scale(1.25098)" gradientUnits="userSpaceOnUse"><stop offset=".55" class="d5fabsakk"/><stop offset="1" class="ndghkrcwe"/></radialGradient><radialGradient id="iAAvyQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.17188 .58594 -.45305 .9061 .052 .516)" gradientUnits="userSpaceOnUse"><stop class="n0n4e7bnh"/><stop offset="1" class="jm8e13_st"/></radialGradient><radialGradient id="iH86wby" cx="0" cy="0" r="1" gradientTransform="matrix(.66407 -1.01563 1.1175 .73068 .52 1.063)" gradientUnits="userSpaceOnUse"><stop offset=".587" class="yhk8aqbmk"/><stop offset="1" class="zxvvm-hti"/></radialGradient><radialGradient id="iQxtjGI" cx="0" cy="0" r="1" gradientTransform="rotate(139.138 1.34 12.683)scale(1.3016)" gradientUnits="userSpaceOnUse"><stop class="eatp636hk"/><stop offset="1" class="tgwkdpbql"/></radialGradient><radialGradient id="izM6NXd" cx="0" cy="0" r="1" gradientTransform="matrix(1 1.07031 -1.1661 1.0895 .298 .379)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="zl4k6m5yt"/><stop offset="1" class="j9i7xp3bx"/></radialGradient><radialGradient id="iGbM8pb" cx="0" cy="0" r="1" gradientTransform="matrix(1.07812 -.64844 .589 .9793 .391 .926)" gradientUnits="userSpaceOnUse"><stop offset=".29" class="tqblnl2vv"/><stop offset=".964" class="kv9fthb_h"/></radialGradient><radialGradient id="ifs3aJb" cx="0" cy="0" r="1" gradientTransform="rotate(69.815 -10.405 19.393)scale(2.04763 .82994)" gradientUnits="userSpaceOnUse"><stop class="z87kcgb7t"/><stop offset=".853" class="r_s898b6a"/></radialGradient><radialGradient id="ioHNtib" cx="0" cy="0" r="1" gradientTransform="rotate(67.353 -9.33 20.249)scale(4.0633 .80773)" gradientUnits="userSpaceOnUse"><stop class="i7kjncbis"/><stop offset="1" class="wkalc4bst"/></radialGradient><radialGradient id="iGviC4d" cx="0" cy="0" r="1" gradientTransform="matrix(1.97895 1.21874 -.15017 .24384 9.481 23.062)" gradientUnits="userSpaceOnUse"><stop class="ddg3g7pcd"/><stop offset="1" class="ejr-khbri"/></radialGradient><radialGradient id="i6aONjc" cx="0" cy="0" r="1" gradientTransform="rotate(-118.794 14.19 9.25)scale(2.33566 5.83179)" gradientUnits="userSpaceOnUse"><stop offset=".268" class="isiq9yb3m"/><stop offset="1" class="uq7zq9b9u"/></radialGradient><radialGradient id="i1SdOce" cx="0" cy="0" r="1" gradientTransform="matrix(-1.12499 1.3125 -.4864 -.4169 14.278 24.86)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="ehlybtbyr"/><stop offset="1" class="pbh041bmy"/></radialGradient><radialGradient id="iDNQMzi" cx="0" cy="0" r="1" gradientTransform="matrix(-1.64063 -.62499 .30595 -.80313 14.31 24.641)" gradientUnits="userSpaceOnUse"><stop class="u3ly29i0x"/><stop offset="1" class="k1xxa4bqz"/></radialGradient><radialGradient id="iqG6CPZ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03126 2.5625 -1.3029 -.52434 21.528 21.859)" gradientUnits="userSpaceOnUse"><stop class="rau9skumu"/><stop offset="1" class="obmju7b-z"/></radialGradient><radialGradient id="iW6dcKq" cx="0" cy="0" r="1" gradientTransform="matrix(-.67188 .51562 -.16532 -.21542 23.294 22.765)" gradientUnits="userSpaceOnUse"><stop class="m92tte26k"/><stop offset="1" class="ty1ewib_q"/></radialGradient><radialGradient id="i1I6Ivc" cx="0" cy="0" r="1" gradientTransform="matrix(.58243 3.00041 -1.02662 .19928 19.588 20.78)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="l33l9dqgq"/><stop offset="1" class="fjji9zbbw"/></radialGradient><radialGradient id="iVAHnDe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.03124 2.3125 -1.56386 -.69739 16.794 21.344)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="iF4XRMe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.96008 .75001 -.74136 -1.93748 19.285 23.032)" gradientUnits="userSpaceOnUse"><stop class="wh23x9bjk"/><stop offset="1" class="wsyd1pyom"/></radialGradient><radialGradient id="itae1Md" cx="0" cy="0" r="1" gradientTransform="rotate(111.14 1.288 16.662)scale(6.15203 6.32964)" gradientUnits="userSpaceOnUse"><stop class="hr9jc16ta"/><stop offset="1" class="f_r_72dts"/></radialGradient><radialGradient id="itOsIRb" cx="0" cy="0" r="1" gradientTransform="matrix(-.8047 .60938 -.52546 -.69388 16.386 23.906)" gradientUnits="userSpaceOnUse"><stop class="ifzr0vvcb"/><stop offset=".808" class="he14dbbbc"/></radialGradient><radialGradient id="iof0uQc" cx="0" cy="0" r="1" gradientTransform="matrix(.17187 -1.1 1.36133 .2127 15.731 25.293)" gradientUnits="userSpaceOnUse"><stop offset=".039" class="xo240subg"/><stop offset="1" class="ruz641x6w"/></radialGradient><radialGradient id="iC6iWDx" cx="0" cy="0" r="1" gradientTransform="rotate(-48.104 23.138 -17.215)scale(2.73591 3.34042)" gradientUnits="userSpaceOnUse"><stop offset=".444" class="w--6bgeqj"/><stop offset=".944" class="sheftacio"/></radialGradient><radialGradient id="iUh5lHe" cx="0" cy="0" r="1" gradientTransform="matrix(1.31576 .7375 -.2085 .37199 21.063 8.847)" gradientUnits="userSpaceOnUse"><stop class="ynae43ovp"/><stop offset="1" class="v-9tn59hb"/></radialGradient><radialGradient id="imSLWeb" cx="0" cy="0" r="1" gradientTransform="matrix(1.50989 -.11231 .0878 1.18032 20.384 10.64)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="k2oqpgb0o"/><stop offset="1" class="dkw8bsvxv"/></radialGradient><radialGradient id="iz6VMey" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20681 0 0 -.95203 11.391 10.528)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="b55qklbsj"/><stop offset="1" class="uaoaczbhz"/></radialGradient><radialGradient id="iQzbOGr" cx="0" cy="0" r="1" gradientTransform="matrix(-6.50357 2.99901 -4.01413 -8.70492 18.852 9.99)" gradientUnits="userSpaceOnUse"><stop class="v5rheyc4i"/><stop offset="1" class="wum9l96_j"/></radialGradient><radialGradient id="ihxOpDz" cx="0" cy="0" r="1" gradientTransform="matrix(-3.46116 .45112 -.49796 -3.82051 19.244 11.353)" gradientUnits="userSpaceOnUse"><stop class="z-rzt8b_f"/><stop offset="1" class="tk20gvbnd"/></radialGradient><radialGradient id="iSDRgQd" cx="0" cy="0" r="1" gradientTransform="matrix(1.30737 -3.78806 4.80634 1.6588 13.613 17.32)" gradientUnits="userSpaceOnUse"><stop class="fvm07vbkd"/><stop offset="1" class="n1w64orcn"/></radialGradient><radialGradient id="iIoTlDb" cx="0" cy="0" r="1" gradientTransform="scale(7.78405 6.72467)rotate(90 .3 1.754)" gradientUnits="userSpaceOnUse"><stop offset=".567" class="fwm5mebpo"/><stop offset="1" class="q1wk2zbta"/></radialGradient><radialGradient id="iRK3eLd" cx="0" cy="0" r="1" gradientTransform="rotate(168.897 8.332 6.726)scale(7.03738 12.1162)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="brg8dbpny"/><stop offset="1" class="d_t8kfbgb"/></radialGradient><radialGradient id="in0KWqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.15077 1.41231 0 18.294 9.572)" gradientUnits="userSpaceOnUse"><stop class="e2earo80w"/><stop offset="1" class="xl9xm7bnj"/></radialGradient><radialGradient id="iDsDFDe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.31251 1.50423 0 13.916 9.343)" gradientUnits="userSpaceOnUse"><stop class="suybu51ug"/><stop offset="1" class="intda8ekf"/></radialGradient><radialGradient id="ij3mfie" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28528 0 0 -6.44557 21.088 11.06)" gradientUnits="userSpaceOnUse"><stop class="sqxrh1b6n"/><stop offset="1" class="eodwsybla"/></radialGradient><radialGradient id="i6ROELk" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 4 -6.96848 2.28654 13.808 3.992)" gradientUnits="userSpaceOnUse"><stop class="f_q-3cc4h"/><stop offset="1" class="s44y8_wdc"/></radialGradient><radialGradient id="izyDZxe" cx="0" cy="0" r="1" gradientTransform="matrix(-.45554 -2.04401 .62995 -.1404 16.778 11.786)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="xbgj88f0b"/><stop offset="1" class="y_9l2i5ww"/></radialGradient><radialGradient id="irgGfme" cx="0" cy="0" r="1" gradientTransform="matrix(-.7794 0 0 -.2179 16.537 11.997)" gradientUnits="userSpaceOnUse"><stop class="qpkqxibzk"/><stop offset="1" class="nwt8glb0m"/></radialGradient><radialGradient id="iG5spOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.29049 0 18.174 9.931)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="i9lOJsc" cx="0" cy="0" r="1" gradientTransform="matrix(-.23192 -.29886 .41145 -.3193 17.946 10.015)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iJZVQbe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 13.81 9.931)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iu6rjgb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.758 -1.582)scale(.49412 .59395)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iXcfBle" cx="0" cy="0" r="1" gradientTransform="matrix(1.26205 -2.75541 1.4096 .64564 10.334 7.81)" gradientUnits="userSpaceOnUse"><stop class="cuv4n92_b"/><stop offset="1" class="mq6wd3bba"/></radialGradient><radialGradient id="ivR99Ie" cx="0" cy="0" r="1" gradientTransform="rotate(115.684 8.133 6.93)scale(4.8729 7.96691)" gradientUnits="userSpaceOnUse"><stop offset=".639" class="ssbc2ccsr"/><stop offset="1" class="ou3onybvn"/></radialGradient><radialGradient id="ik3Mqbb" cx="0" cy="0" r="1" gradientTransform="matrix(-.21034 1.3672 -2.94144 -.45253 16.203 2.972)" gradientUnits="userSpaceOnUse"><stop class="g5d3hjacf"/><stop offset="1" class="j2p90_-bc"/></radialGradient><radialGradient id="i9smCsV" cx="0" cy="0" r="1" gradientTransform="rotate(118.072 9.65 8.616)scale(.92969 16.1409)" gradientUnits="userSpaceOnUse"><stop offset=".107" class="al0tyek2y"/><stop offset="1" class="nbz8snbyn"/></radialGradient><filter id="im11RYb" width="21.944" height="26.818" x="4.962" y="3.281" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.952941 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3422"/></filter><filter id="iNYpTbV" width="12.631" height="14.916" x="9.484" y="8.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.811765 0 0 0 0 0.807843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3422"/><feGaussianBlur result="effect2_foregroundBlur_4002_3422" stdDeviation=".05"/></filter><filter id="iip9Mie" width="15.268" height="15.768" x="8.483" y="1.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.121569 0 0 0 0 0.0705882 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3422"/></filter><filter id="iyiwQ5d" width="5.874" height="5.537" x="6.993" y="23.209" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3422" stdDeviation=".5"/></filter><filter id="iUhpdWb" width="4.979" height="4.054" x="18.51" y="24.812" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3422" stdDeviation=".5"/></filter><filter id="irm8EKb" width="2.973" height="2.006" x="21.47" y="23.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3422"/></filter><filter id="iMhRmGc" width="3.281" height="2" x="20.468" y="25.361" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3422"/></filter><filter id="ix6tJ0c" width="13.965" height="11.381" x="9.149" y="12.67" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.623529 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3422"/></filter><filter id="ig2Q7Mc" width="10.996" height="6.432" x="11.932" y="22.036" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3422" stdDeviation=".5"/></filter><filter id="iR1L1gb" width="2.973" height="2.006" x="7.658" y="23.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3422"/></filter><filter id="i46Sdxb" width="3.266" height="2" x="8.366" y="25.361" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.576471 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3422"/></filter><filter id="icxJCBe" width="6.218" height="6.789" x="8.343" y="20.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.639216 0 0 0 0 0.227451 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3422"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".3"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.141176 0 0 0 0 0.427451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3422" result="effect2_innerShadow_4002_3422"/></filter><filter id="i5NEHbd" width="6.218" height="6.639" x="17.574" y="20.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.694118 0 0 0 0 0.239216 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3422"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.815686 0 0 0 0 0.301961 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_3422" result="effect2_innerShadow_4002_3422"/></filter><filter id="ir3Yxre" width="6.702" height="6.417" x="12.683" y="20.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.619608 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3422"/></filter><filter id="ibNAgdb" width="6.703" height="6.517" x="12.633" y="20.74" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3422" stdDeviation=".15"/></filter><filter id="ia65ABb" width="3.2" height="3.2" x="14.271" y="22.725" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3422" stdDeviation=".25"/></filter><filter id="i2hXNfe" width="2.35" height="2.35" x="14.893" y="23.093" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.92549 0 0 0 0 0.521569 0 0 0 0 0.0823529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3422"/></filter><filter id="i1Om6pM" width="1.458" height="2.505" x="15.848" y="20.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3422" stdDeviation=".125"/></filter><filter id="iRbVxkI" width="1.723" height="1.924" x="16.94" y="24.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3422" stdDeviation=".125"/></filter><filter id="iIOBXOb" width="1.368" height="2.217" x="18.104" y="22.207" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3422" stdDeviation=".125"/></filter><filter id="is1lJmO" width="3.55" height="1.942" x="15.171" y="17.722" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3422" stdDeviation=".25"/></filter><filter id="ikhA00o" width="3.368" height="3.218" x="9.698" y="8.919" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.894118 0 0 0 0 0.682353 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3422"/></filter><filter id="iHcLued" width="3.218" height="3.468" x="19.211" y="8.669" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.572549 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3422"/></filter><filter id="iPXydZj" width="3.148" height="3.148" x="19.246" y="8.954" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3422" stdDeviation=".25"/></filter><filter id="iKV3LWb" width="2.948" height="2.948" x="9.852" y="9.054" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3422" stdDeviation=".2"/></filter><filter id="iFvWVyD" width="10.191" height="11.277" x="10.897" y="5.621" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.807843 0 0 0 0 0.592157 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3422"/></filter><filter id="i9SpZHz" width="2.877" height="3.682" x="14.392" y="9.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3422" stdDeviation=".25"/></filter><filter id="iuDzmub" width="2.377" height="3.182" x="14.804" y="9.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3422" stdDeviation=".125"/></filter><filter id="izaHxze" width="2.377" height="3.182" x="14.804" y="9.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3422" stdDeviation=".125"/></filter><filter id="iGkZZtd" width="3.702" height="1.526" x="14.141" y="12.876" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3422" stdDeviation=".05"/></filter><filter id="ikM5Bib" width="3.001" height="1.286" x="16.934" y="9.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.0666667 0 0 0 0 0.117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3422"/></filter><filter id="iWVDv9b" width="3.001" height="1.286" x="12.049" y="9.123" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0862745 0 0 0 0 0.054902 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3422"/></filter><filter id="irVpwKe" width="2.453" height="1.091" x="12.184" y="7.699" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3422"/></filter><filter id="i2Ld1jd" width="2.453" height="1.091" x="17.602" y="7.699" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0235294 0 0 0 0 0.0313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3422"/></filter><filter id="ixA9l3c" width=".787" height=".696" x="17.44" y="9.491" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3422" stdDeviation=".05"/></filter><filter id="iQSM7Tc" width=".891" height=".913" x="18.28" y="9.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3422" stdDeviation=".1"/></filter><filter id="i8Al3Zb" width=".986" height="1.04" x="13.837" y="9.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3422" stdDeviation=".1"/></filter><filter id="iZ0W8Fb" width=".913" height=".704" x="13.083" y="9.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3422" stdDeviation=".05"/></filter><filter id="iXa4LNc" width="2.261" height=".978" x="17.632" y="7.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3422" stdDeviation=".1"/></filter><filter id="i2mWd3z" width="2.261" height=".978" x="12.18" y="7.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3422" stdDeviation=".1"/></filter><filter id="ijJ6YJb" width="4.212" height="4.513" x="9.738" y="3.686" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.352941 0 0 0 0 0.341176 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3422"/><feGaussianBlur result="effect2_foregroundBlur_4002_3422" stdDeviation=".15"/></filter><filter id="iqVzlOY" width="8.767" height="5.782" x="12.822" y="2.451" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".2"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.345098 0 0 0 0 0.329412 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3422"/><feGaussianBlur result="effect2_foregroundBlur_4002_3422" stdDeviation=".125"/></filter><filter id="il5p0Bc" width="1.145" height="2.31" x="12.801" y="3.685" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3422" stdDeviation=".1"/></filter><filter id="ir9wVGb" width="6.427" height="3.372" x="15.411" y="4.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_3422" stdDeviation=".375"/></filter><filter id="iSBZULc" width="15.448" height="4.54" x="8.283" y="2.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.35"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.694118 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_3422"/></filter><linearGradient id="iwYCaFc" x1="26.906" x2="11.7" y1="11.563" y2="21.563" gradientUnits="userSpaceOnUse"><stop class="fzn5p4bte"/><stop offset="1" class="mu5z5titl"/></linearGradient><linearGradient id="iXM8uDe" x1="20.7" x2="10.387" y1="17.469" y2="17.469" gradientUnits="userSpaceOnUse"><stop class="ct82q_bbh"/><stop offset="1" class="gi1yleb5l"/></linearGradient><linearGradient id="iNLS20a" x1="20.686" x2="13.881" y1="3.576" y2="16.18" gradientUnits="userSpaceOnUse"><stop class="hjtn79bml"/><stop offset="1" class="a4-v90a8k"/></linearGradient><linearGradient id="imnSurd" x1="14.887" x2="14.887" y1="30.938" y2="29.657" gradientUnits="userSpaceOnUse"><stop class="ujdq-6enc"/><stop offset="1" class="hpzv-ab9a"/></linearGradient><linearGradient id="iL2yTXd" x1="23.649" x2="21.867" y1="25.86" y2="24.449" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="ictvJrb" x1="22.95" x2="21.169" y1="27.444" y2="25.75" gradientUnits="userSpaceOnUse"><stop class="t-y5i3b_t"/><stop offset="1" class="rsfcoybzb"/></linearGradient><linearGradient id="iT3Quuy" x1="12.653" x2="13.255" y1="29.328" y2="28.984" gradientUnits="userSpaceOnUse"><stop class="jih6tvbze"/><stop offset="1" class="g22d_bc_z"/></linearGradient><linearGradient id="ixwR2od" x1="7.856" x2="9.361" y1="24.343" y2="26.163" gradientUnits="userSpaceOnUse"><stop class="n1imc2b4i"/><stop offset="1" class="dz0-61bre"/></linearGradient><linearGradient id="i9VKvCc" x1="9.062" x2="10.843" y1="27.443" y2="25.758" gradientUnits="userSpaceOnUse"><stop class="cnrgi8b1a"/><stop offset="1" class="y8qpet1tz"/></linearGradient><linearGradient id="iAUaSKd" x1="14.919" x2="16.7" y1="27.207" y2="22.938" gradientUnits="userSpaceOnUse"><stop class="i1hqu4kst"/><stop offset="1" class="k_kfijbew"/></linearGradient><linearGradient id="iY57Xzd" x1="13.356" x2="16.981" y1="22.969" y2="23.657" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="iiD64iq" x1="17.231" x2="16.325" y1="26.969" y2="25.219" gradientUnits="userSpaceOnUse"><stop offset=".039" class="felc_fb-i"/><stop offset="1" class="wa496n4py"/></linearGradient><linearGradient id="ioCfISc" x1="16.477" x2="16.477" y1="20.891" y2="22.898" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="i1Jjsyc" x1="17.286" x2="18.153" y1="24.945" y2="26.148" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset="0" class="gn67s1beu"/><stop offset=".739" class="gn67s1beu"/><stop offset="1" class="o38c5rykb"/></linearGradient><linearGradient id="ixwvrGc" x1="18.728" x2="18.728" y1="22.477" y2="24.094" gradientUnits="userSpaceOnUse"><stop class="uy9-hlbji"/><stop offset=".214" class="e-0jmrbwd"/><stop offset=".739" class="e-0jmrbwd"/><stop offset="1" class="uy9-hlbji"/></linearGradient><linearGradient id="i6SbCqJ" x1="16.132" x2="20.117" y1="19.089" y2="17.917" gradientUnits="userSpaceOnUse"><stop class="s_ql7obry"/><stop offset="1" class="zpmzd2b_c"/></linearGradient><linearGradient id="iYpCnAb" x1="9.698" x2="12.657" y1="10.615" y2="10.615" gradientUnits="userSpaceOnUse"><stop class="ixw8njbyx"/><stop offset="1" class="me4c4fyoe"/></linearGradient><linearGradient id="iALt8Ab" x1="15.054" x2="15.992" y1="11.859" y2="11.859" gradientUnits="userSpaceOnUse"><stop class="l38p1-72g"/><stop offset="1" class="njp0-cbrk"/></linearGradient><linearGradient id="iFZYkRc" x1="15.992" x2="15.992" y1="12.658" y2="12.047" gradientUnits="userSpaceOnUse"><stop class="vdvey0c5l"/><stop offset="1" class="tddz0-g7t"/></linearGradient><linearGradient id="ipOppDy" x1="15.992" x2="15.992" y1="9.719" y2="10.642" gradientUnits="userSpaceOnUse"><stop class="wg4z4rbcp"/><stop offset="1" class="vcmfsx9ck"/></linearGradient><linearGradient id="iNfBGck" x1="14.928" x2="15.389" y1="14.068" y2="13.356" gradientUnits="userSpaceOnUse"><stop class="b5nknil5b"/><stop offset=".663" class="prv6psg5p"/></linearGradient><linearGradient id="iBs0eNe" x1="18.952" x2="18.639" y1="9.984" y2="10.178" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iD2iKYd" x1="14.554" x2="14.24" y1="9.984" y2="10.178" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iYUSOKb" x1="13.101" x2="13.646" y1="4.329" y2="5.603" gradientUnits="userSpaceOnUse"><stop class="z66p5h_5k"/><stop offset="1" class="ll4sw0vun"/></linearGradient><linearGradient id="iFmEHve" x1="20.481" x2="8.544" y1="3.718" y2="7.406" gradientUnits="userSpaceOnUse"><stop class="muovvys4e"/><stop offset="1" class="bvsk-i9dj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-with-veil-light" /></template>
<style>
.a0fnokbdc {
  d: path("m13.196 30l-2.547-3.837l5.25-3.476l5.828 2.91L18.805 30z");
}

.a4-v90a8k {
  stop-color: var(--svg-color--1a1718, #1A1718);
}

.a5a1u75xf {
  d: path("M11.39 25.875c-.678-.6-1.716-.535-2.298.112l-.69.734c-.062.068-.04.22.024.271c.91.563 1.996.492 2.66-.27l.42-.584a.11.11 0 0 0-.009-.15z");
}

.a805jtb_d {
  stop-color: var(--svg-color--365c3e, #365C3E);
}

.al0tyek2y {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
}

.b38d6lbic {
  d: path("M10.905 9.265h.013L10.908 9l-.01-.306c.02-.949.573-1.316.81-1.439l.05-.02l.052-.02A2.3 2.3 0 0 0 13 5.98l.081-.194a.264.264 0 0 1 .462-.051a3.86 3.86 0 0 0 3.19 1.673h3.22c.18 0 1.081.088 1.135 1.333l-.119 3.073c-.123 2.802-2.312 4.684-4.983 4.684s-4.86-1.882-4.983-4.685z");
}

.b4of-6bao {
  stop-color: var(--svg-color--e5d7d2, #E5D7D2);
}

.b55qklbsj {
  stop-color: var(--svg-color--bc8272, #BC8272);
  stop-opacity: 0;
}

.b5nknil5b {
  stop-color: var(--svg-color--eabbab, #EABBAB);
}

.b8csw2ryl {
  cx: 9.168px;
  cy: 20.567px;
  r: 0.762px;
}

.bl7uysvvb {
  stop-color: var(--svg-color--181518, #181518);
}

.brg8dbpny {
  stop-color: var(--svg-color--e2a895, #E2A895);
  stop-opacity: 0;
}

.bvsk-i9dj {
  stop-color: var(--svg-color--cdc8ce, #CDC8CE);
}

.c06i-_swg {
  stop-color: var(--svg-color--fac4b3, #FAC4B3);
  stop-opacity: 0;
}

.c9_6uxbfa {
  stop-color: var(--svg-color--4a4446, #4A4446);
  stop-opacity: 0;
}

.cc9ylm0_i {
  fill: var(--svg-color--4b4648, #4B4648);
  d: path("m18.399 6.347l-1.426.262a.688.688 0 1 1-.125-1.365h2.341c1.385 0 1.843 1.395 1.899 1.872a3.15 3.15 0 0 0-2.69-.77");
}

.cgwf57bmz {
  d: path("M21.48 25.362c.063-.898.843-1.586 1.721-1.534l.99.058c.121 0 .162.158.149.207c-.176.967-.961 1.704-2 1.633l-.768-.097a.11.11 0 0 1-.102-.118z");
}

.chj8m5e2t {
  stop-color: var(--svg-color--040101, #040101);
  stop-opacity: 0;
}

.cj4rfmfkx {
  stop-color: var(--svg-color--3b3638, #3B3638);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cnrgi8b1a {
  stop-color: var(--svg-color--58843a, #58843A);
}

.ct82q_bbh {
  stop-color: var(--svg-color--cac2c0, #CAC2C0);
}

.cuv4n92_b {
  stop-color: var(--svg-color--433838, #433838);
}

.cyqt__gil {
  stop-color: var(--svg-color--f3ba97, #F3BA97);
}

.d_t8kfbgb {
  stop-color: var(--svg-color--e2a895, #E2A895);
}

.d5fabsakk {
  stop-color: var(--svg-color--d7cfcf, #D7CFCF);
  stop-opacity: 0;
}

.ddg3g7pcd {
  stop-color: var(--svg-color--cb5996, #CB5996);
}

.dkw8bsvxv {
  stop-color: var(--svg-color--f5b99d, #F5B99D);
}

.dz0-61bre {
  stop-color: var(--svg-color--487a38, #487A38);
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

.e2earo80w {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
}

.e3pms-bdy {
  fill: var(--svg-color--f1c4b2, #F1C4B2);
  d: path("m15.61 10.166l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.646-.376-.765 0");
}

.e8gnj8b4j {
  d: path("M20.82 11.602a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
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

.eodwsybla {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
  stop-opacity: 0;
}

.es9rdnb2g {
  d: path("M11.307 12.137a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.ezs6x-jxc {
  d: path("m15.61 10.166l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.646-.376-.765 0");
}

.f_q-3cc4h {
  stop-color: var(--svg-color--a47463, #A47463);
}

.f_r_72dts {
  stop-color: var(--svg-color--facc4a, #FACC4A);
}

.felc_fb-i {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
}

.fjji9zbbw {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fvm07vbkd {
  stop-color: var(--svg-color--b87c92, #B87C92);
}

.fwm5mebpo {
  stop-color: var(--svg-color--ebb1a6, #EBB1A6);
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

.ga9gd76rf {
  d: path("m20.799 26.369l-2.71-1.12l.67-1.62c.41-1 1.1-1.692 1.987-2.11c.466-.191.718.058.798.238c.3.82.081 2.137-.085 3.002z");
}

.gae5lxbxj {
  d: path("M12.712 23.24c.15-.67.84-1.06 1.5-.85l.62.211a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.267 1.09-1.277c.69-.01 1.18.527 1.18 1.25v.561a.05.05 0 0 0 .066.048l.55-.188c.64-.24 1.31.06 1.49.73c.17.65-.214 1.373-.884 1.493l-.457.1a.05.05 0 0 0-.03.079l.307.422c.44.52.34 1.32-.22 1.71s-1.296.193-1.67-.36l-.31-.413a.05.05 0 0 0-.081.003l-.242.375c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.526a.05.05 0 0 0-.032-.077l-.37-.067c-.67-.1-1.11-.75-.96-1.41");
}

.gi1yleb5l {
  stop-color: var(--svg-color--aca4a1, #ACA4A1);
}

.gic5jpboz {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.602 9.182c-.654 0-1.205.45-1.355 1.058a.274.274 0 0 0 .267.341h2.231a.23.23 0 0 0 .228-.272A1.4 1.4 0 0 0 13.6 9.182");
}

.glo437b-m {
  stop-color: var(--svg-color--040002, #040002);
  stop-opacity: 0;
}

.gn67s1beu {
  stop-color: var(--svg-color--ffef65, #FFEF65);
}

.gpoq-dbst {
  stop-color: var(--svg-color--fac4b3, #FAC4B3);
}

.h1vv8wrrd {
  d: path("M20.61 25.875c.678-.6 1.716-.535 2.297.112l.69.734c.063.068.083.205-.023.271c-.91.563-1.996.492-2.66-.27l-.42-.584a.11.11 0 0 1 .009-.15z");
}

.h71xt0usx {
  d: path("M11.326 11.602a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.hcqoaqlig {
  fill: var(--svg-color--2d2b2e, #2D2B2E);
  d: path("M17.135 9.959c.265-.467.668-.836 1.537-.836c.38 0 .747.105 1.073.369c.268.217.232.495.024.599l-.556.318c-.652-.211-1.372-.24-2.079-.45");
}

.he14dbbbc {
  stop-color: var(--svg-color--f38330, #F38330);
}

.hge7y2igm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M13.101 3.985c.023.243.235 1.157.545 1.71");
}

.hjtn79bml {
  stop-color: var(--svg-color--393134, #393134);
}

.hkormb2xp {
  stop-color: var(--svg-color--575455, #575455);
}

.hosbwkb7o {
  d: path("M10.923 4.54c.566-.6 1.637-.6 2.131-.511l.396 1.29c-.253-.038-.478.05-.668.235c-.448 1.26-1.99 1.956-2.704 2.146c-.148-1.492.11-2.38.845-3.16");
}

.hpzv-ab9a {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
  stop-opacity: 0;
}

.hr9jc16ta {
  stop-color: var(--svg-color--ffe24b, #FFE24B);
}

.hx66smwtj {
  stop-color: var(--svg-color--4a4446, #4A4446);
}

.i_w-uabpc {
  stop-color: var(--svg-color--efb59b, #EFB59B);
}

.i1hqu4kst {
  stop-color: var(--svg-color--ca992e, #CA992E);
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

.intda8ekf {
  stop-color: var(--svg-color--d09790, #D09790);
  stop-opacity: 0;
}

.ip2fbrb5p {
  d: path("M10.52 25.362c-.063-.898-.843-1.586-1.721-1.534l-.99.058c-.121 0-.162.158-.149.207c.176.967.961 1.704 2 1.633l.768-.097a.11.11 0 0 0 .102-.118z");
}

.isiq9yb3m {
  stop-color: var(--svg-color--c46399, #C46399);
}

.ixw8njbyx {
  stop-color: var(--svg-color--cc9987, #CC9987);
}

.j2p90_-bc {
  stop-color: var(--svg-color--4c4749, #4C4749);
  stop-opacity: 0;
}

.j9i7xp3bx {
  stop-color: var(--svg-color--cdc7c8, #CDC7C8);
}

.jih6tvbze {
  stop-color: var(--svg-color--3e5d50, #3E5D50);
}

.jjrmf5_5v {
  fill: var(--svg-color--3f6834, #3F6834);
  d: path("M21.819 23.476c.096.053.144.219.081.348l-.668 1.39c-.181.388-.526.926-.809 1.177c-.687.639-1.466.646-2.21.3a2.4 2.4 0 0 1-.481-.291a.97.97 0 0 1-.407.892c-.466.325-1.079.16-1.39-.3l-.258-.344a.042.042 0 0 0-.068.003l-.201.312a.966.966 0 0 1-1.374.35a.97.97 0 0 1-.241-1.415l.298-.438a.042.042 0 0 0-.027-.065l-.308-.055a.97.97 0 0 1-.799-1.173a.97.97 0 0 1 1.248-.708l.516.176a.042.042 0 0 0 .055-.042l-.025-.403c-.05-.558.514 1.048 1.08 1.04c.574-.009.81-1.664.81-1.062v.467c0 .029.028.049.055.04l.458-.157q.112-.041.223-.057l.036-.085l1.043.854c.063-.13.19-.198.295-.152c.711.327.494-.417.288.728c-.022.122.015.13.098.03c.74-.9 1.97-1.696 2.682-1.36");
}

.jk5udqbyz {
  stop-color: var(--svg-color--464444, #464444);
  stop-opacity: 0;
}

.jm8e13_st {
  stop-color: var(--svg-color--e1d6d3, #E1D6D3);
}

.jr0kq7b_h {
  fill: var(--svg-color--dca238, #DCA238);
  d: path("M15.87 25.425a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.k_kfijbew {
  stop-color: var(--svg-color--ca992e, #CA992E);
  stop-opacity: 0;
}

.k1xxa4bqz {
  stop-color: var(--svg-color--af246b, #AF246B);
  stop-opacity: 0;
}

.k2oqpgb0o {
  stop-color: var(--svg-color--f4b89e, #F4B89E);
  stop-opacity: 0;
}

.k4o_95-jn {
  fill: var(--svg-color--f6bca5, #F6BCA5);
  d: path("M20.82 11.602a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.k9-y_ac5p {
  d: path("M20.82 12.137a1.61 1.61 0 1 0 0-3.218a1.61 1.61 0 0 0 0 3.218");
}

.kbl3igr5c {
  stop-color: var(--svg-color--040002, #040002);
}

.kdxbzbgjp {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.932 8.155c.323-.078 1.125-.039 1.66.345");
}

.kfxms3gui {
  d: path("M18.972 10.228a.84.84 0 0 0-.232-.462l-.26.285l.117.228z");
}

.kk5nghg8x {
  d: path("M9.15 20.533a11.2 11.2 0 0 1 4.31-2.048c.28-.06.48-.32.48-.61V14.73c0-1.13.9-2.04 2.02-2.06c1.16-.02 2.1.95 2.1 2.1v3.105c0 .29.2.54.48.61a11.3 11.3 0 0 1 4.325 2.063a8.44 8.44 0 0 1-6.852 3.503a8.44 8.44 0 0 1-6.864-3.518");
}

.kor6y-bvl {
  fill: var(--svg-color--000, #000);
  d: path("M14.32 10.346a.51.51 0 0 0-.512-.511a.51.51 0 0 0-.454.746h.905a.5.5 0 0 0 .06-.235");
}

.kv9fthb_h {
  stop-color: var(--svg-color--dfc7b5, #DFC7B5);
}

.l-mrnsw2p {
  d: path("M9.984 15.922c0-4.853 2.694-7.28 6.016-7.28s6.016 2.323 6.016 7.28v7.436H9.984z");
}

.l0xg-rbdf {
  stop-color: var(--svg-color--040101, #040101);
}

.l33l9dqgq {
  stop-color: var(--svg-color--e16fa7, #E16FA7);
}

.l38p1-72g {
  stop-color: var(--svg-color--dfa791, #DFA791);
}

.l5x2v-b4z {
  cx: 13.539px;
  cy: 9.835px;
  rx: 0.39px;
  ry: 0.197px;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l9b4opb5t {
  stop-color: var(--svg-color--338e58, #338E58);
  stop-opacity: 0;
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

.lrfw_3buu {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.993 13.44c-.521 0-1.01-.126-1.422-.345c-.14-.073-.292.089-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.137-.063-.293-.204-.22c-.411.22-.896.345-1.422.345Z");
}

.m08rdxbim {
  d: path("M18.177 9.454a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.m65aglb3j {
  d: path("M23.457 22.828c.076-.155.018-.354-.098-.418c-.854-.404-2.334.552-3.222 1.633c-.099.12-.144.112-.117-.035c.247-1.376.009-3.139-.846-3.532c-.127-.055-.279.027-.355.183l-.754 1.631c-.044.107-.088.204-.132.311c-.111.293-.303.839-.336 1.135c-.152 1.231.46 2.09 1.43 2.537c.894.415 1.83.406 2.656-.36c.34-.303.754-.948.972-1.414z");
}

.m92tte26k {
  stop-color: var(--svg-color--e170ad, #E170AD);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.me4c4fyoe {
  stop-color: var(--svg-color--ac7864, #AC7864);
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

.mt5e72-yt {
  stop-color: var(--svg-color--ffd4b8, #FFD4B8);
}

.mu5z5titl {
  stop-color: var(--svg-color--c6bebf, #C6BEBF);
}

.muovvys4e {
  stop-color: var(--svg-color--e2dfe3, #E2DFE3);
}

.mw8ur5bua {
  fill: var(--svg-color--232121, #232121);
  d: path("M10.923 4.54c.566-.6 1.637-.6 2.131-.511l.396 1.29c-.253-.038-.478.05-.668.235c-.448 1.26-1.99 1.956-2.704 2.146c-.148-1.492.11-2.38.845-3.16");
}

.mxnnm4bur {
  stop-color: var(--svg-color--464444, #464444);
}

.myo455mpg {
  d: path("M14.624 10.24c0-.287-.235-.48-.298-.538l-.289.279l.178.361z");
}

.n0n4e7bnh {
  stop-color: var(--svg-color--f3f0ef, #F3F0EF);
}

.n1imc2b4i {
  stop-color: var(--svg-color--4f8436, #4F8436);
}

.n1w64orcn {
  stop-color: var(--svg-color--b87c92, #B87C92);
  stop-opacity: 0;
}

.nbz8snbyn {
  stop-color: var(--svg-color--f2f1f2, #F2F1F2);
  stop-opacity: 0;
}

.ndghkrcwe {
  stop-color: var(--svg-color--c3bbbb, #C3BBBB);
}

.nhvn8xbgd {
  stop-color: var(--svg-color--e19584, #E19584);
}

.njp0-cbrk {
  stop-color: var(--svg-color--dfa791, #DFA791);
  stop-opacity: 0;
}

.nljy2k17i {
  fill-rule: evenodd;
  d: path("M15.972 4.43c-3.812 0-5.694 1.657-6.334 2.38a.775.775 0 1 1-1.16-1.027c.88-.996 3.165-2.902 7.494-2.902c4.41 0 6.608 1.915 7.54 2.876A.775.775 0 1 1 22.4 6.836c-.735-.757-2.556-2.405-6.428-2.405");
}

.nof2xyhhe {
  stop-color: var(--svg-color--d1ced0, #D1CED0);
  stop-opacity: 0;
}

.nq8ap6btb {
  fill: var(--svg-color--d19590, #D19590);
  d: path("m15.6 10.305l-.684 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.53-1.7c-.114-.377-.494-.377-.613 0");
}

.nthvp6bhf {
  d: path("M8.528 22.828c-.076-.155-.018-.354.098-.418c.854-.404 2.333.552 3.222 1.633c.099.12.144.112.117-.035c-.248-1.376-.009-3.139.846-3.532c.126-.055.278.027.355.183l.753 1.631l.133.311c.111.293.303.839.336 1.135c.152 1.231-.46 2.09-1.43 2.537c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.948-.972-1.414z");
}

.nwt8glb0m {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
  stop-opacity: 0;
}

.ny041mpzr {
  d: path("M13.808 9.454a.892.892 0 0 0-.86 1.128h1.724a1 1 0 0 0 .033-.235a.9.9 0 0 0-.897-.893");
}

.o38c5rykb {
  stop-color: var(--svg-color--ffef65, #FFEF65);
  stop-opacity: 0;
}

.o5a57gb_x {
  d: path("M5.062 16.5c0-8.812 4.89-13.219 10.922-13.219S26.906 7.5 26.906 16.5V30H5.062z");
}

.o8rnhccaw {
  d: path("m15.61 10.001l-.531 1.7a.54.54 0 0 0 .52.7h.787a.54.54 0 0 0 .52-.7l-.531-1.7c-.114-.376-.646-.376-.765 0");
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

.onrup1btv {
  stop-color: var(--svg-color--eea990, #EEA990);
  stop-opacity: 0;
}

.ou3onybvn {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
}

.oujulfp4v {
  d: path("M18.11 9.642c.064.085-.069.189-.22.302c-.15.113-.263.192-.326.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.p5ii0k_1a {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
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

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.plguddvmo {
  fill: var(--svg-color--dc62a7, #DC62A7);
  d: path("M23.457 22.828c.076-.155.018-.354-.098-.418c-.854-.404-2.334.552-3.222 1.633c-.099.12-.144.112-.117-.035c.247-1.376.009-3.139-.846-3.532c-.127-.055-.279.027-.355.183l-.754 1.631c-.044.107-.088.204-.132.311c-.111.293-.303.839-.336 1.135c-.152 1.231.46 2.09 1.43 2.537c.894.415 1.83.406 2.656-.36c.34-.303.754-.948.972-1.414z");
}

.pp_chx--o {
  fill-rule: evenodd;
  d: path("M23.178 11.938a3.25 3.25 0 0 0 .323-1.427a3.3 3.3 0 0 0-.268-1.306h.005a3 3 0 0 0-.28-.513l-.003-.003a3.24 3.24 0 0 1-.526-1.77v-.01a3.3 3.3 0 0 0-3.3-3.3a.54.54 0 0 1-.455-.233A3.3 3.3 0 0 0 15.992 2a3.3 3.3 0 0 0-2.682 1.376a.56.56 0 0 1-.455.233l-.085.001a3.3 3.3 0 0 0-3.214 3.298v.01A3.24 3.24 0 0 1 9.03 8.69l-.003.004a3.3 3.3 0 0 0-.22 3.245a.51.51 0 0 1 0 .455a3.213 3.213 0 0 0 2.894 4.625h8.582a3.213 3.213 0 0 0 3.218-3.218c0-.506-.12-.982-.323-1.407a.51.51 0 0 1 0-.455m-12.26-2.673h-.013l1.199 2.356c.123 2.803 1.217 0 3.888 0c2.672 0 3.837 3.12 3.96.317l1.136-3.197c-.054-1.245-.956-1.332-1.136-1.332h-3.22a3.86 3.86 0 0 1-3.19-1.674a.264.264 0 0 0-.46.051l-.083.194c-.225.561-.656.99-1.19 1.235q-.023.008-.05.02l-.052.02c-.236.123-.79.49-.81 1.44l.01.305z");
}

.prv6psg5p {
  stop-color: var(--svg-color--eabbab, #EABBAB);
  stop-opacity: 0;
}

.pzpwlzysi {
  stop-color: var(--svg-color--8bc659, #8BC659);
  stop-opacity: 0;
}

.q1wk2zbta {
  stop-color: var(--svg-color--c8857d, #C8857D);
}

.q9uatzb-b {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  fill-rule: evenodd;
  d: path("m19.724 8.292l-.138.23za.268.268 0 0 1-.275.46l-.005-.002l-.022-.012l-.091-.047a3 3 0 0 0-.343-.135a2.3 2.3 0 0 0-1.072-.091a.268.268 0 1 1-.093-.529c.513-.09.989.001 1.328.11a3.3 3.3 0 0 1 .559.238l.01.005l.002.002z");
}

.qpkqxibzk {
  stop-color: var(--svg-color--ffd6c2, #FFD6C2);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwp4ni-tf {
  stop-color: var(--svg-color--171418, #171418);
  stop-opacity: 0;
}

.qx4s8jbjv {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M16.098 21.094c.324 0 .758.376.758.86v.944");
}

.r_s898b6a {
  stop-color: var(--svg-color--b81560, #B81560);
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

.rb6miyacc {
  stop-color: var(--svg-color--eea990, #EEA990);
}

.rla7irgzy {
  fill: var(--svg-color--aaaeae, #AAAEAE);
  d: path("M19.688 26.04c.78-.46 1.787-.2 2.235.546l.538.852c.048.078.043.217-.074.261c-1 .38-2.053.105-2.561-.77l-.302-.652a.11.11 0 0 1 .037-.145z");
}

.rsfcoybzb {
  stop-color: var(--svg-color--64a25a, #64A25A);
}

.ruz641x6w {
  stop-color: var(--svg-color--d76316, #D76316);
  stop-opacity: 0;
}

.ryatr-kxe {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.11 9.642c.064.085-.069.189-.22.302c-.15.113-.263.192-.326.107c-.064-.085.007-.245.158-.358s.325-.136.389-.05");
}

.s_ql7obry {
  stop-color: var(--svg-color--ffceba, #FFCEBA);
}

.s44y8_wdc {
  stop-color: var(--svg-color--a47463, #A47463);
  stop-opacity: 0;
}

.sa_c7ns7l {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
}

.sfz55pe2y {
  fill: var(--svg-color--272528, #272528);
  d: path("M14.85 9.959c-.265-.467-.668-.836-1.537-.836c-.38 0-.747.105-1.073.369c-.268.217-.232.495-.024.599l.556.318c.652-.211 1.372-.24 2.079-.45");
}

.sheftacio {
  stop-color: var(--svg-color--ffd8c1, #FFD8C1);
}

.silozpblh {
  stop-color: var(--svg-color--3b3638, #3B3638);
  stop-opacity: 0;
}

.sjzpc70ui {
  fill: var(--svg-color--c58c80, #C58C80);
  d: path("M11.326 11.602a1.074 1.074 0 1 0 0-2.148a1.074 1.074 0 0 0 0 2.148");
}

.sqxrh1b6n {
  stop-color: var(--svg-color--ffd8bc, #FFD8BC);
}

.ssbc2ccsr {
  stop-color: var(--svg-color--1f0d24, #1F0D24);
  stop-opacity: 0;
}

.suybu51ug {
  stop-color: var(--svg-color--d09790, #D09790);
}

.t-y5i3b_t {
  stop-color: var(--svg-color--8ac463, #8AC463);
}

.tddz0-g7t {
  stop-color: var(--svg-color--d29394, #D29394);
  stop-opacity: 0;
}

.tgwkdpbql {
  stop-color: var(--svg-color--bab5b4, #BAB5B4);
}

.tk20gvbnd {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
  stop-opacity: 0;
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

.tvt8ccczx {
  d: path("m11.186 26.369l2.71-1.12l-.67-1.62c-.41-1-1.1-1.692-1.988-2.11c-.465-.191-.717.058-.797.238c-.3.82-.081 2.137.085 3.002z");
}

.ty1ewib_q {
  stop-color: var(--svg-color--e170ad, #E170AD);
  stop-opacity: 0;
}

.u3ly29i0x {
  stop-color: var(--svg-color--af246b, #AF246B);
}

.uaoaczbhz {
  stop-color: var(--svg-color--bc8272, #BC8272);
}

.uaxm8f1hq {
  stop-color: var(--svg-color--338e58, #338E58);
}

.ue4tj-40t {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("m17.348 24.86l.907 1.18");
}

.ujdq-6enc {
  stop-color: var(--svg-color--d2cfd8, #D2CFD8);
}

.uq7zq9b9u {
  stop-color: var(--svg-color--c46399, #C46399);
  stop-opacity: 0;
}

.uwzhnobuw {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M15.993 13.44c-.521 0-1.01-.126-1.422-.345c-.14-.073-.292.089-.203.22a1.932 1.932 0 0 0 3.25 0c.088-.137-.063-.293-.204-.22c-.411.22-.896.345-1.422.345");
}

.uy9-hlbji {
  stop-color: var(--svg-color--fff967, #FFF967);
  stop-opacity: 0;
}

.v-9tn59hb {
  stop-color: var(--svg-color--dba98b, #DBA98B);
  stop-opacity: 0;
}

.v3n252bdr {
  d: path("M27 30v-1c0-5.2-3.61-9.365-8.46-10.515a.63.63 0 0 1-.48-.61V14.77c0-1.15-.94-2.12-2.1-2.1c-1.12.02-2.02.93-2.02 2.06v3.145c0 .29-.2.55-.48.61C8.61 19.625 5 23.8 5 29v1z");
}

.v5rheyc4i {
  stop-color: var(--svg-color--ffd7bf, #FFD7BF);
}

.v9-8bpxan {
  stop-color: var(--svg-color--a3a2a8, #A3A2A8);
}

.v904-8f9f {
  fill: var(--svg-color--c55496, #C55496);
  d: path("M8.528 22.828c-.076-.155-.018-.354.098-.418c.854-.404 2.333.552 3.222 1.633c.099.12.144.112.117-.035c-.248-1.376-.009-3.139.846-3.532c.126-.055.278.027.355.183l.753 1.631l.133.311c.111.293.303.839.336 1.135c.152 1.231-.46 2.09-1.43 2.537c-.894.415-1.83.406-2.656-.36c-.34-.303-.754-.948-.972-1.414z");
}

.vba3cacoe {
  d: path("M15.39 2.737c-1.133-.25-2.15.88-2.268 1.299c1.052 3.545 3.713 3.35 6.34 3.059c1.573-.175 1.743.542 1.877.888c0-3.933-3.344-4.67-5.921-5.24z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vcmfsx9ck {
  stop-color: var(--svg-color--efc2b0, #EFC2B0);
  stop-opacity: 0;
}

.vdvey0c5l {
  stop-color: var(--svg-color--d29394, #D29394);
}

.vgt2qnb2u {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.383 9.182c.654 0 1.205.45 1.355 1.058a.274.274 0 0 1-.267.341h-2.232a.23.23 0 0 1-.227-.272a1.4 1.4 0 0 1 1.371-1.127");
}

.vlhzj-bky {
  fill: var(--svg-color--9b9da0, #9B9DA0);
  d: path("M9.134 24.212c.879-.052 1.658.636 1.72 1.534l.009.116c.31.043.61.175.862.397l.107.114a.11.11 0 0 1 .01.15l-.42.582c-.665.763-1.75.833-2.66.27c-.064-.05-.086-.202-.024-.27l.69-.734q.136-.152.302-.26c-.906-.06-1.574-.75-1.735-1.634c-.013-.049.028-.207.15-.207z");
}

.vt544m69k {
  stop-color: var(--svg-color--e19584, #E19584);
  stop-opacity: 0;
}

.w--6bgeqj {
  stop-color: var(--svg-color--e5b1a5, #E5B1A5);
}

.w13qlvl6z {
  stroke: var(--svg-color--323233, #323233);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.141 8.155c-.322-.078-1.124-.039-1.66.345");
}

.w5vkn-xtc {
  cx: 13.539px;
  cy: 9.835px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.wa496n4py {
  stop-color: var(--svg-color--ecb12a, #ECB12A);
  stop-opacity: 0;
}

.wg4z4rbcp {
  stop-color: var(--svg-color--efc2b0, #EFC2B0);
}

.wh23x9bjk {
  stop-color: var(--svg-color--fff763, #FFF763);
}

.wjaz7obfy {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m12.595 8.75l-.005.002a.268.268 0 0 1-.275-.46h.001l.003-.002l.01-.006l.032-.018l.116-.059c.099-.047.24-.107.41-.161c.34-.109.815-.2 1.329-.11a.268.268 0 0 1-.094.529a2.3 2.3 0 0 0-1.072.091a3 3 0 0 0-.455.194");
}

.wkalc4bst {
  stop-color: var(--svg-color--d35897, #D35897);
  stop-opacity: 0;
}

.wsyd1pyom {
  stop-color: var(--svg-color--fff763, #FFF763);
  stop-opacity: 0;
}

.wum9l96_j {
  stop-color: var(--svg-color--d59f97, #D59F97);
}

.x7zyp6nnz {
  fill: var(--svg-color--ffdd2c, #FFDD2C);
  d: path("M12.712 23.24c.15-.67.84-1.06 1.5-.85l.62.211a.05.05 0 0 0 .066-.05l-.03-.484c-.06-.67.41-1.267 1.09-1.277c.69-.01 1.18.527 1.18 1.25v.561a.05.05 0 0 0 .066.048l.55-.188c.64-.24 1.31.06 1.49.73c.17.65-.214 1.373-.884 1.493l-.457.1a.05.05 0 0 0-.03.079l.307.422c.44.52.34 1.32-.22 1.71s-1.296.193-1.67-.36l-.31-.413a.05.05 0 0 0-.081.003l-.242.375c-.32.59-1.08.79-1.65.42c-.58-.37-.71-1.16-.29-1.7l.357-.526a.05.05 0 0 0-.032-.077l-.37-.067c-.67-.1-1.11-.75-.96-1.41");
}

.xbgj88f0b {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
}

.xdn388byj {
  stop-color: var(--svg-color--171418, #171418);
}

.xevmwcccx {
  fill-rule: evenodd;
  d: path("M13.709 24.403a.913.913 0 0 1-.753-1.107a.91.91 0 0 1 1.178-.668l.617.21a.3.3 0 0 0 .396-.303l-.03-.484v-.007q-.019-.216.044-.404a.85.85 0 0 1 .8-.6c.532-.008.927.396.927 1v.561a.3.3 0 0 0 .396.284l.551-.187l.007-.003c.516-.193 1.023.047 1.16.56c.14.532-.183 1.092-.687 1.183l-.466.103a.3.3 0 0 0-.178.469l.312.43l.006.007a.92.92 0 0 1-.172 1.343c-.429.299-1.012.16-1.32-.295l-.316-.423a.3.3 0 0 0-.493.017l-.247.384l-.005.008a.91.91 0 0 1-1.294.33l-.001-.002a.92.92 0 0 1-.227-1.335l.005-.007l.362-.533a.3.3 0 0 0-.196-.463l-.369-.067z");
}

.xflvpmp1u {
  stop-color: var(--svg-color--d4d0d4, #D4D0D4);
  stop-opacity: 0;
}

.xgo5xrbyv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M15.92 18.913c.395.01 1.357-.063 2.05-.441");
}

.xl9xm7bnj {
  stop-color: var(--svg-color--f6baa9, #F6BAA9);
  stop-opacity: 0;
}

.xm2ilgmxp {
  d: path("M15.993 25.293a1.1 1.1 0 1 0 0-2.2a1.1 1.1 0 0 0 0 2.2");
}

.xo240subg {
  stop-color: var(--svg-color--d76316, #D76316);
}

.y_9l2i5ww {
  stop-color: var(--svg-color--ffdcc5, #FFDCC5);
  stop-opacity: 0;
}

.y32ab_wii {
  stop-color: var(--svg-color--bcb7bd, #BCB7BD);
  stop-opacity: 0;
}

.y8qpet1tz {
  stop-color: var(--svg-color--34673c, #34673C);
}

.ycdc5fyuc {
  cx: 10.18px;
  cy: 21.645px;
  r: 0.762px;
}

.yhk8aqbmk {
  stop-color: var(--svg-color--e6dcda, #E6DCDA);
  stop-opacity: 0;
}

.yisy14b-j {
  fill: var(--svg-color--2a2a2a, #2A2A2A);
  d: path("M15.39 2.737c-1.133-.25-2.15.88-2.268 1.299c1.052 3.545 3.713 3.35 6.34 3.059c1.573-.175 1.743.542 1.877.888c0-3.933-3.344-4.67-5.921-5.24z");
}

.ynae43ovp {
  stop-color: var(--svg-color--dba98b, #DBA98B);
}

.yvysc04cm {
  stop-color: var(--svg-color--f3ba97, #F3BA97);
  stop-opacity: 0;
}

.z-rzt8b_f {
  stop-color: var(--svg-color--ffdebf, #FFDEBF);
}

.z3hpt3mcq {
  stop-color: var(--svg-color--8bc659, #8BC659);
}

.z6_95pbhj {
  fill: var(--svg-color--000, #000);
  d: path("M17.665 10.346a.51.51 0 0 1 .512-.511a.51.51 0 0 1 .454.746h-.905a.46.46 0 0 1-.06-.235");
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

.zpmzd2b_c {
  stop-color: var(--svg-color--ffceba, #FFCEBA);
  stop-opacity: 0;
}

.zxvvm-hti {
  stop-color: var(--svg-color--d9cabf, #D9CABF);
}

.zzvuu8b-w {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.434 22.64c.307.136.83.616.461 1.454");
}

</style>
