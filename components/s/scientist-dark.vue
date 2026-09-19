<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iakT1uc)" class="v7gluqbxb"/><path fill="url(#inImBqd)" class="su72xqoac"/><path fill="url(#iV1sFKd)" class="su72xqoac"/><path fill="url(#iXRAxLe)" class="xu2szrbjd"/><path fill="url(#izGmjCe)" class="xu2szrbjd"/><path fill="url(#iqL9usb)" class="xu2szrbjd"/><path fill="url(#inrblnc)" class="xu2szrbjd"/><path fill="url(#iOu9xxd)" class="r3q9_wiir"/><path fill="url(#iw7An0a)" class="r3q9_wiir"/><path fill="url(#iViGBMM)" class="r3q9_wiir"/><path fill="url(#iCFheld)" class="r3q9_wiir"/><g filter="url(#i0Bi6pb)"><path fill="url(#iEc0Kbd)" class="gx7fejb9o"/></g><g filter="url(#ihizP2s)"><path fill="url(#iVg82Db)" class="zehc2bc2m"/></g><g filter="url(#iaznMce)"><path fill="url(#imzHW5c)" class="zrtk-0btq"/></g><path fill="url(#i4t7TWb)" class="ztn-0pg6n"/><path fill="url(#ivSDZvr)" class="ztn-0pg6n"/><path fill="url(#ibfNy4b)" class="ztn-0pg6n"/><path fill="url(#iDvpDpd)" class="ztn-0pg6n"/><path fill="url(#iXhEQSK)" class="ztn-0pg6n"/><path fill="url(#iM7SDhd)" class="mx0dy7bzm"/><path fill="url(#islFNtA)" class="mx0dy7bzm"/><path fill="url(#iw8F5Od)" class="mx0dy7bzm"/><path fill="url(#iFUKKEd)" class="mx0dy7bzm"/><path fill="url(#iuURRhd)" class="zehc2bc2m"/><path fill="url(#iC3KAHn)" class="qctpdhrvn"/><path fill="url(#iupneAV)" class="qctpdhrvn"/><path fill="url(#iakT1uc)" class="v7gluqbxb"/><path fill="url(#iZXPkud)" class="xazl-5b3q"/><path fill="url(#i5B6eec)" class="tq9nmh6wg"/><path fill="url(#i10b0Fd)" class="tq9nmh6wg"/><path fill="url(#iKkFNtc)" class="briaz_b_b"/><path fill="url(#ijPMi1c)" class="briaz_b_b"/><path fill="url(#icTS2Zb)" class="briaz_b_b"/><g filter="url(#ilBJKyq)"><rect class="dpvsui56n"/><rect fill="url(#izniTAb)" class="i6tsuwbjp"/><rect fill="url(#iVSfw3d)" class="i6tsuwbjp"/><rect fill="url(#ieqcHub)" class="i6tsuwbjp"/></g><path fill="url(#i3VTKjc)" class="b7ptc5bto"/><path fill="url(#i5TJHOH)" class="b7ptc5bto"/><path fill="url(#iY8Nhve)" class="b7ptc5bto"/><path fill="url(#iy710pt)" class="b7ptc5bto"/><path fill="url(#ikHXSJd)" class="edip7dywy"/><path fill="url(#iMtf6md)" class="l2nok66dj"/><g filter="url(#isjnIog)"><path fill="url(#iaeG5Lb)" class="k-hxoxbhg"/><path fill="url(#ij5KFpc)" class="k-hxoxbhg"/><path fill="url(#it8SQfc)" class="k-hxoxbhg"/><path fill="url(#iIJ2ird)" class="k-hxoxbhg"/><path fill="url(#iAEf7Td)" class="k-hxoxbhg"/></g><g filter="url(#ifHj77d)"><path stroke="url(#iEqzVJu)" class="mw90q1dqu"/></g><g filter="url(#iD8euEV)"><path stroke="url(#iDsISkb)" class="j7f_szbwp"/></g><g filter="url(#iOVP2Je)"><path stroke="url(#iR7DZcL)" class="adazreaar"/></g><path fill="url(#ifZ2BTd)" class="a-sxnexfj"/><path fill="url(#iBkM6ub)" class="u1ex21b5h"/><g filter="url(#iNq7hje)"><path fill="url(#iuX2S4c)" class="mzwvwcnpv"/></g><path fill="url(#if8cdHd)" class="mzwvwcnpv"/><path fill="url(#iztfgzd)" class="mzwvwcnpv"/><path fill="url(#ifopR5f)" class="mzwvwcnpv"/><path fill="url(#iFRdIrb)" class="mzwvwcnpv"/><path fill="url(#iHNeHdb)" class="mzwvwcnpv"/><path fill="url(#iEmRBUh)" class="mzwvwcnpv"/><path fill="url(#ilQ1z0c)" class="mzwvwcnpv"/><path fill="url(#iJE4mjc)" class="mzwvwcnpv"/><path fill="url(#iCaRYqy)" class="mzwvwcnpv"/><g filter="url(#ipRjSRc)"><path class="u1e-wkoxo"/></g><g filter="url(#iCgH8Wd)"><path class="fxtmsac4g"/><path fill="url(#incM7rb)" class="fmm8sbcyc"/><path fill="url(#izgP3Wb)" class="fmm8sbcyc"/><path fill="url(#i3LM0Ub)" class="fmm8sbcyc"/><path fill="url(#iktMWMd)" class="fmm8sbcyc"/><path fill="url(#i5DVHyc)" class="fmm8sbcyc"/></g><g filter="url(#iwTkQud)"><path stroke="url(#iGwV7zb)" class="xerdc-bkq"/></g><path fill="url(#iaO1DBe)" class="k1l7rcmme"/><g filter="url(#iaMj7uG)"><path fill="url(#ibQu5Lb)" class="vxc_33b_r"/><path fill="url(#iEmpH3b)" class="vxc_33b_r"/><path fill="url(#iw4livv)" class="vxc_33b_r"/><path fill="url(#is9eKQe)" class="vxc_33b_r"/><path fill="url(#ikthl9d)" class="vxc_33b_r"/></g><g filter="url(#iNPQTfe)"><path class="ievcqe6-b"/></g><g filter="url(#iEzswge)"><path class="xn9ioi9ep"/></g><g filter="url(#iIyIcpb)"><path class="qxz6u5blh"/><path fill="url(#ilqU6Yd)" class="fff6690zm"/><path fill="url(#iJpK1Oc)" class="fff6690zm"/></g><g filter="url(#ihVNYzd)"><path class="mrpm2ac7n"/><path fill="url(#iDwNenP)" class="ry0u1-aml"/></g><path class="nedljebjz"/><path fill="url(#iPf8Scc)" class="ly54c-bwl"/><path class="ge2gdowzb"/><g filter="url(#icWNFcd)"><path class="m-gdoiz-p"/><path fill="url(#iOckxGc)" class="t1h65cb3y"/></g><g filter="url(#iRzoQde)"><path fill="url(#iIUnzjc)" class="pku9hacug"/></g><path class="bs712usjw"/><path fill="url(#iMkNj9c)" class="b7xhdibmp"/><path class="h6tsfek6j"/><g filter="url(#ihXiXQc)"><path fill="url(#iWWk2od)" class="pkh5xs8tl"/></g><g filter="url(#iy8Dnjy)"><ellipse transform="rotate(-27.914 12.972 10.135)" class="esnu1u5kn"/><ellipse fill="url(#iN3kcCp)" transform="rotate(-27.914 12.972 10.135)" class="b7m7jvbhs"/></g><path fill="url(#iuvC0sd)" class="ifk0xsq8e"/><path fill="url(#iqg9Ujb)" class="ifk0xsq8e"/><path fill="url(#iGh0qlc)" class="ifk0xsq8e"/><path fill="url(#iVVR94c)" class="ifk0xsq8e"/><path fill="url(#ihehM9d)" class="o1h14jbrx"/><path fill="url(#iwaP4Yb)" class="o1h14jbrx"/><g filter="url(#i9PKPNd)"><path fill="url(#ihoV42c)" class="x2pnnabxt"/></g><g filter="url(#iowwPFc)"><path fill="url(#iKi4Ebc)" class="ksmphdgaj"/></g><g filter="url(#ixAbyFd)"><path class="aeknldblb"/></g><g filter="url(#in2EOZd)" class="z4n2hhy8u"><path fill="url(#ilLlLTV)" class="jfs_p_tcs"/></g><g filter="url(#iXBlNqc)"><path clip-rule="evenodd" class="jdt4fccib"/></g><defs><radialGradient id="inImBqd" cx="0" cy="0" r="1" gradientTransform="scale(3.29991 5.8125)rotate(90 .76 3.921)" gradientUnits="userSpaceOnUse"><stop class="e2ig5yb1x"/><stop offset="1" class="rsfdnufmx"/></radialGradient><radialGradient id="iV1sFKd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.65625 6.93357 0 15.446 30.378)" gradientUnits="userSpaceOnUse"><stop class="eol9ugodk"/><stop offset="1" class="e080jybbb"/></radialGradient><radialGradient id="iXRAxLe" cx="0" cy="0" r="1" gradientTransform="rotate(161.686 4.488 14.592)scale(4.67425 7.57955)" gradientUnits="userSpaceOnUse"><stop class="hy6proxed"/><stop offset="1" class="bqs6izbmd"/></radialGradient><radialGradient id="inrblnc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.375 -2.57376 0 9.302 17.472)" gradientUnits="userSpaceOnUse"><stop class="x3hlfcbwc"/><stop offset="1" class="sfpaimhix"/></radialGradient><radialGradient id="iOu9xxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.15073 2.71782 0 21.206 30.347)" gradientUnits="userSpaceOnUse"><stop class="lj5m7ucmi"/><stop offset="1" class="d3a6h5dbs"/></radialGradient><radialGradient id="iw7An0a" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.15625 -3.9375 0 22.77 18.597)" gradientUnits="userSpaceOnUse"><stop class="n8vj2kb3y"/><stop offset="1" class="irjqokbks"/></radialGradient><radialGradient id="iVg82Db" cx="0" cy="0" r="1" gradientTransform="matrix(-3.7279 1.31251 -2.69681 -7.65971 14.999 21.972)" gradientUnits="userSpaceOnUse"><stop class="iezv8nbum"/><stop offset="1" class="ry-6rkb7q"/></radialGradient><radialGradient id="i4t7TWb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.74796 3.71877 -3.74799 -3.7774 22.49 17.753)" gradientUnits="userSpaceOnUse"><stop class="y5gxirbqq"/><stop offset="1" class="t0qf5rbqk"/></radialGradient><radialGradient id="ivSDZvr" cx="0" cy="0" r="1" gradientTransform="rotate(-64.11 29.357 -.224)scale(8.30198 11.1931)" gradientUnits="userSpaceOnUse"><stop class="mvrro-b_u"/><stop offset=".93" class="ocku6nzyd"/></radialGradient><radialGradient id="ibfNy4b" cx="0" cy="0" r="1" gradientTransform="matrix(-.73439 2.1875 -3.93465 -1.32095 19.943 16.05)" gradientUnits="userSpaceOnUse"><stop offset=".073" class="xpzhm0iru"/><stop offset="1" class="jqs3afbfy"/></radialGradient><radialGradient id="iM7SDhd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.95848 0 0 -8.5991 8.226 26.174)" gradientUnits="userSpaceOnUse"><stop class="xoi7hsb-w"/><stop offset="1" class="hkq9astav"/></radialGradient><radialGradient id="iw8F5Od" cx="0" cy="0" r="1" gradientTransform="matrix(-7.51743 0 0 -10.8202 10.005 29.03)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="c1dciy28n"/><stop offset="1" class="vxd8ts5kx"/></radialGradient><radialGradient id="iuURRhd" cx="0" cy="0" r="1" gradientTransform="matrix(-1 2.84375 -3.2172 -1.13131 12.552 16.128)" gradientUnits="userSpaceOnUse"><stop offset=".058" class="fbqio7b7r"/><stop offset="1" class="txsyviqti"/></radialGradient><radialGradient id="iC3KAHn" cx="0" cy="0" r="1" gradientTransform="matrix(.41584 12.10916 -8.52544 .29277 24.177 17.94)" gradientUnits="userSpaceOnUse"><stop class="v6ge5bcpf"/><stop offset="1" class="z78o0obou"/></radialGradient><radialGradient id="iZXPkud" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.59837 5.09841 0 15.426 18.68)" gradientUnits="userSpaceOnUse"><stop class="p9hufzb8h"/><stop offset=".621" class="c16vk8bri"/><stop offset="1" class="l0v2fsbcc"/></radialGradient><radialGradient id="i5B6eec" cx="0" cy="0" r="1" gradientTransform="matrix(-1.7802 1.77747 -2.19627 -2.19964 27.55 23.298)" gradientUnits="userSpaceOnUse"><stop offset=".493" class="k7qyxzbsl"/><stop offset=".946" class="zdypug-8z"/></radialGradient><radialGradient id="i10b0Fd" cx="0" cy="0" r="1" gradientTransform="matrix(.80395 -.6129 .32018 .41998 27.206 23.528)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="m8ott3b3k"/><stop offset="1" class="zk5cvukoj"/></radialGradient><radialGradient id="icTS2Zb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.54688 -.39416 0 25.571 19.44)" gradientUnits="userSpaceOnUse"><stop class="hkh0bccgk"/><stop offset="1" class="sfa02aclf"/></radialGradient><radialGradient id="izniTAb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.91833 0 0 -.20741 25.177 19.128)" gradientUnits="userSpaceOnUse"><stop offset=".496" class="afeb8bsjy"/><stop offset="1" class="rced3uh7f"/></radialGradient><radialGradient id="iVSfw3d" cx="0" cy="0" r="1" gradientTransform="matrix(-.28516 .14844 -.12607 -.24218 27.004 18.98)" gradientUnits="userSpaceOnUse"><stop class="p4k8mjbje"/><stop offset="1" class="e1oaafz6u"/></radialGradient><radialGradient id="ieqcHub" cx="0" cy="0" r="1" gradientTransform="matrix(-.17969 .13281 -.08816 -.11928 23.407 19.34)" gradientUnits="userSpaceOnUse"><stop class="bj_z41bxg"/><stop offset="1" class="boi6rx35q"/></radialGradient><radialGradient id="iy710pt" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.34375 -.51563 0 26.227 21.284)" gradientUnits="userSpaceOnUse"><stop class="tsloro5fn"/><stop offset="1" class="p9rinuedy"/></radialGradient><radialGradient id="ij5KFpc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.574 25.354)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="it8SQfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.574 26.649)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iIJ2ird" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.574 27.899)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="iAEf7Td" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.574 29.25)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="entsizubv"/><stop offset="1" class="wj9mtgody"/></radialGradient><radialGradient id="ifZ2BTd" cx="0" cy="0" r="1" gradientTransform="rotate(69.657 1.654 20.37)scale(2.15388 2.55864)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="iBkM6ub" cx="0" cy="0" r="1" gradientTransform="matrix(1.47646 .46402 -1.43155 4.555 9.37 12.229)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="iuX2S4c" cx="0" cy="0" r="1" gradientTransform="matrix(-5.22785 0 0 -9.24802 18.233 10.797)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="iztfgzd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.02223 12.42352 -10.28813 -.84653 17.007 4.884)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset=".997" class="h1qder98v"/></radialGradient><radialGradient id="ifopR5f" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.14835 1.42108 0 17.873 9.484)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="iFRdIrb" cx="0" cy="0" r="1" gradientTransform="rotate(-89.794 11.345 -1.82)scale(1.09429 1.19084)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="iHNeHdb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.49599 .5363 -1.37 -21.703 18.858 11.785)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="iEmRBUh" cx="0" cy="0" r="1" gradientTransform="matrix(4.073 -2.6483 .96946 1.491 9.958 6.472)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="ilQ1z0c" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 6.898 13.486)scale(2.50844 1.00273)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="iJE4mjc" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 7.286 7.943)scale(3.36898 2.78137)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="izgP3Wb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .2441 -.76718 0 15.892 12.354)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="iktMWMd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.52115 .69743 -1.12083 -2.4446 16.008 11.784)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="iaO1DBe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.72074 2.89971 0 15.426 14.337)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="iEmpH3b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.50133 8.85445 0 10.196 7.905)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="iw4livv" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 14.965 -6.006)scale(2.51513 4.45631)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="is9eKQe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.35883 -1.5514 1.13881 -1.7315 19.532 2.939)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="ikthl9d" cx="0" cy="0" r="1" gradientTransform="matrix(.90511 1.475 -3.4154 2.09582 14.52 1.347)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="ilqU6Yd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.20113 0 0 -.81692 15.68 3.606)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="iJpK1Oc" cx="0" cy="0" r="1" gradientTransform="matrix(3.2182 -5.09542 5.6452 3.56544 9.995 7.548)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iDwNenP" cx="0" cy="0" r="1" gradientTransform="rotate(6.667 -42.435 150.4)scale(3.27033 1.36922)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iPf8Scc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81132 -1.2905 0 17.608 10.23)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iOckxGc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 11.216 .902)scale(.37829 .52081)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iMkNj9c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .81136 -1.29056 0 13.244 10.231)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iN3kcCp" cx="0" cy="0" r="1" gradientTransform="matrix(-.00774 -.49408 .59392 -.0093 12.957 10.45)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iqg9Ujb" cx="0" cy="0" r="1" gradientTransform="matrix(.62855 2.24328 -2.14025 .59968 20.043 9.895)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="iGh0qlc" cx="0" cy="0" r="1" gradientTransform="matrix(.78778 -1.0811 .90618 .66032 20.404 10.44)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="iVVR94c" cx="0" cy="0" r="1" gradientTransform="matrix(.587 -1.55042 2.07158 .7843 20.518 10.612)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="iwaP4Yb" cx="0" cy="0" r="1" gradientTransform="rotate(101.248 .952 9.201)scale(2.11668 2.08089)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="ihoV42c" cx="0" cy="0" r="1" gradientTransform="matrix(-.91648 .1573 -.06938 -.40422 10.512 10.538)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><linearGradient id="iakT1uc" x1="8.23" x2="22.659" y1="15.358" y2="15.358" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kt__1405u"/><stop offset="1" class="h_j9u0wvt"/></linearGradient><linearGradient id="izGmjCe" x1="11.239" x2="11.239" y1="30.472" y2="29.159" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iqL9usb" x1="15.177" x2="14.208" y1="29.159" y2="29.159" gradientUnits="userSpaceOnUse"><stop offset=".129" class="dx1e6jb0z"/><stop offset="1" class="q4mowll4q"/></linearGradient><linearGradient id="iViGBMM" x1="19.74" x2="19.74" y1="30.472" y2="29.159" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iCFheld" x1="15.802" x2="16.505" y1="28.034" y2="28.034" gradientUnits="userSpaceOnUse"><stop class="bx23o8bkx"/><stop offset="1" class="i4kgizoks"/></linearGradient><linearGradient id="iEc0Kbd" x1="10.677" x2="12.896" y1="18.003" y2="24.691" gradientUnits="userSpaceOnUse"><stop class="v4-zmrbyl"/><stop offset="1" class="r-0tl8b_g"/></linearGradient><linearGradient id="imzHW5c" x1="20.45" x2="18.099" y1="19.032" y2="23.733" gradientUnits="userSpaceOnUse"><stop class="z4xhuybyb"/><stop offset="1" class="lkjzf4omc"/></linearGradient><linearGradient id="iDvpDpd" x1="18.958" x2="17.552" y1="24.159" y2="22.659" gradientUnits="userSpaceOnUse"><stop class="p2mir8bpk"/><stop offset="1" class="ifg4wbcuq"/></linearGradient><linearGradient id="iXhEQSK" x1="17.146" x2="17.974" y1="18.941" y2="19.284" gradientUnits="userSpaceOnUse"><stop offset=".081" class="ea_0ewlyw"/><stop offset="1" class="z_a2ribdx"/></linearGradient><linearGradient id="islFNtA" x1="6.567" x2="6.567" y1="30.415" y2="29.281" gradientUnits="userSpaceOnUse"><stop class="pclg_efwa"/><stop offset="1" class="zpmhxsbxd"/></linearGradient><linearGradient id="iFUKKEd" x1="8.38" x2="7.935" y1="29.449" y2="29.446" gradientUnits="userSpaceOnUse"><stop offset=".175" class="w01lnqx9a"/><stop offset="1" class="xx10debny"/></linearGradient><linearGradient id="iupneAV" x1="22.753" x2="23.162" y1="27.722" y2="27.706" gradientUnits="userSpaceOnUse"><stop class="ckzhu0bvt"/><stop offset="1" class="dtqi4cbss"/></linearGradient><linearGradient id="iKkFNtc" x1="23.825" x2="26.529" y1="20.909" y2="20.909" gradientUnits="userSpaceOnUse"><stop offset=".253" class="cpykpvzxv"/><stop offset=".773" class="ahix7mbin"/></linearGradient><linearGradient id="ijPMi1c" x1="26.529" x2="26.18" y1="20.894" y2="20.894" gradientUnits="userSpaceOnUse"><stop class="g1a66we9o"/><stop offset="1" class="c3eiz-bza"/></linearGradient><linearGradient id="i3VTKjc" x1="26.529" x2="25.177" y1="23.222" y2="23.222" gradientUnits="userSpaceOnUse"><stop offset=".477" class="ubsir5m6c"/><stop offset="1" class="v0fk_zbwr"/></linearGradient><linearGradient id="i5TJHOH" x1="26.529" x2="26.129" y1="23.37" y2="23.37" gradientUnits="userSpaceOnUse"><stop class="bywelvb6j"/><stop offset="1" class="s44sum5km"/></linearGradient><linearGradient id="iY8Nhve" x1="23.696" x2="24.227" y1="23.37" y2="23.37" gradientUnits="userSpaceOnUse"><stop class="jr9zsmblm"/><stop offset="1" class="r1tra0r1f"/></linearGradient><linearGradient id="ikHXSJd" x1="24.782" x2="23.892" y1="21.863" y2="21.863" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="iMtf6md" x1="24.782" x2="23.892" y1="23.644" y2="23.644" gradientUnits="userSpaceOnUse"><stop class="d7d_80btw"/><stop offset="1" class="x3pdtmzbl"/></linearGradient><linearGradient id="iaeG5Lb" x1="27.165" x2="23.137" y1="28.112" y2="28.112" gradientUnits="userSpaceOnUse"><stop offset=".146" class="o3k0towjz"/><stop offset=".861" class="qxb7siz6w"/></linearGradient><linearGradient id="iEqzVJu" x1="23.754" x2="25.463" y1="26.13" y2="26.13" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iDsISkb" x1="23.676" x2="25.385" y1="27.435" y2="27.435" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="iR7DZcL" x1="23.754" x2="25.463" y1="28.739" y2="28.739" gradientUnits="userSpaceOnUse"><stop class="wj3drmbex"/><stop offset="1" class="ur8e5kbgj"/></linearGradient><linearGradient id="if8cdHd" x1="20.583" x2="16.23" y1="12.483" y2="12.483" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="iCaRYqy" x1="15.473" x2="15.473" y1="17.049" y2="16.409" gradientUnits="userSpaceOnUse"><stop class="dn2_hckup"/><stop offset="1" class="jk-0m6p0q"/></linearGradient><linearGradient id="incM7rb" x1="16.264" x2="15.426" y1="11.668" y2="11.703" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="i3LM0Ub" x1="15.426" x2="15.426" y1="12.807" y2="12.342" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="i5DVHyc" x1="15.426" x2="15.426" y1="9.852" y2="10.649" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="iGwV7zb" x1="14.224" x2="14.543" y1="14.182" y2="13.348" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="ibQu5Lb" x1="22.278" x2="10.665" y1="5.135" y2="5.135" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="iIUnzjc" x1="18.386" x2="18.072" y1="10.285" y2="10.478" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iWWk2od" x1="13.988" x2="13.674" y1="10.285" y2="10.478" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iuvC0sd" x1="21.862" x2="20.655" y1="9.962" y2="12.138" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="ihehM9d" x1="9.576" x2="11.034" y1="10.666" y2="10.539" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="iKi4Ebc" x1="20.842" x2="20.842" y1="9.58" y2="11.483" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient><linearGradient id="ilLlLTV" x1="10.917" x2="22.177" y1="9.789" y2="9.789" gradientUnits="userSpaceOnUse"><stop offset=".257" class="x5t80dq2u"/><stop offset="1" class="p67rx3bjq"/></linearGradient><filter id="i0Bi6pb" width="7.023" height="11.703" x="8.591" y="15.777" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2166" stdDeviation=".375"/></filter><filter id="ihizP2s" width="5.673" height="10.453" x="9.475" y="15.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.721569 0 0 0 0 0.941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2166"/></filter><filter id="iaznMce" width="6.388" height="10.529" x="15.499" y="16.343" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2166" stdDeviation=".375"/></filter><filter id="ilBJKyq" width="4.008" height=".781" x="23.173" y="18.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.67451 0 0 0 0 0.796078 0 0 0 0 0.94902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2166"/></filter><filter id="isjnIog" width="4.468" height="5.556" x="23.137" y="24.494" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.117647 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2166"/></filter><filter id="ifHj77d" width="2.097" height=".3" x="23.604" y="25.902" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2166" stdDeviation=".05"/></filter><filter id="iD8euEV" width="2.097" height=".3" x="23.526" y="27.207" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2166" stdDeviation=".05"/></filter><filter id="iOVP2Je" width="2.097" height=".3" x="23.604" y="28.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2166" stdDeviation=".05"/></filter><filter id="iNq7hje" width="11.22" height="12.542" x="10.363" y="4.626" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2166"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2166" result="effect2_innerShadow_4002_2166"/></filter><filter id="ipRjSRc" width="3.747" height="4.9" x="13.41" y="9.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2166" stdDeviation=".5"/></filter><filter id="iCgH8Wd" width="2.277" height="3.3" x="14.287" y="9.773" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2166" stdDeviation=".1"/></filter><filter id="iwTkQud" width="3.718" height="1.573" x="13.566" y="13.098" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2166" stdDeviation=".05"/></filter><filter id="iaMj7uG" width="12.873" height="8.357" x="8.989" y="1.45" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2166"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2166" result="effect2_innerShadow_4002_2166"/></filter><filter id="iNPQTfe" width="2.339" height="1.19" x="17.015" y="7.458" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2166"/></filter><filter id="iEzswge" width="2.339" height="1.176" x="11.758" y="7.472" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2166"/></filter><filter id="iIyIcpb" width="6.734" height="5.992" x="9.345" y="2.539" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2166"/><feGaussianBlur result="effect2_foregroundBlur_4002_2166" stdDeviation=".125"/></filter><filter id="ihVNYzd" width="6.362" height="5.736" x="15.267" y="2.962" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.305882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2166"/><feGaussianBlur result="effect2_foregroundBlur_4002_2166" stdDeviation=".125"/></filter><filter id="icWNFcd" width=".787" height=".696" x="16.873" y="9.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2166" stdDeviation=".05"/></filter><filter id="iRzoQde" width=".891" height=".913" x="17.713" y="9.866" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2166" stdDeviation=".1"/></filter><filter id="ihXiXQc" width=".986" height="1.04" x="13.271" y="9.803" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2166" stdDeviation=".1"/></filter><filter id="iy8Dnjy" width=".913" height=".705" x="12.516" y="9.783" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2166" stdDeviation=".05"/></filter><filter id="i9PKPNd" width="1.329" height="2.379" x="9.345" y="9.349" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2166" stdDeviation=".125"/></filter><filter id="iowwPFc" width="1.947" height="2.903" x="19.869" y="9.08" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2166" stdDeviation=".25"/></filter><filter id="ixAbyFd" width="5.266" height="3.006" x="16.305" y="3.482" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_2166" stdDeviation=".375"/></filter><filter id="in2EOZd" width="10.729" height="5.624" x="10.061" y="6.526" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.239216 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2166"/></filter><filter id="iXBlNqc" width="11.479" height="6.324" x="9.611" y="6.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.541176 0 0 0 0 0.494118 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_2166"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.760784 0 0 0 0 0.752941 0 0 0 0 0.776471 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_2166" result="effect2_innerShadow_4002_2166"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:scientist-dark" /></template>
<style>
.a-sxnexfj {
  d: path("M20.287 12.047c.335-.01.65-.124.905-.309v.931c0 .894-.532 1.69-1.341 2.02q.256-.546.346-1.18z");
}

.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.adazreaar {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.754 28.661h1.797");
}

.aeknldblb {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M19.619 5.199h-2.081a.483.483 0 1 1 .077-.961c.54.086 1.257.206 1.737.325c1.085.269 1.385.797 1.469 1.174a1.51 1.51 0 0 0-1.203-.538");
}

.afeb8bsjy {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.ahix7mbin {
  stop-color: var(--svg-color--bff0ff, #BFF0FF);
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

.b7m7jvbhs {
  cx: 12.972px;
  cy: 10.135px;
  rx: 0.39px;
  ry: 0.197px;
}

.b7ptc5bto {
  d: path("M26.529 21.284v4.172h-2.704v-4.172z");
}

.b7xhdibmp {
  d: path("M13.242 9.754a.893.893 0 0 0-.86 1.128h1.724a1 1 0 0 0 .032-.236a.9.9 0 0 0-.896-.892");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bj_z41bxg {
  stop-color: var(--svg-color--caedff, #CAEDFF);
}

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.boi6rx35q {
  stop-color: var(--svg-color--caedff, #CAEDFF);
  stop-opacity: 0;
}

.bqs6izbmd {
  stop-color: var(--svg-color--cdc1db, #CDC1DB);
}

.briaz_b_b {
  d: path("M23.825 19.519h2.703v5.938h-2.703z");
}

.bs712usjw {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.035 9.482c-.653 0-1.205.45-1.355 1.059a.273.273 0 0 0 .268.34h2.23a.23.23 0 0 0 .228-.271a1.4 1.4 0 0 0-1.371-1.128");
}

.bx23o8bkx {
  stop-color: var(--svg-color--b28598, #B28598);
}

.bywelvb6j {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
}

.c16vk8bri {
  stop-color: var(--svg-color--301619, #301619);
}

.c1dciy28n {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
  stop-opacity: 0;
}

.c2_7179_n {
  stop-color: var(--svg-color--432742, #432742);
  stop-opacity: 0;
}

.c3eiz-bza {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
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

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ckzhu0bvt {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
}

.cpykpvzxv {
  stop-color: var(--svg-color--a3d3ff, #A3D3FF);
}

.d3a6h5dbs {
  stop-color: var(--svg-color--ccb8e5, #CCB8E5);
}

.d7d_80btw {
  stop-color: var(--svg-color--0e7268, #0E7268);
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
}

.dn2_hckup {
  stop-color: var(--svg-color--49201f, #49201F);
}

.dpvsui56n {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.738px;
  fill: var(--svg-color--addaff, #ADDAFF);
  rx: 0.391px;
}

.dtqi4cbss {
  stop-color: var(--svg-color--b59fc2, #B59FC2);
  stop-opacity: 0;
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
}

.dx1e6jb0z {
  stop-color: var(--svg-color--be9bb3, #BE9BB3);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e080jybbb {
  stop-color: var(--svg-color--ed5030, #ED5030);
  stop-opacity: 0;
}

.e1oaafz6u {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
  stop-opacity: 0;
}

.e2ig5yb1x {
  stop-color: var(--svg-color--e07221, #E07221);
}

.ea_0ewlyw {
  stop-color: var(--svg-color--c79f97, #C79F97);
}

.edip7dywy {
  d: path("M23.825 22.097v-.469h.805a.234.234 0 1 1 0 .469z");
}

.entsizubv {
  stop-color: var(--svg-color--5e4745, #5E4745);
}

.eol9ugodk {
  stop-color: var(--svg-color--ed5030, #ED5030);
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.esnu1u5kn {
  cx: 12.972px;
  cy: 10.135px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.39px;
  ry: 0.197px;
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.fbqio7b7r {
  stop-color: var(--svg-color--a27d98, #A27D98);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fff6690zm {
  d: path("m15.658 5.182l-.066-.137a.66.66 0 0 0-.615-.419h-1.273c-1.846 0-3.342 1.513-3.342 3.38v.275c-.34-.26-.767-.805-.767-1.688c0-1.072.781-1.614 1.28-1.96c.14-.097.26-.179.33-.253l.1-.104c.35-.371.973-1.032 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.011.806.42.806.892v1.485z");
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.fmm8sbcyc {
  d: path("m15.044 10.278l-.532 1.839c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.839c-.115-.407-.646-.407-.765 0");
}

.ft5dv1b6b {
  fill: none;
}

.fxtmsac4g {
  fill: var(--svg-color--402929, #402929);
  d: path("m15.044 10.278l-.532 1.839c-.108.378.152.756.52.756h.787c.369 0 .63-.384.52-.756l-.53-1.839c-.115-.407-.646-.407-.765 0");
}

.g1a66we9o {
  stop-color: var(--svg-color--aedcff, #AEDCFF);
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.ge2gdowzb {
  fill: var(--svg-color--000, #000);
  d: path("M17.099 10.646c0-.284.227-.51.51-.51a.51.51 0 0 1 .455.746h-.904a.46.46 0 0 1-.061-.236");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gx7fejb9o {
  d: path("m9.474 17.782l-.131 1.733a.6.6 0 0 0 .494.636l.479.085a.15.15 0 0 1 .085.249l-.626.69a.5.5 0 0 0 .014.687l4.733 4.808a.2.2 0 0 0 .342-.14v-3.38c0-.283-.06-.562-.175-.82l-2.606-5.803c-.929.298-1.806.722-2.61 1.255");
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.h1qder98v {
  stop-color: var(--svg-color--432742, #432742);
}

.h6tsfek6j {
  fill: var(--svg-color--000, #000);
  d: path("M13.753 10.646a.51.51 0 0 0-.511-.51a.51.51 0 0 0-.455.746h.905a.5.5 0 0 0 .06-.236");
}

.hkh0bccgk {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
}

.hkq9astav {
  stop-color: var(--svg-color--d6cbe2, #D6CBE2);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.hy6proxed {
  stop-color: var(--svg-color--e1d2f9, #E1D2F9);
}

.i4kgizoks {
  stop-color: var(--svg-color--d1bee7, #D1BEE7);
  stop-opacity: 0;
}

.i6tsuwbjp {
  width: 4.008px;
  height: 0.781px;
  x: 23.173px;
  y: 18.738px;
  rx: 0.391px;
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.ievcqe6-b {
  fill: var(--svg-color--202020, #202020);
  d: path("M19.159 8.162a1.85 1.85 0 0 0-.688-.412c-.304-.095-.685-.121-1.212-.057a.277.277 0 1 0 .067.55c.481-.058.776-.027.979.036c.198.063.332.164.49.3a.277.277 0 1 0 .364-.417");
}

.iezv8nbum {
  stop-color: var(--svg-color--fcefff, #FCEFFF);
}

.ifg4wbcuq {
  stop-color: var(--svg-color--e2d2ee, #E2D2EE);
  stop-opacity: 0;
}

.ifk0xsq8e {
  d: path("M20.348 12.138q.1-1.595.184-3.191a1.61 1.61 0 0 1-.184 3.191");
}

.irjqokbks {
  stop-color: var(--svg-color--d7ccea, #D7CCEA);
  stop-opacity: 0;
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j7f_szbwp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.676 27.357h1.797");
}

.jdt4fccib {
  fill: var(--svg-color--9f9ba5, #9F9BA5);
  fill-rule: evenodd;
  d: path("M9.761 9.231c.011-1.676 1.389-3.005 3.047-3.005h5.275a3.01 3.01 0 0 1 3.007 3.04v.001c-.022 1.568-1.339 2.918-2.907 2.973h-.002a3.06 3.06 0 0 1-2.63-1.342c-.045-.065-.09-.076-.112-.076s-.067.01-.112.076a3.08 3.08 0 0 1-2.549 1.352a3.02 3.02 0 0 1-3.017-3.017zm.6.003a2.42 2.42 0 0 0 2.417 2.416c.841 0 1.62-.435 2.05-1.085l.002-.003a.74.74 0 0 1 .609-.34c.243 0 .465.128.608.34l.001.001a2.46 2.46 0 0 0 2.114 1.077c1.248-.044 2.31-1.133 2.328-2.381a2.41 2.41 0 0 0-2.407-2.433h-5.275c-1.336 0-2.437 1.07-2.447 2.408");
}

.jfs_p_tcs {
  d: path("M18.083 6.526h-5.275c-1.497 0-2.737 1.2-2.747 2.707a2.72 2.72 0 0 0 2.717 2.717c.942 0 1.814-.486 2.3-1.22c.189-.277.533-.277.721 0a2.76 2.76 0 0 0 2.373 1.21c1.408-.05 2.598-1.269 2.618-2.677a2.71 2.71 0 0 0-2.707-2.737");
}

.jk-0m6p0q {
  stop-color: var(--svg-color--49201f, #49201F);
  stop-opacity: 0;
}

.jqs3afbfy {
  stop-color: var(--svg-color--ece2e9, #ECE2E9);
  stop-opacity: 0;
}

.jr9zsmblm {
  stop-color: var(--svg-color--a4c098, #A4C098);
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.k-hxoxbhg {
  d: path("M23.137 25.375c0-.4.325-.731.726-.731h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.39a.735.735 0 0 1 0-1.313a.735.735 0 0 1 0-1.315a.74.74 0 0 1-.406-.657");
}

.k1l7rcmme {
  d: path("M15.426 13.694c-.508 0-.985-.12-1.386-.329c-.137-.07-.284.085-.198.21c.335.507.919.845 1.584.845c.664 0 1.248-.338 1.583-.846c.086-.129-.06-.278-.198-.209a3 3 0 0 1-1.385.329");
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.k7qyxzbsl {
  stop-color: var(--svg-color--4b312d, #4B312D);
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.ksmphdgaj {
  d: path("M20.369 11.483q.058-.95.11-1.903a.956.956 0 0 1-.11 1.903");
}

.kt__1405u {
  stop-color: var(--svg-color--ccc, #CCC);
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l0v2fsbcc {
  stop-color: var(--svg-color--2a1515, #2A1515);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.l2nok66dj {
  d: path("M23.825 23.878v-.469h.805a.234.234 0 0 1 0 .47z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lj5m7ucmi {
  stop-color: var(--svg-color--bea0dc, #BEA0DC);
}

.lkjzf4omc {
  stop-color: var(--svg-color--c5b2dd, #C5B2DD);
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.ly54c-bwl {
  d: path("M17.61 9.754a.892.892 0 0 1 .86 1.128h-1.724a.896.896 0 0 1 .864-1.128");
}

.m-gdoiz-p {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M17.544 9.943c.064.085-.07.188-.22.301c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.325-.135.39-.05");
}

.m8ott3b3k {
  stop-color: var(--svg-color--675655, #675655);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.mrpm2ac7n {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m20.638 8.448l-.029-.63c-.01-.764-.641-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.136-.12-.368c-.257-.97.67-1.713 1.655-1.522c.974.19 2.083.517 2.903 1.052c1.744 1.138 1.439 3.189.52 4.154");
}

.mvrro-b_u {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
}

.mw90q1dqu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.754 26.052h1.797");
}

.mx0dy7bzm {
  d: path("M8.226 30.05V18.26c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07z");
}

.mzwvwcnpv {
  d: path("M10.6 13.562a3.916 3.916 0 0 0 3.887 3.406h1.886a3.916 3.916 0 0 0 3.886-3.406c.118-1.883.236-3.76.324-5.642a1.45 1.45 0 0 0-1.379-1.432h-1.4c-.955 0-1.82-.564-2.212-1.443a.66.66 0 0 0-.615-.419h-1.273c-1.846 0-3.341 1.513-3.341 3.38c0 1.86.116 3.69.238 5.556");
}

.n8vj2kb3y {
  stop-color: var(--svg-color--f6f4ff, #F6F4FF);
}

.nedljebjz {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.817 9.482c.653 0 1.204.45 1.355 1.059a.274.274 0 0 1-.268.34h-2.231a.23.23 0 0 1-.228-.271a1.4 1.4 0 0 1 1.372-1.128");
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1h14jbrx {
  d: path("M10.372 8.938a1.61 1.61 0 0 0 .138 3.2a78 78 0 0 1-.138-3.2");
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.o3k0towjz {
  stop-color: var(--svg-color--533632, #533632);
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.ocku6nzyd {
  stop-color: var(--svg-color--d8bbf3, #D8BBF3);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p2mir8bpk {
  stop-color: var(--svg-color--d2b4ed, #D2B4ED);
}

.p4k8mjbje {
  stop-color: var(--svg-color--d3faff, #D3FAFF);
}

.p67rx3bjq {
  stop-color: var(--svg-color--7e9a67, #7E9A67);
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.p9hufzb8h {
  stop-color: var(--svg-color--3d1e24, #3D1E24);
}

.p9rinuedy {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
  stop-opacity: 0;
}

.pclg_efwa {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pkh5xs8tl {
  d: path("M14.057 10.542c0-.289-.235-.481-.298-.54l-.288.28l.177.36z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pku9hacug {
  d: path("M18.405 10.529a.84.84 0 0 0-.232-.463l-.26.285l.118.229z");
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

.q4mowll4q {
  stop-color: var(--svg-color--e2d2f8, #E2D2F8);
  stop-opacity: 0;
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qctpdhrvn {
  d: path("M22.753 30.05V18.26c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07z");
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxb7siz6w {
  stop-color: var(--svg-color--3f282a, #3F282A);
}

.qxz6u5blh {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m15.658 5.182l-.066-.137a.66.66 0 0 0-.615-.419h-1.273c-1.846 0-3.342 1.513-3.342 3.38v.275c-.34-.26-.767-.805-.767-1.688c0-1.072.781-1.614 1.28-1.96c.14-.097.26-.179.33-.253l.1-.104c.35-.371.973-1.032 2.06-1.32a5.5 5.5 0 0 1 1.508-.165c.473.011.806.42.806.892v1.485z");
}

.r-0tl8b_g {
  stop-color: var(--svg-color--bfa7d3, #BFA7D3);
}

.r1tra0r1f {
  stop-color: var(--svg-color--a4c098, #A4C098);
  stop-opacity: 0;
}

.r3q9_wiir {
  d: path("M19.865 16.343a10.5 10.5 0 0 1 2.878 1.917v.014l.01-.014c1.29 1.21 2.3 2.76 2.86 4.53l.03.08c.52 1.66.79 3.38.79 5.11v2.07H15.98v-6.52z");
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.rced3uh7f {
  stop-color: var(--svg-color--b8e0ff, #B8E0FF);
  stop-opacity: 0;
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.rsfdnufmx {
  stop-color: var(--svg-color--b64118, #B64118);
}

.ry-6rkb7q {
  stop-color: var(--svg-color--e6d7e3, #E6D7E3);
}

.ry0u1-aml {
  d: path("m20.638 8.448l-.029-.63c-.01-.764-.641-1.394-1.405-1.426h-1.4c-.89 0-1.7-.486-2.124-1.26c0 0-.059-.136-.12-.368c-.257-.97.67-1.713 1.655-1.522c.974.19 2.083.517 2.903 1.052c1.744 1.138 1.439 3.189.52 4.154");
}

.s44sum5km {
  stop-color: var(--svg-color--c0f07e, #C0F07E);
  stop-opacity: 0;
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.sfa02aclf {
  stop-color: var(--svg-color--bcebff, #BCEBFF);
  stop-opacity: 0;
}

.sfpaimhix {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
  stop-opacity: 0;
}

.su72xqoac {
  d: path("M15.466 15.41c-2.75 0-5.32 1.06-7.23 2.85v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h21.79l.01-2.03c.01-1.76-.25-3.51-.77-5.18c-.57-1.81-1.59-3.38-2.91-4.61a10.62 10.62 0 0 0-7.2-2.82");
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.t0qf5rbqk {
  stop-color: var(--svg-color--e6d2de, #E6D2DE);
}

.t1h65cb3y {
  d: path("M17.544 9.943c.064.085-.07.188-.22.301c-.152.113-.264.193-.327.108c-.064-.085.007-.246.158-.359s.325-.135.39-.05");
}

.tq9nmh6wg {
  d: path("M26.434 23.02c.56 0 1.02.46 1.02 1.02v2.34h-2.04v-2.34c.01-.56.46-1.02 1.02-1.02");
}

.tsloro5fn {
  stop-color: var(--svg-color--e6ff81, #E6FF81);
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.txsyviqti {
  stop-color: var(--svg-color--aa9fa6, #AA9FA6);
  stop-opacity: 0;
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.u1e-wkoxo {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m15.024 10.474l-.59 1.838c-.101.379.14.757.484.757h.732c.343 0 .585-.384.484-.757l-.495-1.838c-.105-.407-.504-.407-.615 0");
}

.u1ex21b5h {
  d: path("M10.565 12.047a1.64 1.64 0 0 1-.905-.309v.931c0 .894.532 1.69 1.34 2.02a4.1 4.1 0 0 1-.345-1.18z");
}

.ubsir5m6c {
  stop-color: var(--svg-color--ccff86, #CCFF86);
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.ur8e5kbgj {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
  stop-opacity: 0;
}

.v0fk_zbwr {
  stop-color: var(--svg-color--83b651, #83B651);
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.v4-zmrbyl {
  stop-color: var(--svg-color--b0a6b5, #B0A6B5);
}

.v6ge5bcpf {
  stop-color: var(--svg-color--faf8fe, #FAF8FE);
}

.v7gluqbxb {
  d: path("M15.466 15.36h-.04c.1 0 .19 0 .3.01c-.09-.01-.18-.01-.26-.01");
}

.vxc_33b_r {
  d: path("M20.28 4.154c.515.177.976.537 1.268 1.052a2.37 2.37 0 0 1-.106 2.526a1.56 1.56 0 0 0-.27.874v1.188a1.7 1.7 0 0 0-.668-.268l.079-1.606a1.45 1.45 0 0 0-1.38-1.432h-1.4a2.42 2.42 0 0 1-2.211-1.443a.66.66 0 0 0-.615-.419h-1.273c-1.846 0-3.342 1.513-3.342 3.38l.031 1.537c-.254.037-.52.122-.72.264v-1.2a1.56 1.56 0 0 0-.27-.875a2.39 2.39 0 0 1-.144-2.446a2.34 2.34 0 0 1 1.3-1.126a2.68 2.68 0 0 0 1.384-1.11a2.325 2.325 0 0 1 2.89-.912a1.5 1.5 0 0 0 1.194 0c.28-.118.588-.188.912-.188c.843 0 1.58.456 1.989 1.132c.308.51.79.88 1.352 1.072");
}

.vxd8ts5kx {
  stop-color: var(--svg-color--c4c1c3, #C4C1C3);
}

.w01lnqx9a {
  stop-color: var(--svg-color--bfa6da, #BFA6DA);
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

.wj3drmbex {
  stop-color: var(--svg-color--2e1c1e, #2E1C1E);
}

.wj9mtgody {
  stop-color: var(--svg-color--533531, #533531);
  stop-opacity: 0;
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x2pnnabxt {
  d: path("M10.34 9.599a.956.956 0 0 0 .084 1.88a78 78 0 0 1-.084-1.88");
}

.x3hlfcbwc {
  stop-color: var(--svg-color--bdbabb, #BDBABB);
}

.x3pdtmzbl {
  stop-color: var(--svg-color--29615d, #29615D);
}

.x5t80dq2u {
  stop-color: var(--svg-color--3e5b48, #3E5B48);
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.xazl-5b3q {
  d: path("M15.426 18.68a2.11 2.11 0 0 1-2.11-2.11v-1.39h4.22v1.39c0 1.17-.95 2.11-2.11 2.11");
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xerdc-bkq {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M14.075 13.299a.23.23 0 0 0-.272.046a.21.21 0 0 0-.023.271c.349.528.955.88 1.646.88a1.97 1.97 0 0 0 1.646-.88a.214.214 0 0 0-.024-.273a.23.23 0 0 0-.27-.044h-.002c-.39.203-.85.32-1.35.32a2.9 2.9 0 0 1-1.351-.32Z");
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.xn9ioi9ep {
  fill: var(--svg-color--202020, #202020);
  d: path("M12.015 8.053a2.77 2.77 0 0 1 1.739-.36a.277.277 0 1 1-.068.55a2.22 2.22 0 0 0-1.386.285a1 1 0 0 0-.092.06l-.003.002a.277.277 0 0 1-.34-.438z");
}

.xoi7hsb-w {
  stop-color: var(--svg-color--ddcef1, #DDCEF1);
}

.xpzhm0iru {
  stop-color: var(--svg-color--cec5ca, #CEC5CA);
}

.xu2szrbjd {
  d: path("M11.114 16.343a10.5 10.5 0 0 0-2.878 1.917v.014l-.01-.014c-1.29 1.21-2.3 2.76-2.86 4.53l-.03.08c-.52 1.66-.79 3.38-.79 5.11v2.07h10.453v-6.52z");
}

.xx10debny {
  stop-color: var(--svg-color--c0a9d9, #C0A9D9);
  stop-opacity: 0;
}

.y5gxirbqq {
  stop-color: var(--svg-color--fffbff, #FFFBFF);
}

.z_a2ribdx {
  stop-color: var(--svg-color--e7d3df, #E7D3DF);
  stop-opacity: 0;
}

.z4n2hhy8u {
  opacity: var(--svg-opacity--0-6, 0.6);
}

.z4xhuybyb {
  stop-color: var(--svg-color--c8c2cc, #C8C2CC);
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.z78o0obou {
  stop-color: var(--svg-color--c6a5e0, #C6A5E0);
}

.zdypug-8z {
  stop-color: var(--svg-color--2b1820, #2B1820);
}

.zehc2bc2m {
  d: path("m9.608 17.174l-.13 1.733a.6.6 0 0 0 .493.636l.48.085a.15.15 0 0 1 .084.248l-.626.691a.5.5 0 0 0 .015.687l4.732 4.807a.2.2 0 0 0 .343-.14v-3.38c0-.282-.06-.562-.176-.82l-2.605-5.803c-.93.299-1.807.723-2.61 1.256");
}

.zk5cvukoj {
  stop-color: var(--svg-color--675655, #675655);
  stop-opacity: 0;
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zpmhxsbxd {
  stop-color: var(--svg-color--c7aae2, #C7AAE2);
  stop-opacity: 0;
}

.zrtk-0btq {
  d: path("m21.02 18.204l.115 1.533a.53.53 0 0 1-.437.563l-.424.075a.133.133 0 0 0-.076.22l.554.612a.44.44 0 0 1-.012.607l-4.188 4.254a.177.177 0 0 1-.303-.124v-2.99c0-.25.053-.498.155-.726l2.306-5.135a9.4 9.4 0 0 1 2.31 1.11");
}

.ztn-0pg6n {
  d: path("m21.37 17.174l.132 1.733a.6.6 0 0 1-.494.636l-.48.085a.15.15 0 0 0-.085.248l.626.691a.5.5 0 0 1-.014.687l-4.732 4.807a.2.2 0 0 1-.343-.14v-3.38c0-.282.06-.562.175-.82l2.606-5.803c.929.299 1.807.723 2.61 1.256");
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
