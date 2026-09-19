<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#it724Gx)"><path class="jhlh1_3ek"/><path fill="url(#ijJnbEe)" class="vb809lo-e"/></g><path fill="url(#i6qhIMe)" class="vb809lo-e"/><path fill="url(#iMX3qoe)" class="vb809lo-e"/><path fill="url(#iojSsLc)" class="vb809lo-e"/><path fill="url(#ioT8ldb)" class="vb809lo-e"/><g filter="url(#ily5f1b)"><path class="siw2d1f7p"/><path fill="url(#izT5PGd)" class="i9-uutisp"/></g><path class="j83otbcan"/><path fill="url(#iI08NNb)" class="xtp47zbsj"/><path fill="url(#iPHWNcc)" class="u--ocwryb"/><path fill="url(#iJ67Gde)" class="sazwi3bdn"/><path fill="url(#il6NAWb)" class="sazwi3bdn"/><g filter="url(#iMHmyBc)"><path fill="url(#inumkee)" class="qnmjgylyq"/><path fill="url(#ihJgNrc)" class="qnmjgylyq"/></g><g filter="url(#iTxSkBe)"><circle fill="url(#iAisVdc)" class="s2ikxxbfc"/></g><g filter="url(#inCEwhy)"><circle fill="url(#iuX5Neb)" class="qv62lactv"/></g><g filter="url(#iWZZHQP)"><circle fill="url(#i9dRGae)" class="ae99og76i"/></g><rect fill="url(#ibU9Xsd)" transform="rotate(26.595 20.662 12.797)" class="i34rybopj"/><g filter="url(#iEsxjxH)"><path fill="url(#iNk77vd)" class="pekg0u7cp"/></g><path class="i5vej436q"/><g filter="url(#i7GMw2d)"><path class="drevzvb2z"/><path fill="url(#iTZSY5Q)" class="frgrxi9fy"/><path fill="url(#iUgFvud)" class="frgrxi9fy"/></g><g filter="url(#iTvOmyb)"><path fill="url(#i792cHc)" class="gwjr899hs"/><path fill="url(#iM7HHze)" class="gwjr899hs"/><path fill="url(#iADJpWd)" class="gwjr899hs"/></g><path fill="url(#iRsy8Zd)" class="xt887yc-y"/><path fill="url(#iIYpcRf)" class="xt887yc-y"/><path clip-rule="evenodd" class="wfnn4zbei"/><path fill="url(#imb9vQe)" clip-rule="evenodd" class="l89w7ttua"/><path clip-rule="evenodd" class="kp-2efbsj"/><path fill="url(#ibuw9Iv)" clip-rule="evenodd" class="x2d1t4xtf"/><path clip-rule="evenodd" class="o2riu6e9b"/><path fill="url(#igZGKic)" clip-rule="evenodd" class="ljni-v35c"/><path clip-rule="evenodd" class="herbgz03w"/><path fill="url(#ilme1mb)" clip-rule="evenodd" class="wc05b2bod"/><path class="ooocs2okn"/><path fill="url(#ihCsk4d)" class="uu4f6-byw"/><g filter="url(#i0OAvie)"><path fill="url(#iqofZec)" class="so3eyo06u"/></g><g filter="url(#if50Qdb)"><path fill="url(#iBybyQb)" class="olg-72bto"/></g><g filter="url(#inXJ5tb)"><path stroke="url(#iNeOQ4F)" class="on9u00bey"/></g><path fill="url(#iYq1Gcb)" class="b5nd2m-sq"/><path fill="url(#iAPtvjw)" class="a4fvj8bnp"/><g filter="url(#i864QSb)"><path fill="url(#i56to9c)" class="wnm4h6zib"/></g><path fill="url(#i1Lw7xe)" class="wnm4h6zib"/><path fill="url(#igWowov)" class="wnm4h6zib"/><path fill="url(#iL0Y6sd)" class="wnm4h6zib"/><path fill="url(#ik6w2ve)" class="wnm4h6zib"/><path fill="url(#ipcOdGc)" class="wnm4h6zib"/><path fill="url(#iGfZ69b)" class="wnm4h6zib"/><path fill="url(#ixi7Lze)" class="wnm4h6zib"/><path fill="url(#iFUqEAc)" class="wnm4h6zib"/><path fill="url(#iNCSTVd)" class="wnm4h6zib"/><g filter="url(#ik6Hipd)"><path class="nzwbzmrxs"/></g><g filter="url(#i2heNbe)"><path class="pq8pgob9x"/><path fill="url(#irfV2xL)" class="or_7yib9u"/><path fill="url(#ivzw86d)" class="or_7yib9u"/><path fill="url(#iOe3Cve)" class="or_7yib9u"/><path fill="url(#iWV919d)" class="or_7yib9u"/><path fill="url(#ijuCjNe)" class="or_7yib9u"/></g><g filter="url(#imJOqUc)"><path stroke="url(#iQxOEmc)" class="c9oouybqp"/></g><path fill="url(#i91X2vb)" class="f30_2gbsx"/><g filter="url(#iWHPWsi)"><path fill="url(#iRaPisi)" class="bg90e8h8i"/><path fill="url(#ipvd6eb)" class="bg90e8h8i"/><path fill="url(#isk1pwd)" class="bg90e8h8i"/><path fill="url(#iaAeebb)" class="bg90e8h8i"/><path fill="url(#idSVMtd)" class="bg90e8h8i"/></g><g filter="url(#iyfgkXI)"><path class="xpbvfbwgb"/></g><g filter="url(#isH94SP)"><path class="vf1wvpb0u"/></g><g filter="url(#iHD47Pd)"><path class="zdcmpbb4s"/><path fill="url(#iHAZlae)" class="yqqphg97p"/><path fill="url(#i0cAHbc)" class="yqqphg97p"/></g><g filter="url(#iyZJl0b)"><path class="ici3-z1na"/><path fill="url(#ivp53Qd)" class="vsfbr_bbt"/></g><path class="rw5mc4bto"/><path fill="url(#iqZvc2c)" class="m27i__bjt"/><path class="azfgivboh"/><g filter="url(#i2CTebe)"><path class="um5zdnbvm"/><path fill="url(#ibYD8Ke)" class="msha2ob6c"/></g><g filter="url(#ivzeSAd)"><path fill="url(#ib3Apmi)" class="tkg6kfb1c"/></g><path class="k-l9f-bpq"/><path fill="url(#iYpgiFc)" class="nlgpmqbhl"/><path class="s6k9w6bfo"/><g filter="url(#iNpdFBc)"><path fill="url(#iPOAz6c)" class="e847_w9hd"/></g><g filter="url(#iaGVcte)"><ellipse transform="rotate(-27.914 13.095 5.707)" class="j5xpxuvyt"/><ellipse fill="url(#i7uZPkb)" transform="rotate(-27.914 13.095 5.707)" class="dnlo8zm8l"/></g><path fill="url(#iMapDzC)" class="gzlr_0cpw"/><path fill="url(#imZLVbd)" class="gzlr_0cpw"/><path fill="url(#i3A1Pne)" class="gzlr_0cpw"/><path fill="url(#idgJACd)" class="gzlr_0cpw"/><path fill="url(#iC5RrlV)" class="b2f11iceb"/><path fill="url(#iP95Thd)" class="b2f11iceb"/><g filter="url(#iGEMa0b)"><path fill="url(#iQgjJ5b)" class="k3be01b8g"/></g><g filter="url(#izM7kAc)"><path fill="url(#iwtMubD)" class="f70-asboo"/></g><g filter="url(#iAb259b)"><path class="uncbc3bjy"/></g><defs><radialGradient id="i6qhIMe" cx="0" cy="0" r="1" gradientTransform="matrix(3.84373 7.81251 -11.27829 5.54887 20.985 21.758)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="er0557b1s"/><stop offset=".913" class="qg0p67bet"/></radialGradient><radialGradient id="iojSsLc" cx="0" cy="0" r="1" gradientTransform="matrix(3.56253 -6.12498 3.8162 2.21965 22.203 21.914)" gradientUnits="userSpaceOnUse"><stop class="vj0--9brr"/><stop offset="1" class="holozbkuz"/></radialGradient><radialGradient id="ioT8ldb" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 -12.12496 23.16436 4.11944 23.61 28.758)" gradientUnits="userSpaceOnUse"><stop offset=".931" class="ro0d6lgcg"/><stop offset="1" class="ghsb7_-dv"/></radialGradient><radialGradient id="izT5PGd" cx="0" cy="0" r="1" gradientTransform="matrix(1.09706 3.375 -16.62038 5.40254 16.17 25.196)" gradientUnits="userSpaceOnUse"><stop offset=".716" class="czuo201bw"/><stop offset="1" class="ecs-9379l"/></radialGradient><radialGradient id="iI08NNb" cx="0" cy="0" r="1" gradientTransform="matrix(-.83721 2.51163 -.64638 -.21546 9.761 25.128)" gradientUnits="userSpaceOnUse"><stop class="ub7ea32uh"/><stop offset="1" class="w7mkf5ikd"/></radialGradient><radialGradient id="il6NAWb" cx="0" cy="0" r="1" gradientTransform="matrix(-.73437 -1.28906 .42946 -.24466 23.579 25.46)" gradientUnits="userSpaceOnUse"><stop class="kzew_oulk"/><stop offset="1" class="ui2bqrbyd"/></radialGradient><radialGradient id="ihJgNrc" cx="0" cy="0" r="1" gradientTransform="rotate(-110.045 20.738 2.812)scale(2.46162 1.62421)" gradientUnits="userSpaceOnUse"><stop class="of_rz239k"/><stop offset="1" class="lvv_hcmig"/></radialGradient><radialGradient id="iAisVdc" cx="0" cy="0" r="1" gradientTransform="rotate(146.686 11.217 11.132)scale(2.36974 1.91739)" gradientUnits="userSpaceOnUse"><stop offset=".171" class="b07bm3qgt"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="iuX5Neb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.47607 .92253 -.74644 -1.19432 29.42 12.544)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="i9dRGae" cx="0" cy="0" r="1" gradientTransform="rotate(147.995 12.17 9.166)scale(1.52552 1.23432)" gradientUnits="userSpaceOnUse"><stop class="fdd72shlv"/><stop offset="1" class="n-jrenige"/></radialGradient><radialGradient id="ibU9Xsd" cx="0" cy="0" r="1" gradientTransform="matrix(-.06342 .73199 -.55995 -.04852 21.024 13.096)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="vgekv3bdy"/><stop offset="1" class="r95brsblk"/></radialGradient><radialGradient id="iNk77vd" cx="0" cy="0" r="1" gradientTransform="rotate(139.295 9.201 10.919)scale(2.80315 2.75944)" gradientUnits="userSpaceOnUse"><stop class="nbncwobqn"/><stop offset="1" class="na5vpgbch"/></radialGradient><radialGradient id="iTZSY5Q" cx="0" cy="0" r="1" gradientTransform="rotate(142.524 4.928 6.711)scale(4.72526 1.21438)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="yt5sdf2gy"/><stop offset="1" class="n0_4eow9o"/></radialGradient><radialGradient id="iUgFvud" cx="0" cy="0" r="1" gradientTransform="rotate(103.462 2.34 10.547)scale(4.16121 1.35388)" gradientUnits="userSpaceOnUse"><stop class="nf0740e8o"/><stop offset="1" class="fltjd-k8p"/></radialGradient><radialGradient id="iM7HHze" cx="0" cy="0" r="1" gradientTransform="matrix(4.2188 -6.78122 .53719 .3342 11.329 24.414)" gradientUnits="userSpaceOnUse"><stop class="qfyn005sz"/><stop offset="1" class="inzu6lb7s"/></radialGradient><radialGradient id="iADJpWd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.09375 -2.46875 0 13.766 8.227)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="fu31k5bmq"/><stop offset="1" class="zkqd2ycat"/></radialGradient><radialGradient id="iIYpcRf" cx="0" cy="0" r="1" gradientTransform="rotate(24.436 -15.497 48.342)scale(3.39814 2.30082)" gradientUnits="userSpaceOnUse"><stop offset=".317" class="s41d30h-g"/><stop offset="1" class="woc0miqaj"/></radialGradient><radialGradient id="imb9vQe" cx="0" cy="0" r="1" gradientTransform="rotate(-164.074 4.362 6.434)scale(1.78035 1.88131)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="kn6afsb3f"/><stop offset=".98" class="t7r9i6b3f"/></radialGradient><radialGradient id="ibuw9Iv" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6671 -.63637 .8491 -2.2244 6.355 14.392)" gradientUnits="userSpaceOnUse"><stop offset=".74" class="kn6afsb3f"/><stop offset=".98" class="t7r9i6b3f"/></radialGradient><radialGradient id="igZGKic" cx="0" cy="0" r="1" gradientTransform="matrix(-1.6486 -.68743 .9779 -2.34523 6.177 14.934)" gradientUnits="userSpaceOnUse"><stop offset=".706" class="kn6afsb3f"/><stop offset=".922" class="t7r9i6b3f"/></radialGradient><radialGradient id="ilme1mb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.40308 -.60156 .87252 -2.03506 6.294 15.205)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="kn6afsb3f"/><stop offset=".98" class="t7r9i6b3f"/></radialGradient><radialGradient id="ihCsk4d" cx="0" cy="0" r="1" gradientTransform="matrix(.14063 .15625 -.6598 .59382 7.037 14.768)" gradientUnits="userSpaceOnUse"><stop class="bu3azkbir"/><stop offset="1" class="zga9nrbjv"/></radialGradient><radialGradient id="iqofZec" cx="0" cy="0" r="1" gradientTransform="rotate(135 10.51 15.396)scale(15.9541 20.2938)" gradientUnits="userSpaceOnUse"><stop class="q7quaubxc"/><stop offset="1" class="kf-sl5b6g"/></radialGradient><radialGradient id="iYq1Gcb" cx="0" cy="0" r="1" gradientTransform="matrix(.33109 .89299 -1.0608 .3933 16.281 6.57)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="iAPtvjw" cx="0" cy="0" r="1" gradientTransform="matrix(.65285 .20518 -.633 2.01409 11.502 6.787)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="i56to9c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31162 0 0 -4.08923 15.42 6.154)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="igWowov" cx="0" cy="0" r="1" gradientTransform="matrix(-.45202 5.49334 -4.54915 -.37433 14.88 3.539)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset=".997" class="h1qder98v"/></radialGradient><radialGradient id="iL0Y6sd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.50777 .62837 0 15.261 5.574)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="ik6w2ve" cx="0" cy="0" r="1" gradientTransform="matrix(.00174 -.48386 .52656 .0019 13.162 5.594)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="ipcOdGc" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 7.745 3.543)scale(3.76418 9.61559)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="iGfZ69b" cx="0" cy="0" r="1" gradientTransform="matrix(1.80097 -1.171 .42867 .65928 11.762 4.242)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="ixi7Lze" cx="0" cy="0" r="1" gradientTransform="matrix(-.10376 1.1043 -.44144 -.04148 16.63 4.865)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="iFUqEAc" cx="0" cy="0" r="1" gradientTransform="matrix(-.77078 1.27477 -1.05243 -.63634 15.253 3.953)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="ivzw86d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .10794 -.33923 0 14.386 6.756)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="iWV919d" cx="0" cy="0" r="1" gradientTransform="rotate(155.369 6.508 4.828)scale(.73994 1.18914)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="i91X2vb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.3187 1.28217 0 14.18 7.72)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="ipvd6eb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.54819 3.9152 0 11.867 4.875)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="isk1pwd" cx="0" cy="0" r="1" gradientTransform="matrix(.05043 -1.11098 1.96844 .08935 16.328 5.454)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iaAeebb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04301 -.68599 .50355 -.76562 15.995 2.68)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="idSVMtd" cx="0" cy="0" r="1" gradientTransform="matrix(.40022 .6522 -1.5102 .92671 13.78 1.975)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="iHAZlae" cx="0" cy="0" r="1" gradientTransform="matrix(-.97328 0 0 -.36122 14.291 2.974)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="i0cAHbc" cx="0" cy="0" r="1" gradientTransform="matrix(1.42299 -2.25307 2.49617 1.57653 11.778 4.718)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="ivp53Qd" cx="0" cy="0" r="1" gradientTransform="rotate(6.667 -26.93 130.364)scale(1.44605 .60543)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iqZvc2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35874 -.57062 0 15.144 5.749)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="ibYD8Ke" cx="0" cy="0" r="1" gradientTransform="matrix(-.10255 -.13215 .18193 -.14118 15.043 5.786)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iYpgiFc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35876 -.57065 0 13.214 5.749)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i7uZPkb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00342 -.21847 .26261 -.00411 13.088 5.846)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="imZLVbd" cx="0" cy="0" r="1" gradientTransform="matrix(.27792 .99192 -.94637 .26516 16.221 5.755)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="i3A1Pne" cx="0" cy="0" r="1" gradientTransform="matrix(.34834 -.47804 .40069 .29198 16.38 5.996)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="idgJACd" cx="0" cy="0" r="1" gradientTransform="matrix(.25955 -.68556 .916 .3468 16.43 6.072)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="iP95Thd" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 3.534 7.778)scale(.93594 .92012)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="iQgjJ5b" cx="0" cy="0" r="1" gradientTransform="matrix(-.40524 .06956 -.03068 -.17874 12.007 6.039)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><filter id="it724Gx" width="23.977" height="13.398" x="6.016" y="16.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.729412 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22991"/></filter><filter id="ily5f1b" width="20.681" height="10.082" x="6.11" y="20.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22991" stdDeviation=".75"/></filter><filter id="iMHmyBc" width="24.344" height="8.644" x="2.007" y="21.114" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.415686 0 0 0 0 0.839216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22991"/></filter><filter id="iTxSkBe" width="2.686" height="2.686" x="24.571" y="13.357" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22991"/></filter><filter id="inCEwhy" width="2.186" height="2.186" x="27.821" y="11.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22991"/></filter><filter id="iWZZHQP" width="1.928" height="1.928" x="25.946" y="9.701" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".225"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.619608 0 0 0 0 0.952941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22991"/></filter><filter id="iEsxjxH" width="2.857" height="2.898" x="20.532" y="12.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.14902 0 0 0 0 0.133333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22991"/></filter><filter id="i7GMw2d" width="5.571" height="6.952" x="7.773" y="7.822" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.976471 0 0 0 0 0.305882 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22991"/></filter><filter id="iTvOmyb" width="14.97" height="18.152" x="8.427" y="7.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.521569 0 0 0 0 0.415686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22991"/></filter><filter id="i0OAvie" width="17.737" height="14.8" x="13.579" y="15.839" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22991" stdDeviation="1"/></filter><filter id="if50Qdb" width="6.506" height="14.75" x="14.572" y="7.398" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22991" stdDeviation=".375"/></filter><filter id="inXJ5tb" width="5.506" height="5.421" x="17.991" y="7.473" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22991" stdDeviation=".3"/></filter><filter id="i864QSb" width="5.519" height="5.657" x="11.941" y="3.426" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22991"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22991" result="effect2_innerShadow_3987_22991"/></filter><filter id="ik6Hipd" width="2.772" height="3.282" x="12.731" y="4.79" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22991" stdDeviation=".5"/></filter><filter id="i2heNbe" width="1.03" height="1.482" x="13.664" y="5.603" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22991" stdDeviation=".05"/></filter><filter id="imJOqUc" width="1.923" height=".975" x="13.218" y="7.032" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22991" stdDeviation=".05"/></filter><filter id="iWHPWsi" width="5.692" height="3.974" x="11.333" y="1.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22991"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_22991" result="effect2_innerShadow_3987_22991"/></filter><filter id="iyfgkXI" width="1.09" height=".638" x="14.882" y="4.414" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22991"/></filter><filter id="isH94SP" width="1.09" height=".631" x="12.558" y="4.42" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22991"/></filter><filter id="iHD47Pd" width="3.24" height="2.758" x="11.451" y="2.484" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22991"/><feGaussianBlur result="effect2_foregroundBlur_3987_22991" stdDeviation=".075"/></filter><filter id="iyZJl0b" width="2.92" height="2.677" x="14.092" y="2.638" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.305882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_22991"/><feGaussianBlur result="effect2_foregroundBlur_3987_22991" stdDeviation=".1"/></filter><filter id="i2CTebe" width=".459" height=".419" x="14.764" y="5.499" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22991" stdDeviation=".05"/></filter><filter id="ivzeSAd" width=".617" height=".627" x="15.079" y="5.476" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22991" stdDeviation=".1"/></filter><filter id="iNpdFBc" width=".659" height=".683" x="13.115" y="5.448" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22991" stdDeviation=".1"/></filter><filter id="iaGVcte" width=".515" height=".423" x="12.837" y="5.495" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22991" stdDeviation=".05"/></filter><filter id="iGEMa0b" width=".867" height="1.331" x="11.351" y="5.374" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22991" stdDeviation=".125"/></filter><filter id="izM7kAc" width="1.419" height="1.842" x="15.865" y="5.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22991" stdDeviation=".25"/></filter><filter id="iAb259b" width="2.165" height="1.166" x="14.65" y="3.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_22991" stdDeviation=".125"/></filter><linearGradient id="ijJnbEe" x1="7.172" x2="16.735" y1="29.352" y2="29.352" gradientUnits="userSpaceOnUse"><stop class="e_8e_fe6a"/><stop offset="1" class="t2zfh_b3c"/></linearGradient><linearGradient id="iMX3qoe" x1="16.86" x2="16.766" y1="30.258" y2="28.633" gradientUnits="userSpaceOnUse"><stop offset=".178" class="oste98bcz"/><stop offset="1" class="ojj5yabro"/></linearGradient><linearGradient id="iPHWNcc" x1="21.172" x2="19.469" y1="21.914" y2="23" gradientUnits="userSpaceOnUse"><stop class="l20_z6baj"/><stop offset="1" class="spcerobbw"/></linearGradient><linearGradient id="iJ67Gde" x1="22.095" x2="23.329" y1="24.82" y2="26.102" gradientUnits="userSpaceOnUse"><stop class="jikp3gouc"/><stop offset="1" class="esa0tobpk"/></linearGradient><linearGradient id="inumkee" x1="5.891" x2="25.735" y1="29.227" y2="22.32" gradientUnits="userSpaceOnUse"><stop class="d9q_ne9mx"/><stop offset="1" class="y110racyj"/></linearGradient><linearGradient id="i792cHc" x1="15.777" x2="15.777" y1="7.594" y2="25.555" gradientUnits="userSpaceOnUse"><stop class="nmvycabwt"/><stop offset=".978" class="xujwu-wlk"/></linearGradient><linearGradient id="iRsy8Zd" x1="22.329" x2="16.517" y1="11.912" y2="8.537" gradientUnits="userSpaceOnUse"><stop class="ku_swbhun"/><stop offset=".888" class="upowizugn"/></linearGradient><linearGradient id="iBybyQb" x1="17.826" x2="20.269" y1="8.148" y2="21.384" gradientUnits="userSpaceOnUse"><stop class="e95gaqibw"/><stop offset="1" class="mtqjbpbdp"/></linearGradient><linearGradient id="iNeOQ4F" x1="22.438" x2="18.766" y1="11.867" y2="7.977" gradientUnits="userSpaceOnUse"><stop class="yjjppjb0c"/><stop offset="1" class="fvilr_bly"/></linearGradient><linearGradient id="i1Lw7xe" x1="16.46" x2="14.535" y1="6.899" y2="6.899" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="iNCSTVd" x1="14.2" x2="14.2" y1="8.919" y2="8.635" gradientUnits="userSpaceOnUse"><stop class="dn2_hckup"/><stop offset="1" class="jk-0m6p0q"/></linearGradient><linearGradient id="irfV2xL" x1="14.55" x2="14.179" y1="6.453" y2="6.468" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="iOe3Cve" x1="14.179" x2="14.179" y1="6.956" y2="6.751" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="ijuCjNe" x1="14.179" x2="14.179" y1="5.65" y2="6.002" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="iQxOEmc" x1="13.648" x2="13.789" y1="7.651" y2="7.282" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="iRaPisi" x1="17.209" x2="12.075" y1="3.65" y2="3.65" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="ib3Apmi" x1="15.488" x2="15.35" y1="5.773" y2="5.858" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iPOAz6c" x1="13.544" x2="13.405" y1="5.773" y2="5.858" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iMapDzC" x1="17.025" x2="16.492" y1="5.785" y2="6.747" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="iC5RrlV" x1="11.593" x2="12.238" y1="6.096" y2="6.04" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="iwtMubD" x1="16.574" x2="16.574" y1="5.616" y2="6.458" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-surfing-dark" /></template>
<style>
.a4fvj8bnp {
  d: path("M12.03 6.707a.73.73 0 0 1-.4-.137v.412a.96.96 0 0 0 .593.893a1.8 1.8 0 0 1-.153-.522z");
}

