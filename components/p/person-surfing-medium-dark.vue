<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iL99E6d)"><path class="c4gk4qbre"/><path fill="url(#i5BMVwc)" class="vc0stzb2b"/></g><path fill="url(#i0MA8Pb)" class="vc0stzb2b"/><path fill="url(#iiC4tnd)" class="vc0stzb2b"/><path fill="url(#il2gNce)" class="vc0stzb2b"/><path fill="url(#iQQsnkb)" class="vc0stzb2b"/><g filter="url(#ipFtHzU)"><path class="ztof03btl"/><path fill="url(#iki95tc)" class="udjnzvwry"/></g><path class="sqq33qb1e"/><path fill="url(#iZruFCc)" class="vsa9yt_zc"/><path fill="url(#i3oGTgd)" class="txy8o-b9p"/><path fill="url(#i3DEP3c)" class="y4sbh5bmj"/><path fill="url(#iubnsVb)" class="y4sbh5bmj"/><g filter="url(#iDJlXac)"><path fill="url(#iwWmMLd)" class="rtugrsb1s"/><path fill="url(#irnG2Ck)" class="rtugrsb1s"/></g><g filter="url(#i76sK2b)"><circle fill="url(#iaiKPvk)" class="lhouptx_t"/></g><g filter="url(#iQ0MlHd)"><circle fill="url(#iDiiZ5c)" class="xyr1brbaw"/></g><g filter="url(#iK8C5ie)"><circle fill="url(#i7KP5xd)" class="nb1sixbgm"/></g><rect fill="url(#ieiFNec)" transform="rotate(26.595 19.986 12.81)" class="h3fjnxbnc"/><g filter="url(#iE39Xuc)"><path fill="url(#i6MmWBb)" class="bcvezxuef"/></g><path class="s69jymf9k"/><g filter="url(#iSl44qb)"><path class="d8d_cybzn"/><path fill="url(#iLcRJrb)" class="bx_ajvbxr"/><path fill="url(#iforxfd)" class="bx_ajvbxr"/></g><g filter="url(#izgiHXd)"><path fill="url(#iAWqJve)" class="n3ivew17u"/><path fill="url(#igVY3Qd)" class="n3ivew17u"/><path fill="url(#iNU6Yqd)" class="n3ivew17u"/></g><path fill="url(#iTJLgWT)" class="utzn9kn9q"/><path fill="url(#iZyC5Pe)" class="utzn9kn9q"/><path clip-rule="evenodd" class="wks9ssbug"/><path fill="url(#igyXhqd)" clip-rule="evenodd" class="fveku386v"/><path clip-rule="evenodd" class="qswrskbcf"/><path fill="url(#iY2kcqd)" clip-rule="evenodd" class="eylv4trdg"/><path clip-rule="evenodd" class="zl6_f2bcr"/><path fill="url(#iQQZQ7s)" clip-rule="evenodd" class="f4nse45rd"/><path clip-rule="evenodd" class="cr6tek86r"/><path fill="url(#iAiNhlZ)" clip-rule="evenodd" class="lpxhpcbvx"/><path class="z9uidyb6w"/><path fill="url(#ifSj2He)" class="ja57asbbp"/><g filter="url(#iYrTV7V)"><path fill="url(#iy8zW5c)" class="rn9fbxb5o"/></g><g filter="url(#ibrKzAe)"><path fill="url(#il5WOtc)" class="iejf4hbly"/></g><g filter="url(#iic9BCc)"><path stroke="url(#ipHtwtH)" class="xwdp292ir"/></g><path fill="url(#iikPeVd)" class="vtn8sbczo"/><path fill="url(#ibZHohE)" class="waxuy09cc"/><g filter="url(#iYWZvKd)"><path fill="url(#ipvHpWb)" class="hd_0eypmm"/><path fill="url(#i1jcPyd)" class="hd_0eypmm"/></g><path fill="url(#i6eefNl)" class="hd_0eypmm"/><path fill="url(#i5BeIkc)" class="hd_0eypmm"/><path fill="url(#icemknc)" class="hd_0eypmm"/><path fill="url(#imMBTub)" class="hd_0eypmm"/><path fill="url(#i5N9F1d)" class="hd_0eypmm"/><path fill="url(#ir1ZmQe)" class="hd_0eypmm"/><path fill="url(#ixq7pcc)" class="hd_0eypmm"/><g filter="url(#i0XLkfc)"><path class="u9r0afb_s"/></g><g filter="url(#ig0PcOd)"><path class="wg7_ywkcx"/><path fill="url(#imfavAb)" class="z8g0bbbjy"/><path fill="url(#inqpake)" class="z8g0bbbjy"/><path fill="url(#ic5lqHN)" class="z8g0bbbjy"/><path fill="url(#iI9m0Je)" class="z8g0bbbjy"/><path fill="url(#iFNMzKd)" class="z8g0bbbjy"/></g><g filter="url(#ir8HTVs)"><path stroke="url(#i6cSHcd)" class="f7qmk1bul"/></g><path fill="url(#ihGe3ce)" class="yfve034tb"/><g filter="url(#iE4Oglc)"><path fill="url(#ibU4Y1D)" class="pohq21btr"/><path fill="url(#iCoEVMe)" class="pohq21btr"/><path fill="url(#iwpN9mc)" class="pohq21btr"/><path fill="url(#iOO4jOe)" class="pohq21btr"/><path fill="url(#i6c8UOe)" class="pohq21btr"/></g><g filter="url(#iPBSgzc)"><path class="v781osfkd"/></g><g filter="url(#ioqKSSd)"><path class="aplp_ackh"/></g><g filter="url(#iiiEG5d)"><path class="ukqtbzb_a"/><path fill="url(#iEY29tn)" class="izj80v7dd"/><path fill="url(#iQmETLe)" class="izj80v7dd"/></g><g filter="url(#i6unNkd)"><path class="zj7dribao"/><path fill="url(#i1ZS3Hb)" class="ac-xhp72k"/><path fill="url(#iFCfpjr)" class="ac-xhp72k"/></g><path class="e-26k1bqp"/><path fill="url(#iKalOxe)" class="sxt3ddbys"/><path class="u4co9oitl"/><g filter="url(#i7aPDvc)"><path class="qm0xijb6f"/><path fill="url(#i3l6cud)" class="bhnh5qkwr"/></g><g filter="url(#iMIlO0c)"><path fill="url(#ibQp6Nc)" class="hfpnvrbth"/></g><path class="iunk_4d6b"/><path fill="url(#i300t4d)" class="efbqcfj9w"/><path class="dsgg-lbtf"/><g filter="url(#iqA7QFd)"><path fill="url(#i1t82Pc)" class="pu_jwmefu"/></g><g filter="url(#iS7c8hj)"><ellipse transform="rotate(-27.914 12.417 5.695)" class="l1l492bnf"/><ellipse fill="url(#iqee0kb)" transform="rotate(-27.914 12.417 5.695)" class="w8g7f6hkf"/></g><path fill="url(#ie1NnIb)" class="p_kbfib2a"/><path fill="url(#ix8efQO)" class="p_kbfib2a"/><path fill="url(#iRYWDfa)" class="p_kbfib2a"/><path fill="url(#ilY03Dc)" class="p_kbfib2a"/><path fill="url(#iO9aHDb)" class="n_yk4s7wv"/><path fill="url(#ioXQVYb)" class="n_yk4s7wv"/><g filter="url(#iR3n8te)"><path fill="url(#iBBmkUc)" class="z3n_enlzo"/></g><g filter="url(#i1HcLwl)"><path fill="url(#ii34VQj)" class="hlo9g_x7r"/></g><g filter="url(#iAyatZS)"><path class="pss3eyexw"/></g><defs><radialGradient id="i0MA8Pb" cx="0" cy="0" r="1" gradientTransform="matrix(3.84373 7.81251 -11.27829 5.54887 20.309 21.77)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="er0557b1s"/><stop offset=".913" class="qg0p67bet"/></radialGradient><radialGradient id="il2gNce" cx="0" cy="0" r="1" gradientTransform="matrix(3.56253 -6.12498 3.8162 2.21965 21.528 21.926)" gradientUnits="userSpaceOnUse"><stop class="vj0--9brr"/><stop offset="1" class="holozbkuz"/></radialGradient><radialGradient id="iQQsnkb" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 -12.12496 23.16436 4.11944 22.934 28.77)" gradientUnits="userSpaceOnUse"><stop offset=".931" class="ro0d6lgcg"/><stop offset="1" class="ghsb7_-dv"/></radialGradient><radialGradient id="iki95tc" cx="0" cy="0" r="1" gradientTransform="matrix(1.09706 3.375 -16.62038 5.40254 15.494 25.208)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="czuo201bw"/><stop offset="1" class="ecs-9379l"/></radialGradient><radialGradient id="iZruFCc" cx="0" cy="0" r="1" gradientTransform="matrix(-.83721 2.51163 -.64638 -.21546 9.086 25.14)" gradientUnits="userSpaceOnUse"><stop class="nz1yf2bug"/><stop offset="1" class="c2e0llb1c"/></radialGradient><radialGradient id="iubnsVb" cx="0" cy="0" r="1" gradientTransform="matrix(-.73437 -1.28906 .42946 -.24466 22.903 25.473)" gradientUnits="userSpaceOnUse"><stop class="kzew_oulk"/><stop offset="1" class="ui2bqrbyd"/></radialGradient><radialGradient id="irnG2Ck" cx="0" cy="0" r="1" gradientTransform="rotate(-110.045 20.404 3.055)scale(2.46162 1.62421)" gradientUnits="userSpaceOnUse"><stop class="of_rz239k"/><stop offset="1" class="lvv_hcmig"/></radialGradient><radialGradient id="iaiKPvk" cx="0" cy="0" r="1" gradientTransform="rotate(146.686 10.877 11.037)scale(2.36974 1.91739)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="b07bm3qgt"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="iDiiZ5c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47607 .92253 -.74644 -1.19432 28.744 12.556)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="i7KP5xd" cx="0" cy="0" r="1" gradientTransform="rotate(147.995 11.83 9.075)scale(1.52552 1.23432)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="ieiFNec" cx="0" cy="0" r="1" gradientTransform="matrix(-.06342 .73199 -.55995 -.04852 20.349 13.108)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="bv25hsebv"/><stop offset="1" class="j_v8jdemw"/></radialGradient><radialGradient id="i6MmWBb" cx="0" cy="0" r="1" gradientTransform="rotate(139.295 8.861 10.8)scale(2.80315 2.75944)" gradientUnits="userSpaceOnUse"><stop class="m3ok-p19m"/><stop offset="1" class="fv0gs1r5b"/></radialGradient><radialGradient id="iLcRJrb" cx="0" cy="0" r="1" gradientTransform="rotate(142.524 4.588 6.603)scale(4.72526 1.21438)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="yt5sdf2gy"/><stop offset="1" class="n0_4eow9o"/></radialGradient><radialGradient id="iforxfd" cx="0" cy="0" r="1" gradientTransform="rotate(103.462 1.997 10.286)scale(4.16121 1.35388)" gradientUnits="userSpaceOnUse"><stop class="nf0740e8o"/><stop offset="1" class="fltjd-k8p"/></radialGradient><radialGradient id="igVY3Qd" cx="0" cy="0" r="1" gradientTransform="matrix(4.2188 -6.78122 .53719 .3342 10.653 24.426)" gradientUnits="userSpaceOnUse"><stop class="qfyn005sz"/><stop offset="1" class="inzu6lb7s"/></radialGradient><radialGradient id="iNU6Yqd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.09375 -2.46875 0 13.09 8.239)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="fu31k5bmq"/><stop offset="1" class="zkqd2ycat"/></radialGradient><radialGradient id="iZyC5Pe" cx="0" cy="0" r="1" gradientTransform="rotate(24.436 -15.863 46.788)scale(3.39814 2.30082)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="s41d30h-g"/><stop offset="1" class="woc0miqaj"/></radialGradient><radialGradient id="igyXhqd" cx="0" cy="0" r="1" gradientTransform="rotate(-164.074 4.025 6.488)scale(1.78035 1.88131)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="jgkh1vbol"/><stop offset="1" class="wvc2-1b2k"/></radialGradient><radialGradient id="iY2kcqd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6671 -.63637 .8491 -2.2244 5.68 14.404)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="jgkh1vbol"/><stop offset="1" class="wvc2-1b2k"/></radialGradient><radialGradient id="iQQZQ7s" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6486 -.68743 .9779 -2.34523 5.501 14.947)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="jgkh1vbol"/><stop offset="1" class="wvc2-1b2k"/></radialGradient><radialGradient id="iAiNhlZ" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40308 -.60156 .87252 -2.03506 5.619 15.217)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="jgkh1vbol"/><stop offset="1" class="wvc2-1b2k"/></radialGradient><radialGradient id="ifSj2He" cx="0" cy="0" r="1" gradientTransform="matrix(.14063 .15625 -.6598 .59382 6.36 14.78)" gradientUnits="userSpaceOnUse"><stop class="d0tatcb7l"/><stop offset="1" class="ri6ddsbqu"/></radialGradient><radialGradient id="iy8zW5c" cx="0" cy="0" r="1" gradientTransform="rotate(135 10.17 15.263)scale(15.9541 20.2938)" gradientUnits="userSpaceOnUse"><stop class="q7quaubxc"/><stop offset="1" class="kf-sl5b6g"/></radialGradient><radialGradient id="iikPeVd" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 3.089 14.493)scale(.95239 1.13136)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="ibZHohE" cx="0" cy="0" r="1" gradientTransform="matrix(.65285 .20518 -.633 2.0141 10.824 6.775)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="ipvHpWb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31162 0 0 -4.08923 14.743 6.142)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="i1jcPyd" cx="0" cy="0" r="1" gradientTransform="matrix(-.77078 1.27477 -1.05243 -.63634 14.575 3.94)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="i5BeIkc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.00505 3.25847 0 13.494 8.968)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="hjvcixbup"/><stop offset=".432" class="jg-b8c5-y"/><stop offset="1" class="y7x-29baz"/></radialGradient><radialGradient id="icemknc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.50777 .62837 0 14.584 5.562)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="imMBTub" cx="0" cy="0" r="1" gradientTransform="matrix(.00174 -.48386 .52656 .0019 12.485 5.582)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="i5N9F1d" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 7.406 3.526)scale(3.76418 9.61559)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="ir1ZmQe" cx="0" cy="0" r="1" gradientTransform="matrix(1.4971 -1.2896 .38092 .44222 10.499 4.934)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="ixq7pcc" cx="0" cy="0" r="1" gradientTransform="matrix(-.10377 1.1043 -.44144 -.04148 15.953 4.852)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="inqpake" cx="0" cy="0" r="1" gradientTransform="matrix(0 .10794 -.33923 0 13.708 6.744)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="iI9m0Je" cx="0" cy="0" r="1" gradientTransform="rotate(155.369 6.171 4.748)scale(.73994 1.18914)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="ihGe3ce" cx="0" cy="0" r="1" gradientTransform="matrix(.96482 -.47433 1.90835 3.8817 13.285 7.744)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iCoEVMe" cx="0" cy="0" r="1" gradientTransform="scale(3.9152 1.54819)rotate(-90 3 .141)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iwpN9mc" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 10.673 -5.468)scale(1.11213 1.97047)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iOO4jOe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04301 -.68599 .50355 -.76562 15.318 2.667)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="i6c8UOe" cx="0" cy="0" r="1" gradientTransform="matrix(.297 .52983 -1.22682 .6877 13.102 1.964)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="iEY29tn" cx="0" cy="0" r="1" gradientTransform="matrix(-.97328 0 0 -.36122 13.614 2.962)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iQmETLe" cx="0" cy="0" r="1" gradientTransform="matrix(1.423 -2.25307 2.49617 1.57653 11.1 4.705)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="i1ZS3Hb" cx="0" cy="0" r="1" gradientTransform="matrix(1.18446 -1.1285 2.066 2.16844 14.666 4.649)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="iFCfpjr" cx="0" cy="0" r="1" gradientTransform="rotate(6.667 -27.165 124.54)scale(1.44605 .60543)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iKalOxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35874 -.57062 0 14.467 5.737)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i3l6cud" cx="0" cy="0" r="1" gradientTransform="matrix(-.10255 -.13215 .18193 -.14118 14.366 5.774)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i300t4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35876 -.57065 0 12.537 5.737)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iqee0kb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00342 -.21847 .26261 -.00411 12.41 5.834)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ix8efQO" cx="0" cy="0" r="1" gradientTransform="matrix(.27792 .99192 -.94637 .26516 15.543 5.743)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="iRYWDfa" cx="0" cy="0" r="1" gradientTransform="rotate(-53.92 13.734 -12.444)scale(.59149 .49578)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="ilY03Dc" cx="0" cy="0" r="1" gradientTransform="matrix(.25955 -.68556 .916 .3468 15.753 6.06)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="ioXQVYb" cx="0" cy="0" r="1" gradientTransform="matrix(-.73324 0 0 -.81876 11.328 6.027)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="iBBmkUc" cx="0" cy="0" r="1" gradientTransform="matrix(-.40524 .06956 -.07132 -.4155 11.329 6.028)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><filter id="iL99E6d" width="23.977" height="13.398" x="5.341" y="16.362" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.729412 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22994"/></filter><filter id="ipFtHzU" width="20.681" height="10.082" x="5.434" y="20.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22994" stdDeviation=".75"/></filter><filter id="iDJlXac" width="24.344" height="8.644" x="1.332" y="21.127" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.415686 0 0 0 0 0.839216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22994"/></filter><filter id="i76sK2b" width="2.686" height="2.686" x="23.895" y="13.369" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22994"/></filter><filter id="iQ0MlHd" width="2.186" height="2.186" x="27.145" y="11.67" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22994"/></filter><filter id="iK8C5ie" width="1.928" height="1.928" x="25.27" y="9.713" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22994"/></filter><filter id="iE39Xuc" width="2.857" height="2.898" x="19.856" y="12.137" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22994"/></filter><filter id="iSl44qb" width="5.571" height="6.952" x="7.098" y="7.834" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.305882 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22994"/></filter><filter id="izgiHXd" width="14.97" height="18.152" x="7.751" y="7.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.521569 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22994"/></filter><filter id="iYrTV7V" width="17.737" height="14.8" x="12.903" y="15.851" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22994" stdDeviation="1"/></filter><filter id="ibrKzAe" width="6.506" height="14.75" x="13.897" y="7.41" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22994" stdDeviation=".375"/></filter><filter id="iic9BCc" width="5.506" height="5.421" x="17.315" y="7.485" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22994" stdDeviation=".3"/></filter><filter id="iYWZvKd" width="5.519" height="5.657" x="11.263" y="3.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".7"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22994"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22994" result="effect2_innerShadow_3987_22994"/></filter><filter id="i0XLkfc" width="2.772" height="3.282" x="12.053" y="4.778" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22994" stdDeviation=".5"/></filter><filter id="ig0PcOd" width=".93" height="1.382" x="13.037" y="5.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22994" stdDeviation=".025"/></filter><filter id="ir8HTVs" width="1.623" height=".674" x="12.69" y="7.17" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22994" stdDeviation=".025"/></filter><filter id="iE4Oglc" width="5.692" height="3.974" x="10.656" y="1.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22994"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22994" result="effect2_innerShadow_3987_22994"/></filter><filter id="iPBSgzc" width="1.09" height=".638" x="14.204" y="4.402" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22994"/></filter><filter id="ioqKSSd" width="1.09" height=".631" x="11.88" y="4.408" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22994"/></filter><filter id="iiiEG5d" width="2.94" height="2.608" x="10.824" y="2.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22994"/><feGaussianBlur result="effect2_foregroundBlur_3987_22994" stdDeviation=".05"/></filter><filter id="i6unNkd" width="2.801" height="2.561" x="13.464" y="2.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22994" stdDeviation=".075"/></filter><filter id="i7aPDvc" width=".459" height=".419" x="14.086" y="5.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22994" stdDeviation=".05"/></filter><filter id="iMIlO0c" width=".617" height=".627" x="14.402" y="5.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22994" stdDeviation=".1"/></filter><filter id="iqA7QFd" width=".659" height=".683" x="12.438" y="5.436" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22994" stdDeviation=".1"/></filter><filter id="iS7c8hj" width=".515" height=".423" x="12.159" y="5.483" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22994" stdDeviation=".05"/></filter><filter id="iR3n8te" width=".867" height="1.331" x="10.674" y="5.362" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22994" stdDeviation=".125"/></filter><filter id="i1HcLwl" width="1.419" height="1.842" x="15.188" y="5.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22994" stdDeviation=".25"/></filter><filter id="iAyatZS" width="2.065" height="1.066" x="14.022" y="3.012" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22994" stdDeviation=".1"/></filter><linearGradient id="i5BMVwc" x1="6.497" x2="16.059" y1="29.364" y2="29.364" gradientUnits="userSpaceOnUse"><stop class="e_8e_fe6a"/><stop offset="1" class="t2zfh_b3c"/></linearGradient><linearGradient id="iiC4tnd" x1="16.184" x2="16.091" y1="30.27" y2="28.645" gradientUnits="userSpaceOnUse"><stop offset=".178" class="oste98bcz"/><stop offset="1" class="ojj5yabro"/></linearGradient><linearGradient id="i3oGTgd" x1="20.497" x2="18.794" y1="21.926" y2="23.012" gradientUnits="userSpaceOnUse"><stop class="sgu3uubpp"/><stop offset="1" class="hpb-k7b_o"/></linearGradient><linearGradient id="i3DEP3c" x1="21.419" x2="22.653" y1="24.832" y2="26.114" gradientUnits="userSpaceOnUse"><stop class="jikp3gouc"/><stop offset="1" class="esa0tobpk"/></linearGradient><linearGradient id="iwWmMLd" x1="5.216" x2="25.059" y1="29.239" y2="22.332" gradientUnits="userSpaceOnUse"><stop class="d9q_ne9mx"/><stop offset="1" class="y110racyj"/></linearGradient><linearGradient id="iAWqJve" x1="15.101" x2="15.101" y1="7.606" y2="25.567" gradientUnits="userSpaceOnUse"><stop class="nmvycabwt"/><stop offset=".978" class="xujwu-wlk"/></linearGradient><linearGradient id="iTJLgWT" x1="21.653" x2="15.842" y1="11.925" y2="8.549" gradientUnits="userSpaceOnUse"><stop class="ku_swbhun"/><stop offset=".888" class="upowizugn"/></linearGradient><linearGradient id="il5WOtc" x1="17.15" x2="19.593" y1="8.16" y2="21.397" gradientUnits="userSpaceOnUse"><stop class="e95gaqibw"/><stop offset="1" class="mtqjbpbdp"/></linearGradient><linearGradient id="ipHtwtH" x1="21.762" x2="18.091" y1="11.879" y2="7.989" gradientUnits="userSpaceOnUse"><stop class="yjjppjb0c"/><stop offset="1" class="fvilr_bly"/></linearGradient><linearGradient id="i6eefNl" x1="15.782" x2="14.664" y1="6.887" y2="6.887" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="imfavAb" x1="13.872" x2="13.502" y1="6.44" y2="6.456" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="ic5lqHN" x1="13.502" x2="13.502" y1="6.944" y2="6.738" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="iFNMzKd" x1="13.502" x2="13.502" y1="5.748" y2="5.99" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="i6cSHcd" x1="12.97" x2="13.111" y1="7.639" y2="7.27" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="ibU4Y1D" x1="16.532" x2="11.397" y1="3.638" y2="3.638" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="ibQp6Nc" x1="14.811" x2="14.672" y1="5.761" y2="5.846" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i1t82Pc" x1="12.866" x2="12.727" y1="5.761" y2="5.846" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ie1NnIb" x1="16.348" x2="15.814" y1="5.773" y2="6.735" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="iO9aHDb" x1="10.915" x2="11.56" y1="6.084" y2="6.028" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="ii34VQj" x1="15.897" x2="15.897" y1="5.604" y2="6.445" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-surfing-medium-dark" /></template>
<style>
.ac-xhp72k {
  d: path("m15.807 5.103l-.013-.279a.65.65 0 0 0-.622-.63h-.619a1.07 1.07 0 0 1-.939-.557s.32-.915.844-.781c.37.095.766.238 1.078.441c.771.503.677 1.38.27 1.806");
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.aplp_ackh {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M11.993 4.776q.061-.038.17-.083c.145-.056.352-.106.6-.076a.123.123 0 1 1-.03.244a.98.98 0 0 0-.647.147l-.007.005l-.001.001a.123.123 0 0 1-.15-.194z");
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.b07bm3qgt {
  stop-color: var(--svg-color--64ddff, #64DDFF);
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bcvezxuef {
  d: path("M20.005 13.849c.256-.588.372-1.22.398-1.462l2.047.024c.047.268-.04.583-.078.703c.087.322.036.687 0 .829c-.055.225-.18.713-.238.86c-.075.183-.184.246-.348.23a.4.4 0 0 1-.149-.043a.3.3 0 0 0-.23-.018a.43.43 0 0 1-.227.018a.43.43 0 0 1-.203-.112a.22.22 0 0 0-.196-.06a.5.5 0 0 1-.226.004a.36.36 0 0 1-.172-.115a.22.22 0 0 0-.175-.07c-.084.007-.183.002-.235-.042c-.097-.082-.218-.175.032-.746");
}

.bhnh5qkwr {
  d: path("M14.439 5.61c.028.037-.031.083-.098.133s-.116.085-.144.047c-.028-.037.003-.108.07-.158s.144-.06.172-.023");
}

.bv25hsebv {
  stop-color: var(--svg-color--744543, #744543);
}

.bx_ajvbxr {
  d: path("M10.009 11.696c-.968.714-2.205 1.017-2.723 1.058c-.131 1 .107 1.771.242 2.032c.3-.028 1.149-.11 2.5-.72c1.68-.756 2.458-1.803 2.64-2.245l-.28-3.387c-.376 1.031-1.005 2.246-2.38 3.262");
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c2e0llb1c {
  stop-color: var(--svg-color--8f6c66, #8F6C66);
  stop-opacity: 0;
}

.c4gk4qbre {
  fill: var(--svg-color--4bc4fd, #4BC4FD);
  d: path("M19.075 29.748H5.341c3.432-1.326 10.768-4.346 12.656-5.818c2.36-1.84 2.937-3.291 4.11-4.976c1.171-1.685 2.062-2.293 3.921-2.036c1.692.235 3.164 1.575 3.29 4.04c0 4.593-2.74 6.555-4.165 7.51c-1.906 1.28-4.625 1.327-6.078 1.28");
}

.c7qpv738k {
  stop-color: var(--svg-color--362c2e, #362C2E);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.cbylncbjf {
  stop-color: var(--svg-color--332f31, #332F31);
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cr6tek86r {
  fill: var(--svg-color--825c4d, #825C4D);
  fill-rule: evenodd;
  d: path("M4.936 14.945a.375.375 0 0 1-.69-.296c.093-.216.327-.445.6-.604a1.76 1.76 0 0 1 1.118-.237a.375.375 0 1 1-.098.744a1 1 0 0 0-.642.14a1 1 0 0 0-.215.164a.5.5 0 0 0-.073.089");
}

.czuo201bw {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
  stop-opacity: 0;
}

.d0tatcb7l {
  stop-color: var(--svg-color--906e6a, #906E6A);
}

.d8d_cybzn {
  fill: var(--svg-color--ff702b, #FF702B);
  d: path("M10.009 11.696c-.968.714-2.205 1.017-2.723 1.058c-.131 1 .107 1.771.242 2.032c.3-.028 1.149-.11 2.5-.72c1.68-.756 2.458-1.803 2.64-2.245l-.28-3.387c-.376 1.031-1.005 2.246-2.38 3.262");
}

.d9q_ne9mx {
  stop-color: var(--svg-color--f54696, #F54696);
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dsgg-lbtf {
  fill: var(--svg-color--000, #000);
  d: path("M12.762 5.92c0-.125-.1-.225-.226-.225a.225.225 0 0 0-.2.33h.4a.2.2 0 0 0 .026-.104");
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e_8e_fe6a {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
}

.e-26k1bqp {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.559 5.406c.289 0 .533.199.599.468a.12.12 0 0 1-.118.15h-.987a.102.102 0 0 1-.1-.12a.62.62 0 0 1 .606-.498");
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e4t6-lb6y {
  stop-color: var(--svg-color--9a6e61, #9A6E61);
}

.e8ajgab-k {
  stop-color: var(--svg-color--392f31, #392F31);
}

.e95gaqibw {
  stop-color: var(--svg-color--ff965a, #FF965A);
}

.ecs-9379l {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
}

.efbqcfj9w {
  d: path("M12.536 5.526a.395.395 0 0 0-.38.499h.762a.397.397 0 0 0-.382-.499");
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.er0557b1s {
  stop-color: var(--svg-color--3eb9ff, #3EB9FF);
  stop-opacity: 0;
}

.esa0tobpk {
  stop-color: var(--svg-color--9157c5, #9157C5);
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.eylv4trdg {
  fill-rule: evenodd;
  d: path("M4.728 14.139s.02-.028.084-.08c.073-.059.179-.128.31-.193c.266-.13.609-.23.969-.218a.375.375 0 0 0 .023-.75a2.84 2.84 0 0 0-1.322.295c-.176.087-.33.185-.453.284c-.11.089-.234.211-.296.355a.375.375 0 0 0 .685.306");
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f4nse45rd {
  fill-rule: evenodd;
  d: path("M4.574 14.667q-.004.007-.002 0a.375.375 0 0 1-.689-.295c.055-.129.164-.253.27-.354c.116-.11.264-.225.437-.328a2.5 2.5 0 0 1 1.337-.37a.375.375 0 1 1-.024.75a1.73 1.73 0 0 0-.927.263a1.8 1.8 0 0 0-.307.23a1 1 0 0 0-.095.104");
}

.f7qmk1bul {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.502 7.423c-.225 0-.436-.053-.613-.145c-.06-.031-.125.037-.087.092a.84.84 0 0 0 .7.374c.294 0 .552-.15.7-.374c.038-.057-.027-.123-.088-.092a1.3 1.3 0 0 1-.612.145Z");
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fdd72shlv {
  stop-color: var(--svg-color--65e0ff, #65E0FF);
}

.fltjd-k8p {
  stop-color: var(--svg-color--ff4a2b, #FF4A2B);
  stop-opacity: 0;
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.ft5dv1b6b {
  fill: none;
}

.fu31k5bmq {
  stop-color: var(--svg-color--ff5714, #FF5714);
}

.fv0gs1r5b {
  stop-color: var(--svg-color--794853, #794853);
}

.fveku386v {
  fill-rule: evenodd;
  d: path("M6.451 13.544c-.941-.284-1.294.01-1.388.119a.375.375 0 1 1-.57-.488c.328-.383 1.014-.699 2.174-.35a.375.375 0 0 1-.216.719");
}

.fvilr_bly {
  stop-color: var(--svg-color--ff9e61, #FF9E61);
  stop-opacity: 0;
}

.ghsb7_-dv {
  stop-color: var(--svg-color--66b4dd, #66B4DD);
}

.gxf7b0v7y {
  stop-color: var(--svg-color--392f31, #392F31);
  stop-opacity: 0;
}

.h3fjnxbnc {
  width: 0.599px;
  height: 1.031px;
  x: 19.986px;
  y: 12.809px;
  rx: 0.299px;
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.hd_0eypmm {
  d: path("M11.368 7.365a1.73 1.73 0 0 0 1.718 1.506h.835c.87 0 1.604-.643 1.718-1.506c.052-.833.104-1.663.143-2.495a.64.64 0 0 0-.61-.634h-.619c-.422 0-.804-.249-.978-.638a.29.29 0 0 0-.272-.185h-.563c-.816 0-1.477.67-1.477 1.495c0 .822.051 1.632.105 2.457");
}

.hfpnvrbth {
  d: path("M14.819 5.869a.37.37 0 0 0-.102-.205l-.115.126l.052.101z");
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hjvcixbup {
  stop-color: var(--svg-color--7b3a46, #7B3A46);
}

.hlo9g_x7r {
  d: path("M15.688 6.445q.025-.42.048-.841a.422.422 0 0 1-.049.841");
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.holozbkuz {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
  stop-opacity: 0;
}

.hpb-k7b_o {
  stop-color: var(--svg-color--6b3f38, #6B3F38);
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i6xvtdb8e {
  stop-color: var(--svg-color--545051, #545051);
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.iejf4hbly {
  d: path("M16.106 13.45c-.65-1.28-1.166-3.185-1.442-4.423a.713.713 0 0 1 .587-.856c.448-.075.855.271.91.722c.205 1.698.95 3.373 1.445 4.682c.578 1.531.313 1.062.234 3.515c-.056 1.782 1.266 3.25 1.813 4.11l-.406.21c-.61-.827-2.203-2.945-2.203-4.85c0-1.792.062-1.141-.938-3.11");
}

.inzu6lb7s {
  stop-color: var(--svg-color--ff3e28, #FF3E28);
  stop-opacity: 0;
}

.iunk_4d6b {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.445 5.406a.62.62 0 0 0-.6.468c-.02.077.04.15.119.15h.986a.102.102 0 0 0 .1-.12a.62.62 0 0 0-.606-.498");
}

.izj80v7dd {
  d: path("m13.605 3.659l-.03-.06a.29.29 0 0 0-.272-.186h-.562c-.817 0-1.478.67-1.478 1.495v.121c-.15-.114-.34-.355-.34-.746c0-.474.346-.714.567-.866c.062-.043.114-.08.146-.112l.044-.047c.155-.164.43-.456.91-.583q.11-.03.216-.045c.468-.073.808.346.808.819v.204z");
}

.j_v8jdemw {
  stop-color: var(--svg-color--703d44, #703D44);
}

.ja57asbbp {
  d: path("M5.45 14.887c.125-.137.398-.46.52-.605c.23 0 .911-.067 1.199-.098c-.39.715-.84 1.004-1.075 1.195c-.316.211-.605 0-.644-.066c-.047-.047-.156-.254 0-.426");
}

.jg-b8c5-y {
  stop-color: var(--svg-color--794057, #794057);
}

.jgkh1vbol {
  stop-color: var(--svg-color--8a675b, #8A675B);
  stop-opacity: 0;
}

.jikp3gouc {
  stop-color: var(--svg-color--b041ab, #B041AB);
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.kf-sl5b6g {
  stop-color: var(--svg-color--67ecff, #67ECFF);
  stop-opacity: 0;
}

.ku_swbhun {
  stop-color: var(--svg-color--ff8444, #FF8444);
}

.kzew_oulk {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
}

.l1l492bnf {
  cx: 12.417px;
  cy: 5.695px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.172px;
  ry: 0.087px;
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhouptx_t {
  cx: 25.188px;
  cy: 14.762px;
  r: 1.293px;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lpxhpcbvx {
  fill-rule: evenodd;
  d: path("M4.936 14.945a.375.375 0 0 1-.69-.296c.093-.216.327-.445.6-.604a1.76 1.76 0 0 1 1.118-.237a.375.375 0 1 1-.098.744a1 1 0 0 0-.642.14a1 1 0 0 0-.215.164a.5.5 0 0 0-.073.089");
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.lvv_hcmig {
  stop-color: var(--svg-color--9eaef5, #9EAEF5);
  stop-opacity: 0;
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m3ok-p19m {
  stop-color: var(--svg-color--997a72, #997A72);
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mtqjbpbdp {
  stop-color: var(--svg-color--ff8064, #FF8064);
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.n_yk4s7wv {
  d: path("M11.271 5.318a.711.711 0 0 0 .057 1.417a35 35 0 0 1-.057-1.417");
}

.n-jrenige {
  stop-color: var(--svg-color--36b0fc, #36B0FC);
}

.n0_4eow9o {
  stop-color: var(--svg-color--ff875c, #FF875C);
  stop-opacity: 0;
}

.n3ivew17u {
  d: path("M12.083 11.653c-.431-1.716.17-3.162.508-3.485l2.343-.562h1.743c1.523 0 2.821.189 4.203 1.258c1.353 1.047 1.622 2.799 1.588 3.592a.05.05 0 0 1-.051.046l-1.988-.074a.052.052 0 0 1-.05-.058c.039-.371-.066-1.273-1-2.014c-.605-.481-1.519-.532-2.146-.494a.373.373 0 0 0-.323.498c.317.955.84 2.513 1.212 3.52c.547 1.484-.11 2.952.375 4.484c.377 1.191 1.204 2.418 1.637 2.92a.04.04 0 0 1-.014.063l-1.834.852a.04.04 0 0 1-.047-.01c-1.848-2.158-2.5-3.826-2.562-3.99c-.063-.164-.23-.53-.575-.53c-.275 0-.59.35-.808.73l-4.667 7.137a.05.05 0 0 1-.056.02l-1.783-.52a.05.05 0 0 1-.032-.068c1.498-3.164 4.54-9.51 4.772-10.057c.211-.5.181-.917.14-1.086c-.03-.13-.218-.711-.585-2.172");
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nb1sixbgm {
  cx: 26.184px;
  cy: 10.727px;
  r: 0.914px;
}

.nf0740e8o {
  stop-color: var(--svg-color--ff4a2b, #FF4A2B);
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.nmvycabwt {
  stop-color: var(--svg-color--ff7a3c, #FF7A3C);
}

.nz1yf2bug {
  stop-color: var(--svg-color--8f6c66, #8F6C66);
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of_rz239k {
  stop-color: var(--svg-color--9eaef5, #9EAEF5);
}

.ojj5yabro {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
  stop-opacity: 0;
}

.oste98bcz {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.p_kbfib2a {
  d: path("M15.678 6.735q.045-.705.082-1.411a.712.712 0 0 1-.082 1.411");
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pohq21btr {
  d: path("M15.648 3.205a1.048 1.048 0 0 1 .514 1.582a.7.7 0 0 0-.12.386V5.7a.8.8 0 0 0-.295-.12l.035-.71a.64.64 0 0 0-.61-.633h-.619c-.422 0-.804-.249-.978-.638a.29.29 0 0 0-.272-.185h-.563c-.816 0-1.477.67-1.477 1.495l.014.68a.8.8 0 0 0-.319.116v-.53a.7.7 0 0 0-.12-.387a1.06 1.06 0 0 1-.063-1.082c.13-.244.338-.415.575-.498c.253-.09.469-.26.612-.49a1.03 1.03 0 0 1 1.278-.404a.66.66 0 0 0 .528 0a1.03 1.03 0 0 1 1.283.417c.135.226.349.39.597.475");
}

.pss3eyexw {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M15.356 3.64h-.92a.213.213 0 1 1 .034-.426c.238.038.555.091.768.144c.48.119.612.353.65.52a.67.67 0 0 0-.532-.239");
}

.pu_jwmefu {
  d: path("M12.897 5.874c0-.127-.104-.212-.132-.238l-.128.123l.079.16z");
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.q7quaubxc {
  stop-color: var(--svg-color--67ecff, #67ECFF);
}

.qfyn005sz {
  stop-color: var(--svg-color--ff3e28, #FF3E28);
}

.qg0p67bet {
  stop-color: var(--svg-color--7196ff, #7196FF);
}

.qm0xijb6f {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M14.439 5.61c.028.037-.031.083-.098.133s-.116.085-.144.047c-.028-.037.003-.108.07-.158s.144-.06.172-.023");
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qswrskbcf {
  fill: var(--svg-color--825c4d, #825C4D);
  fill-rule: evenodd;
  d: path("M4.728 14.139s.02-.028.084-.08c.073-.059.179-.128.31-.193c.266-.13.609-.23.969-.218a.375.375 0 0 0 .023-.75a2.84 2.84 0 0 0-1.322.295c-.176.087-.33.185-.453.284c-.11.089-.234.211-.296.355a.375.375 0 0 0 .685.306");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.ri6ddsbqu {
  stop-color: var(--svg-color--906e6a, #906E6A);
  stop-opacity: 0;
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rn9fbxb5o {
  d: path("M25.81 24.332c.98-2.278.626-3.886.055-5.013c-.475-.936-.003-1.662 1.018-1.421c.737.174 1.363.694 1.54 1.431c.72 3.025-.314 6.182-3.582 7.816c-2.95 1.475-7.855 1.594-9.938 1.469c3 0 9.805-1.723 10.906-4.282");
}

.ro0d6lgcg {
  stop-color: var(--svg-color--66b4dd, #66B4DD);
  stop-opacity: 0;
}

.rtugrsb1s {
  d: path("M23.782 21.262L1.615 28.951a.421.421 0 0 0 .137.819H5.7c.487 0 .969-.099 1.156-.156c5.922-2.016 17.407-5.86 18.176-6.2c.443-.195.512-.378.605-.627v-.001c.094-.25.047-1.032-.5-1.454c-.437-.337-1.105-.184-1.355-.07");
}

.s41d30h-g {
  stop-color: var(--svg-color--fe5346, #FE5346);
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.s69jymf9k {
  fill: var(--svg-color--825c4d, #825C4D);
  d: path("M6.927 12.776h.594c-.107.669.012 1.608.113 1.996c-1.006.131-1.637-.108-1.856-.246l-.109-1.461c.331-.256.977-.3 1.258-.29");
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.sgu3uubpp {
  stop-color: var(--svg-color--967a70, #967A70);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.sqq33qb1e {
  fill: var(--svg-color--81584a, #81584A);
  d: path("m6.63 27.348l1.172-2.39l1.765.304v1.04z");
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.sxt3ddbys {
  d: path("M14.468 5.526a.395.395 0 0 1 .38.499h-.763a.396.396 0 0 1 .382-.499");
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.t2zfh_b3c {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
  stop-opacity: 0;
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.txy8o-b9p {
  d: path("M19.16 23.012a29 29 0 0 1-.905-.867l1.867-.883c.075.131.51.8.719 1.117z");
}

.u4co9oitl {
  fill: var(--svg-color--000, #000);
  d: path("M14.242 5.92a.225.225 0 1 1 .427.104h-.4a.2.2 0 0 1-.027-.103");
}

.u9r0afb_s {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m13.324 5.913l-.261.813c-.045.167.062.334.214.334h.324c.151 0 .258-.17.214-.334l-.219-.813c-.047-.18-.223-.18-.272 0");
}

.udjnzvwry {
  d: path("m21.31 27.333l-14.376 1.5c4.688-2.24 11.938-4.407 14.375-6.188c1.826-1.334 2.896-1.2 3.282.563c.218 1-1.032 3.625-3.282 4.125");
}

.ui2bqrbyd {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
  stop-opacity: 0;
}

.ukqtbzb_a {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m13.605 3.659l-.03-.06a.29.29 0 0 0-.272-.186h-.562c-.817 0-1.478.67-1.478 1.495v.121c-.15-.114-.34-.355-.34-.746c0-.474.346-.714.567-.866c.062-.043.114-.08.146-.112l.044-.047c.155-.164.43-.456.91-.583q.11-.03.216-.045c.468-.073.808.346.808.819v.204z");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.upowizugn {
  stop-color: var(--svg-color--ff783f, #FF783F);
}

.utzn9kn9q {
  d: path("M16.892 10.277a.37.37 0 0 1 .341-.415c.627-.038 1.54.013 2.147.494c.933.74 1.038 1.643 1 2.014a.05.05 0 0 0 .049.058l1.988.074a.05.05 0 0 0 .051-.046c.034-.793-.235-2.545-1.588-3.592c-1.382-1.07-2.68-1.258-4.203-1.258h-.39c-.158 1.285.25 2.193.605 2.671");
}

.v781osfkd {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M15.152 4.825a.8.8 0 0 0-.304-.182c-.134-.043-.303-.054-.536-.026a.123.123 0 1 0 .03.244c.213-.026.343-.013.433.016a.6.6 0 0 1 .216.132a.123.123 0 0 0 .161-.184");
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vc0stzb2b {
  d: path("M19.075 29.748H5.341c3.432-1.326 10.768-4.346 12.656-5.818c2.36-1.84 2.937-3.291 4.11-4.976c1.171-1.685 2.062-2.293 3.921-2.036c1.692.235 3.164 1.575 3.29 4.04c0 4.593-2.74 6.555-4.165 7.51c-1.906 1.28-4.625 1.327-6.078 1.28");
}

.vj0--9brr {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
}

.vsa9yt_zc {
  d: path("m6.63 27.348l1.172-2.39l1.765.304v1.04z");
}

.vtn8sbczo {
  d: path("M15.651 6.695a.73.73 0 0 0 .4-.137v.412a.96.96 0 0 1-.593.893a1.8 1.8 0 0 0 .153-.522z");
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w8g7f6hkf {
  cx: 12.417px;
  cy: 5.695px;
  rx: 0.172px;
  ry: 0.087px;
}

.waxuy09cc {
  d: path("M11.352 6.695a.73.73 0 0 1-.4-.137v.412a.96.96 0 0 0 .593.893a1.8 1.8 0 0 1-.153-.522z");
}

.wg7_ywkcx {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m13.333 5.826l-.235.813c-.048.167.067.334.23.334h.348c.163 0 .278-.17.23-.334l-.235-.813c-.05-.18-.286-.18-.338 0");
}

.wks9ssbug {
  fill: var(--svg-color--825c4d, #825C4D);
  fill-rule: evenodd;
  d: path("M6.451 13.544c-.941-.284-1.294.01-1.388.119a.375.375 0 1 1-.57-.488c.328-.383 1.014-.699 2.174-.35a.375.375 0 0 1-.216.719");
}

.woc0miqaj {
  stop-color: var(--svg-color--fe5346, #FE5346);
  stop-opacity: 0;
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.wvc2-1b2k {
  stop-color: var(--svg-color--8a675b, #8A675B);
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.xujwu-wlk {
  stop-color: var(--svg-color--ff4d30, #FF4D30);
}

.xwdp292ir {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M17.919 8.286c1.208-.021 3.781.828 4.104 4");
}

.xyr1brbaw {
  cx: 28.188px;
  cy: 12.813px;
  r: 1.043px;
}

.y110racyj {
  stop-color: var(--svg-color--84a6e9, #84A6E9);
}

.y4sbh5bmj {
  d: path("m22.793 25.327l-.421-1.143l-2.352.536l2.226 1.1a.396.396 0 0 0 .547-.493");
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.y7x-29baz {
  stop-color: var(--svg-color--794057, #794057);
  stop-opacity: 0;
}

.yfve034tb {
  d: path("M13.502 7.423c-.225 0-.436-.053-.613-.145c-.06-.031-.125.037-.087.092a.84.84 0 0 0 .7.374c.294 0 .552-.15.7-.374c.038-.057-.027-.123-.088-.092a1.3 1.3 0 0 1-.612.145");
}

.yjjppjb0c {
  stop-color: var(--svg-color--ff9e61, #FF9E61);
}

.yt5sdf2gy {
  stop-color: var(--svg-color--ff875c, #FF875C);
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.z3n_enlzo {
  d: path("M11.253 5.612a.423.423 0 0 0 .037.831a35 35 0 0 1-.037-.83");
}

.z8g0bbbjy {
  d: path("m13.333 5.826l-.235.813c-.048.167.067.334.23.334h.348c.163 0 .278-.17.23-.334l-.235-.813c-.05-.18-.286-.18-.338 0");
}

.z9uidyb6w {
  fill: var(--svg-color--815b52, #815B52);
  d: path("M5.45 14.887c.125-.137.398-.46.52-.605c.23 0 .911-.067 1.199-.098c-.39.715-.84 1.004-1.075 1.195c-.316.211-.605 0-.644-.066c-.047-.047-.156-.254 0-.426");
}

.zj7dribao {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m15.807 5.103l-.013-.279a.65.65 0 0 0-.622-.63h-.619a1.07 1.07 0 0 1-.939-.557s.32-.915.844-.781c.37.095.766.238 1.078.441c.771.503.677 1.38.27 1.806");
}

.zkqd2ycat {
  stop-color: var(--svg-color--ff5714, #FF5714);
  stop-opacity: 0;
}

.zl6_f2bcr {
  fill: var(--svg-color--825c4d, #825C4D);
  fill-rule: evenodd;
  d: path("M4.574 14.667q-.004.007-.002 0a.375.375 0 0 1-.689-.295c.055-.129.164-.253.27-.354c.116-.11.264-.225.437-.328a2.5 2.5 0 0 1 1.337-.37a.375.375 0 1 1-.024.75a1.73 1.73 0 0 0-.927.263a1.8 1.8 0 0 0-.307.23a1 1 0 0 0-.095.104");
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

.ztof03btl {
  fill: var(--svg-color--1b71cc, #1B71CC);
  d: path("m21.31 27.333l-14.376 1.5c4.688-2.24 11.938-4.407 14.375-6.188c1.826-1.334 2.896-1.2 3.282.563c.218 1-1.032 3.625-3.282 4.125");
}

</style>