.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.ae99og76i {
  cx: 26.86px;
  cy: 10.715px;
  r: 0.914px;
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
  stop-opacity: 0;
}

.azfgivboh {
  fill: var(--svg-color--000, #000);
  d: path("M14.92 5.933a.225.225 0 1 1 .427.104h-.401a.2.2 0 0 1-.027-.104");
}

.b07bm3qgt {
  stop-color: var(--svg-color--64ddff, #64DDFF);
}

.b2f11iceb {
  d: path("M11.945 5.332a.712.712 0 0 0 .06 1.415a35 35 0 0 1-.06-1.415");
}

.b5nd2m-sq {
  d: path("M16.329 6.707a.73.73 0 0 0 .4-.137v.412a.96.96 0 0 1-.593.893q.113-.24.153-.522z");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bg90e8h8i {
  d: path("M16.326 3.217a1.048 1.048 0 0 1 .514 1.582a.7.7 0 0 0-.12.386v.526a.8.8 0 0 0-.295-.119l.035-.71a.64.64 0 0 0-.61-.633h-.62c-.421 0-.804-.25-.977-.638a.29.29 0 0 0-.272-.185h-.563c-.816 0-1.477.668-1.477 1.494l.013.68a.8.8 0 0 0-.318.116v-.53a.7.7 0 0 0-.12-.387a1.06 1.06 0 0 1-.063-1.082c.129-.244.337-.415.574-.498c.254-.09.47-.26.612-.49a1.03 1.03 0 0 1 1.279-.404a.66.66 0 0 0 .527 0a1.03 1.03 0 0 1 1.283.417c.136.226.35.39.598.475");
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.bu3azkbir {
  stop-color: var(--svg-color--61504f, #61504F);
}

.c2_7179_n {
  stop-color: var(--svg-color--432742, #432742);
  stop-opacity: 0;
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c5e-i-5dw {
  stop-color: var(--svg-color--361c1e, #361C1E);
  stop-opacity: 0;
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.c9oouybqp {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M13.602 7.223H13.6a.14.14 0 0 0-.17.03a.136.136 0 0 0-.014.171a.91.91 0 0 0 .762.407c.32 0 .601-.163.763-.407l-.062-.042l.062.042a.136.136 0 0 0-.015-.173a.14.14 0 0 0-.169-.028a1.25 1.25 0 0 1-.579.137c-.212 0-.411-.05-.578-.137Z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.czuo201bw {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
  stop-opacity: 0;
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.d9q_ne9mx {
  stop-color: var(--svg-color--f54696, #F54696);
}

.dn2_hckup {
  stop-color: var(--svg-color--49201f, #49201F);
}

.dnlo8zm8l {
  cx: 13.095px;
  cy: 5.707px;
  rx: 0.172px;
  ry: 0.087px;
}

.drevzvb2z {
  fill: var(--svg-color--ff702b, #FF702B);
  d: path("M10.684 11.684c-.967.714-2.204 1.017-2.723 1.058c-.13 1 .107 1.771.243 2.031c.3-.027 1.148-.109 2.5-.718c1.679-.757 2.458-1.804 2.64-2.246l-.28-3.387c-.376 1.031-1.005 2.246-2.38 3.262");
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.e_8e_fe6a {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e847_w9hd {
  d: path("M13.574 5.886c0-.127-.103-.212-.131-.238l-.128.124l.079.16z");
}

.e95gaqibw {
  stop-color: var(--svg-color--ff965a, #FF965A);
}

.ecs-9379l {
  stop-color: var(--svg-color--37a9ff, #37A9FF);
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.er0557b1s {
  stop-color: var(--svg-color--3eb9ff, #3EB9FF);
  stop-opacity: 0;
}

.esa0tobpk {
  stop-color: var(--svg-color--9157c5, #9157C5);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.f30_2gbsx {
  d: path("M14.18 7.435c-.225 0-.436-.053-.613-.145c-.06-.031-.126.037-.088.092a.84.84 0 0 0 .7.374c.294 0 .552-.15.7-.374c.039-.057-.026-.123-.087-.092a1.3 1.3 0 0 1-.613.145");
}

.f70-asboo {
  d: path("M16.365 6.458q.026-.421.049-.842a.422.422 0 0 1-.049.842");
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fdd72shlv {
  stop-color: var(--svg-color--65e0ff, #65E0FF);
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.fltjd-k8p {
  stop-color: var(--svg-color--ff4a2b, #FF4A2B);
  stop-opacity: 0;
}

.frgrxi9fy {
  d: path("M10.684 11.684c-.967.714-2.204 1.017-2.723 1.058c-.13 1 .107 1.771.243 2.031c.3-.027 1.148-.109 2.5-.718c1.679-.757 2.458-1.804 2.64-2.246l-.28-3.387c-.376 1.031-1.005 2.246-2.38 3.262");
}

.ft5dv1b6b {
  fill: none;
}

.fu31k5bmq {
  stop-color: var(--svg-color--ff5714, #FF5714);
}

.fvilr_bly {
  stop-color: var(--svg-color--ff9e61, #FF9E61);
  stop-opacity: 0;
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.ghsb7_-dv {
  stop-color: var(--svg-color--66b4dd, #66B4DD);
}

.gwjr899hs {
  d: path("M12.759 11.64c-.432-1.715.169-3.16.507-3.484l2.344-.562h1.742c1.524 0 2.822.189 4.203 1.258c1.354 1.047 1.622 2.799 1.589 3.592a.05.05 0 0 1-.051.046l-1.989-.074a.05.05 0 0 1-.049-.058c.038-.371-.066-1.274-1-2.014c-.606-.481-1.519-.532-2.146-.494a.373.373 0 0 0-.323.498c.316.955.84 2.512 1.212 3.52c.546 1.484-.11 2.952.375 4.484c.377 1.191 1.203 2.418 1.636 2.92a.04.04 0 0 1-.013.063l-1.834.851a.04.04 0 0 1-.048-.01c-1.848-2.157-2.5-3.825-2.562-3.988c-.062-.165-.23-.532-.574-.532c-.275 0-.59.352-.809.73l-4.667 7.138a.05.05 0 0 1-.056.02l-1.783-.52a.05.05 0 0 1-.032-.068c1.499-3.164 4.542-9.51 4.773-10.058c.21-.5.181-.916.14-1.085c-.03-.13-.218-.711-.585-2.172");
}

.gzlr_0cpw {
  d: path("M16.356 6.747q.044-.705.081-1.411a.712.712 0 0 1-.081 1.411");
}

.h1qder98v {
  stop-color: var(--svg-color--432742, #432742);
}

.herbgz03w {
  fill: var(--svg-color--4c3531, #4C3531);
  fill-rule: evenodd;
  d: path("M5.611 14.932a.375.375 0 1 1-.69-.296c.093-.216.328-.445.6-.604a1.76 1.76 0 0 1 1.119-.237a.375.375 0 0 1-.099.744a1 1 0 0 0-.641.14a1 1 0 0 0-.215.164a.5.5 0 0 0-.074.088");
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.holozbkuz {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
  stop-opacity: 0;
}

.i34rybopj {
  width: 0.599px;
  height: 1.031px;
  x: 20.662px;
  y: 12.797px;
  rx: 0.299px;
}

.i5vej436q {
  fill: var(--svg-color--4c3531, #4C3531);
  d: path("M7.602 12.764h.594c-.106.668.012 1.608.114 1.996c-1.006.131-1.637-.108-1.856-.246l-.11-1.461c.332-.257.977-.3 1.258-.29");
}

.i9-uutisp {
  d: path("M21.985 27.32L7.61 28.82c4.687-2.24 11.938-4.406 14.375-6.187c1.826-1.334 2.896-1.2 3.281.562c.219 1-1.031 3.625-3.281 4.125");
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ici3-z1na {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m16.484 5.116l-.013-.28a.65.65 0 0 0-.62-.63h-.62a1.07 1.07 0 0 1-.94-.557s.32-.92.848-.8c.386.087.799.224 1.115.43c.771.503.636 1.41.23 1.837");
}

.inzu6lb7s {
  stop-color: var(--svg-color--ff3e28, #FF3E28);
  stop-opacity: 0;
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j5xpxuvyt {
  cx: 13.095px;
  cy: 5.707px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.172px;
  ry: 0.087px;
}

.j83otbcan {
  fill: var(--svg-color--4e3732, #4E3732);
  d: path("m7.305 27.336l1.172-2.39l1.766.304v1.04z");
}

.jhlh1_3ek {
  fill: var(--svg-color--4bc4fd, #4BC4FD);
  d: path("M19.75 29.736H6.017c3.433-1.326 10.769-4.346 12.657-5.818c2.359-1.841 2.937-3.292 4.109-4.976s2.062-2.294 3.922-2.036c1.691.235 3.164 1.575 3.289 4.04c0 4.593-2.74 6.555-4.164 7.51c-1.907 1.28-4.625 1.327-6.078 1.28");
}

.jikp3gouc {
  stop-color: var(--svg-color--b041ab, #B041AB);
}

.jk-0m6p0q {
  stop-color: var(--svg-color--49201f, #49201F);
  stop-opacity: 0;
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.k-l9f-bpq {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.122 5.418c-.289 0-.533.2-.599.468a.12.12 0 0 0 .118.15h.987a.102.102 0 0 0 .1-.12a.62.62 0 0 0-.606-.498");
}

.k3be01b8g {
  d: path("M11.93 5.624a.423.423 0 0 0 .038.831a35 35 0 0 1-.037-.83");
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.kf-sl5b6g {
  stop-color: var(--svg-color--67ecff, #67ECFF);
  stop-opacity: 0;
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.kn6afsb3f {
  stop-color: var(--svg-color--58443e, #58443E);
  stop-opacity: 0;
}

.kp-2efbsj {
  fill: var(--svg-color--4c3531, #4C3531);
  fill-rule: evenodd;
  d: path("M5.404 14.127s.02-.028.083-.08a2.1 2.1 0 0 1 1.279-.412a.375.375 0 0 0 .024-.75a2.84 2.84 0 0 0-1.323.296a2.4 2.4 0 0 0-.452.284a1 1 0 0 0-.296.355a.375.375 0 0 0 .685.306");
}

.ku_swbhun {
  stop-color: var(--svg-color--ff8444, #FF8444);
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.kzew_oulk {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l20_z6baj {
  stop-color: var(--svg-color--695857, #695857);
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.l89w7ttua {
  fill-rule: evenodd;
  d: path("M7.127 13.531c-.941-.283-1.295.01-1.388.12a.375.375 0 1 1-.57-.488c.328-.383 1.014-.7 2.174-.35a.375.375 0 1 1-.216.718");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljni-v35c {
  fill-rule: evenodd;
  d: path("M5.25 14.655q-.005.007-.002 0a.375.375 0 0 1-.69-.295c.056-.13.165-.254.27-.354c.116-.11.265-.225.438-.329a2.5 2.5 0 0 1 1.336-.368a.375.375 0 1 1-.023.75a1.73 1.73 0 0 0-.927.261a1.8 1.8 0 0 0-.307.23a.7.7 0 0 0-.095.105");
}

.lvv_hcmig {
  stop-color: var(--svg-color--9eaef5, #9EAEF5);
  stop-opacity: 0;
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.m27i__bjt {
  d: path("M15.145 5.538a.395.395 0 0 1 .38.499h-.762a.396.396 0 0 1 .382-.499");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.msha2ob6c {
  d: path("M15.116 5.622c.028.037-.03.083-.097.133s-.117.085-.145.047c-.028-.037.003-.108.07-.158s.144-.06.172-.022");
}

.mtqjbpbdp {
  stop-color: var(--svg-color--ff8064, #FF8064);
}

.n-jrenige {
  stop-color: var(--svg-color--36b0fc, #36B0FC);
}

.n0_4eow9o {
  stop-color: var(--svg-color--ff875c, #FF875C);
  stop-opacity: 0;
}

.na5vpgbch {
  stop-color: var(--svg-color--4b3234, #4B3234);
}

.nbncwobqn {
  stop-color: var(--svg-color--6b5957, #6B5957);
}

.nf0740e8o {
  stop-color: var(--svg-color--ff4a2b, #FF4A2B);
}

.nlgpmqbhl {
  d: path("M13.214 5.538a.395.395 0 0 0-.38.499h.762a.397.397 0 0 0-.382-.499");
}

.nmvycabwt {
  stop-color: var(--svg-color--ff7a3c, #FF7A3C);
}

.nzwbzmrxs {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m14.002 5.925l-.261.813c-.045.167.062.334.214.334h.323c.152 0 .26-.17.215-.334l-.219-.813c-.047-.18-.223-.18-.272 0");
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.o2riu6e9b {
  fill: var(--svg-color--4c3531, #4C3531);
  fill-rule: evenodd;
  d: path("M5.25 14.655q-.005.007-.002 0a.375.375 0 0 1-.69-.295c.056-.13.165-.254.27-.354c.116-.11.265-.225.438-.329a2.5 2.5 0 0 1 1.336-.368a.375.375 0 1 1-.023.75a1.73 1.73 0 0 0-.927.261a1.8 1.8 0 0 0-.307.23a.7.7 0 0 0-.095.105");
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
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

.olg-72bto {
  d: path("M16.782 13.438c-.65-1.28-1.166-3.185-1.443-4.424a.714.714 0 0 1 .588-.856c.447-.074.855.272.91.723c.205 1.698.95 3.373 1.445 4.682c.578 1.53.312 1.062.234 3.515c-.057 1.782 1.266 3.25 1.813 4.11l-.407.21c-.609-.828-2.203-2.945-2.203-4.851c0-1.791.063-1.14-.937-3.11");
}

.on9u00bey {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M18.594 8.273c1.209-.02 3.782.829 4.104 4");
}

.ooocs2okn {
  fill: var(--svg-color--4c3531, #4C3531);
  d: path("M6.126 14.875c.125-.137.398-.46.52-.605c.23 0 .91-.067 1.198-.098c-.39.715-.84 1.004-1.074 1.195c-.316.211-.605 0-.644-.066c-.047-.047-.157-.254 0-.426");
}

.or_7yib9u {
  d: path("m14.01 5.838l-.235.813c-.048.167.067.334.23.334h.348c.163 0 .278-.17.23-.334l-.235-.813c-.05-.18-.285-.18-.338 0");
}

.oste98bcz {
  stop-color: var(--svg-color--7f8fff, #7F8FFF);
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.pekg0u7cp {
  d: path("M20.68 13.837c.256-.588.373-1.22.399-1.462l2.047.024c.046.268-.04.583-.079.703c.088.322.037.687 0 .829c-.054.225-.178.713-.238.86c-.074.183-.183.246-.348.23a.4.4 0 0 1-.148-.043a.3.3 0 0 0-.23-.019a.43.43 0 0 1-.227.02a.43.43 0 0 1-.204-.113a.22.22 0 0 0-.195-.06a.5.5 0 0 1-.226.004a.36.36 0 0 1-.172-.115a.22.22 0 0 0-.175-.07c-.085.007-.183.002-.235-.042c-.098-.082-.219-.175.031-.746");
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pq8pgob9x {
  fill: var(--svg-color--402929, #402929);
  d: path("m14.01 5.838l-.235.813c-.048.167.067.334.23.334h.348c.163 0 .278-.17.23-.334l-.235-.813c-.05-.18-.285-.18-.338 0");
}

.prh5swccd {
  stop-color: var(--svg-color--563b38, #563B38);
  stop-opacity: 0;
}

.psn4zabca {
  stop-color: var(--svg-color--231112, #231112);
  stop-opacity: 0;
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.q7quaubxc {
  stop-color: var(--svg-color--67ecff, #67ECFF);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qfyn005sz {
  stop-color: var(--svg-color--ff3e28, #FF3E28);
}

.qg0p67bet {
  stop-color: var(--svg-color--7196ff, #7196FF);
}

.qnmjgylyq {
  d: path("M24.458 21.25L2.29 28.939a.421.421 0 0 0 .138.819h3.948c.487 0 .968-.1 1.156-.156c5.922-2.016 17.406-5.86 18.176-6.2c.443-.195.511-.378.605-.627v-.002c.094-.25.047-1.03-.5-1.453c-.437-.337-1.105-.185-1.355-.07");
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qv62lactv {
  cx: 28.864px;
  cy: 12.801px;
  r: 1.043px;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r95brsblk {
  stop-color: var(--svg-color--3a1c21, #3A1C21);
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.ro0d6lgcg {
  stop-color: var(--svg-color--66b4dd, #66B4DD);
  stop-opacity: 0;
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.rw5mc4bto {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.237 5.418c.288 0 .533.2.599.468c.02.077-.04.15-.119.15h-.986a.102.102 0 0 1-.1-.12a.62.62 0 0 1 .606-.498");
}

.s2ikxxbfc {
  cx: 25.864px;
  cy: 14.75px;
  r: 1.293px;
}

.s41d30h-g {
  stop-color: var(--svg-color--fe5346, #FE5346);
}

.s6k9w6bfo {
  fill: var(--svg-color--000, #000);
  d: path("M13.44 5.933c0-.126-.1-.226-.226-.226a.225.225 0 0 0-.201.33h.4a.2.2 0 0 0 .027-.104");
}

.sazwi3bdn {
  d: path("m23.469 25.315l-.422-1.143l-2.351.536l2.225 1.099a.396.396 0 0 0 .547-.492");
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.siw2d1f7p {
  fill: var(--svg-color--1b71cc, #1B71CC);
  d: path("M21.985 27.32L7.61 28.82c4.687-2.24 11.938-4.406 14.375-6.187c1.826-1.334 2.896-1.2 3.281.562c.219 1-1.031 3.625-3.281 4.125");
}

.so3eyo06u {
  d: path("M26.485 24.32c.981-2.278.626-3.887.055-5.013c-.474-.936-.003-1.662 1.018-1.421c.737.174 1.364.694 1.54 1.43c.721 3.026-.313 6.182-3.582 7.817c-2.95 1.475-7.854 1.594-9.937 1.469c3 0 9.804-1.723 10.906-4.282");
}

.spcerobbw {
  stop-color: var(--svg-color--371f23, #371F23);
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.t2zfh_b3c {
  stop-color: var(--svg-color--2d7cf2, #2D7CF2);
  stop-opacity: 0;
}

.t7r9i6b3f {
  stop-color: var(--svg-color--58443e, #58443E);
}

.tkg6kfb1c {
  d: path("M15.497 5.88a.37.37 0 0 0-.103-.204l-.115.126l.052.101z");
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.u--ocwryb {
  d: path("M19.837 23a29 29 0 0 1-.907-.867l1.867-.883c.075.131.51.8.72 1.117z");
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.ub7ea32uh {
  stop-color: var(--svg-color--635351, #635351);
}

.ui2bqrbyd {
  stop-color: var(--svg-color--b77dc7, #B77DC7);
  stop-opacity: 0;
}

.um5zdnbvm {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M15.116 5.622c.028.037-.03.083-.097.133s-.117.085-.145.047c-.028-.037.003-.108.07-.158s.144-.06.172-.022");
}

.uncbc3bjy {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M16.033 3.679h-.92a.213.213 0 1 1 .034-.425c.239.038.556.09.768.143c.48.12.613.353.65.52a.67.67 0 0 0-.532-.238");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.upowizugn {
  stop-color: var(--svg-color--ff783f, #FF783F);
}

.uu4f6-byw {
  d: path("M6.126 14.875c.125-.137.398-.46.52-.605c.23 0 .91-.067 1.198-.098c-.39.715-.84 1.004-1.074 1.195c-.316.211-.605 0-.644-.066c-.047-.047-.157-.254 0-.426");
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.vb809lo-e {
  d: path("M19.75 29.736H6.017c3.433-1.326 10.769-4.346 12.657-5.818c2.359-1.841 2.937-3.292 4.109-4.976s2.062-2.294 3.922-2.036c1.691.235 3.164 1.575 3.289 4.04c0 4.593-2.74 6.555-4.164 7.51c-1.907 1.28-4.625 1.327-6.078 1.28");
}

.vf1wvpb0u {
  fill: var(--svg-color--202020, #202020);
  d: path("M12.671 4.788a1.23 1.23 0 0 1 .769-.159a.123.123 0 1 1-.03.244a.98.98 0 0 0-.646.147l-.007.005l-.002.001a.123.123 0 0 1-.15-.194z");
}

.vgekv3bdy {
  stop-color: var(--svg-color--3e2828, #3E2828);
}

.vj0--9brr {
  stop-color: var(--svg-color--4db5e2, #4DB5E2);
}

.vsfbr_bbt {
  d: path("m16.484 5.116l-.013-.28a.65.65 0 0 0-.62-.63h-.62a1.07 1.07 0 0 1-.94-.557s.32-.92.848-.8c.386.087.799.224 1.115.43c.771.503.636 1.41.23 1.837");
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.w189cfbhy {
  stop-color: var(--svg-color--290018, #290018);
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.w7mkf5ikd {
  stop-color: var(--svg-color--635351, #635351);
  stop-opacity: 0;
}

.wc05b2bod {
  fill-rule: evenodd;
  d: path("M5.611 14.932a.375.375 0 1 1-.69-.296c.093-.216.328-.445.6-.604a1.76 1.76 0 0 1 1.119-.237a.375.375 0 0 1-.099.744a1 1 0 0 0-.641.14a1 1 0 0 0-.215.164a.5.5 0 0 0-.074.088");
}

.wfnn4zbei {
  fill: var(--svg-color--4c3531, #4C3531);
  fill-rule: evenodd;
  d: path("M7.127 13.531c-.941-.283-1.295.01-1.388.12a.375.375 0 1 1-.57-.488c.328-.383 1.014-.7 2.174-.35a.375.375 0 1 1-.216.718");
}

.wnm4h6zib {
  d: path("M12.046 7.377a1.73 1.73 0 0 0 1.718 1.506h.834a1.73 1.73 0 0 0 1.718-1.506c.053-.833.105-1.663.144-2.495a.64.64 0 0 0-.61-.633h-.62c-.421 0-.803-.25-.977-.638a.29.29 0 0 0-.272-.185h-.563c-.816 0-1.477.668-1.477 1.494c0 .822.05 1.632.105 2.457");
}

.woc0miqaj {
  stop-color: var(--svg-color--fe5346, #FE5346);
  stop-opacity: 0;
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x2d1t4xtf {
  fill-rule: evenodd;
  d: path("M5.404 14.127s.02-.028.083-.08a2.1 2.1 0 0 1 1.279-.412a.375.375 0 0 0 .024-.75a2.84 2.84 0 0 0-1.323.296a2.4 2.4 0 0 0-.452.284a1 1 0 0 0-.296.355a.375.375 0 0 0 .685.306");
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.xpbvfbwgb {
  fill: var(--svg-color--202020, #202020);
  d: path("M15.83 4.837a.8.8 0 0 0-.304-.182c-.134-.043-.303-.054-.536-.026a.123.123 0 0 0 .03.244c.213-.026.343-.013.432.016a.6.6 0 0 1 .217.133a.123.123 0 1 0 .161-.185");
}

.xt887yc-y {
  d: path("M17.568 10.265a.37.37 0 0 1 .34-.415c.628-.038 1.541.013 2.147.494c.934.74 1.038 1.643 1 2.014c-.003.03.02.057.05.058l1.987.074a.05.05 0 0 0 .052-.046c.033-.793-.235-2.545-1.589-3.592c-1.381-1.07-2.68-1.258-4.203-1.258h-.39c-.157 1.285.25 2.193.606 2.671");
}

.xtp47zbsj {
  d: path("m7.305 27.336l1.172-2.39l1.766.304v1.04z");
}

.xujwu-wlk {
  stop-color: var(--svg-color--ff4d30, #FF4D30);
}

.y110racyj {
  stop-color: var(--svg-color--84a6e9, #84A6E9);
}

.yjjppjb0c {
  stop-color: var(--svg-color--ff9e61, #FF9E61);
}

.yqqphg97p {
  d: path("m14.282 3.671l-.029-.06a.29.29 0 0 0-.272-.185h-.563c-.816 0-1.477.668-1.477 1.494v.121c-.15-.114-.34-.355-.34-.746c0-.474.346-.713.566-.866c.063-.043.115-.08.147-.112l.044-.047c.154-.163.43-.456.91-.583q.109-.03.216-.045c.467-.073.807.346.807.819v.204z");
}

.yt5sdf2gy {
  stop-color: var(--svg-color--ff875c, #FF875C);
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.zdcmpbb4s {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m14.282 3.671l-.029-.06a.29.29 0 0 0-.272-.185h-.563c-.816 0-1.477.668-1.477 1.494v.121c-.15-.114-.34-.355-.34-.746c0-.474.346-.713.566-.866c.063-.043.115-.08.147-.112l.044-.047c.154-.163.43-.456.91-.583q.109-.03.216-.045c.467-.073.807.346.807.819v.204z");
}

.zga9nrbjv {
  stop-color: var(--svg-color--61504f, #61504F);
  stop-opacity: 0;
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zkqd2ycat {
  stop-color: var(--svg-color--ff5714, #FF5714);
  stop-opacity: 0;
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
