<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ie5ybdd)" class="ris4zbcww"/><path fill="url(#iFs8x3c)" class="pa44uorzy"/><path fill="url(#iDtMJPd)" class="pa44uorzy"/><g filter="url(#i5f7W1N)"><path fill="url(#iRUQFuA)" class="txflnfjuw"/><path fill="url(#iMVVm5c)" class="txflnfjuw"/></g><path class="cm4fmf3_y"/><path fill="url(#iCHgfYc)" class="l9ee6nb0e"/><path fill="url(#iwfggmj)" class="j2km41bzo"/><path fill="url(#iRhXhqc)" class="j2km41bzo"/><path fill="url(#iALKSDc)" class="leuf9sauo"/><path fill="url(#iP2Hvba)" class="leuf9sauo"/><g filter="url(#ivtpQTp)"><path fill="url(#i5mGxtl)" class="z-7tj_h3r"/><path fill="url(#iWWiqVc)" class="z-7tj_h3r"/><path fill="url(#iXjSJye)" class="z-7tj_h3r"/></g><path fill="url(#iTynXDq)" class="z-7tj_h3r"/><path fill="url(#iJgYxTb)" class="z-7tj_h3r"/><path fill="url(#iMpxC9c)" class="getcacc0o"/><path fill="url(#itNDY9n)" class="qpzzpebjw"/><path fill="url(#ihv7Yvc)" class="qpzzpebjw"/><path fill="url(#iLPDeKe)" class="ya-1vfowe"/><path fill="url(#iaDupSG)" class="ya-1vfowe"/><g filter="url(#iTLSDFG)"><path fill="url(#iY1MAqc)" class="tiq3j9qxy"/></g><path fill="url(#iXL2DWc)" class="i-vq35b-c"/><path fill="url(#iQPlnte)" class="i-vq35b-c"/><path fill="url(#iuKsYfd)" class="i-vq35b-c"/><path fill="url(#ipayw1c)" class="i-vq35b-c"/><g filter="url(#i3dUO9b)"><path fill="url(#ivI0HOd)" class="tbu3unbef"/></g><path fill="url(#iCNteWb)" class="dk4xvv5-b"/><path fill="url(#i10Ekjz)" class="dk4xvv5-b"/><path fill="url(#inVcylv)" class="b8oigeb5i"/><path fill="url(#ieFNJzc)" class="a7-bqfbyr"/><path fill="url(#i2WQNHd)" class="a7-bqfbyr"/><path fill="url(#iPFNhJb)" class="a7-bqfbyr"/><path fill="url(#ih8UXud)" class="a7-bqfbyr"/><path fill="url(#i5mLR3d)" class="a7-bqfbyr"/><g filter="url(#i5pMKCd)"><path class="gfb6ihb5l"/></g><g filter="url(#iP8P6en)"><path fill="url(#iztGjPb)" class="vidx7_6lw"/></g><g filter="url(#i87rFFd)"><path fill="url(#iM3a2tJ)" class="u-kx8qjfv"/></g><path fill="url(#iaZucLn)" class="u-kx8qjfv"/><path fill="url(#iXFuPVd)" class="u-kx8qjfv"/><path fill="url(#iQDYkPd)" class="u-kx8qjfv"/><path fill="url(#imPSNyb)" class="u-kx8qjfv"/><path fill="url(#iYx6R9b)" class="u-kx8qjfv"/><g filter="url(#iqAL0Wd)"><path class="cf28mtbaf"/></g><g filter="url(#icSbmzw)"><path class="pqwgsffdo"/><path fill="url(#ilChuRd)" class="qt3yiofev"/><path fill="url(#i6j0lec)" class="qt3yiofev"/><path fill="url(#ijSa3lx)" class="qt3yiofev"/><path fill="url(#iQ6QiRd)" class="qt3yiofev"/><path fill="url(#ikcmtHe)" class="qt3yiofev"/></g><g filter="url(#iDbwHZb)"><path stroke="url(#iHgpfsd)" class="c-12gcc3n"/></g><path class="m6ls0kv6u"/><path fill="url(#ieH7ygb)" class="wuonwfy3p"/><path fill="url(#ixtcX4c)" class="wuonwfy3p"/><path fill="url(#iafQmKd)" class="c-rau6psn"/><path fill="url(#i4qNnzb)" class="c-rau6psn"/><path fill="url(#iyZZy9d)" class="iwyjp3bzl"/><path fill="url(#inpGiKb)" class="iwyjp3bzl"/><path fill="url(#iNy2gpb)" class="iwyjp3bzl"/><g filter="url(#iIutl0b)"><path class="gm26ipb5u"/></g><path class="y4ttqibxw"/><path fill="url(#iilZaVb)" class="p-ay64wcm"/><path class="gk8wqabxd"/><g filter="url(#iuKqRFb)"><path class="bzqk1ib9o"/><path fill="url(#itiiDRd)" class="u_dfs4d2m"/></g><g filter="url(#i3OHxhe)"><path fill="url(#id6M5we)" class="mhv_y3b6k"/></g><path class="zso009b_h"/><path fill="url(#ieeqLDe)" class="aavxil_wd"/><path class="smdfnv1yk"/><g filter="url(#i58ClTc)"><path fill="url(#iwUr9kf)" class="m8uu_ox5v"/></g><g filter="url(#iBDzKii)"><ellipse transform="rotate(-27.914 13.51 9.873)" class="f5y8e2b5f"/><ellipse fill="url(#i8SOJkb)" transform="rotate(-27.914 13.51 9.873)" class="kh-vytb5g"/></g><g filter="url(#itopuxe)"><path fill="url(#iJIk3uM)" class="rg3gb5b2x"/><path fill="url(#iwQ8Ode)" class="rg3gb5b2x"/><path fill="url(#irW7BIc)" class="rg3gb5b2x"/><path fill="url(#inbZ3we)" class="rg3gb5b2x"/><path fill="url(#iM97O2d)" class="rg3gb5b2x"/></g><g filter="url(#ihJpucc)"><path stroke="url(#i16b61b)" class="wmgsz54km"/></g><g filter="url(#iV5cdGw)"><path stroke="url(#i5m3wFg)" class="rfgguobud"/></g><g filter="url(#i9j1Btp)"><path stroke="url(#iDCWWxd)" class="qerlyfbcx"/></g><g filter="url(#iFHnwkC)"><path clip-rule="evenodd" class="goa0n2bcm"/></g><g filter="url(#iZOhWDZ)"><path clip-rule="evenodd" class="jfgc20bja"/></g><g filter="url(#iKB2epd)"><path class="ayvvxxi-n"/></g><g filter="url(#idECEtf)"><path class="zlungxbgo"/></g><defs><radialGradient id="ie5ybdd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.28126 -2.7131 2.52682 -3.98732 19.818 3.96)" gradientUnits="userSpaceOnUse"><stop class="lgo9yub8v"/><stop offset="1" class="ltcbfxk7p"/></radialGradient><radialGradient id="iFs8x3c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.15625 8.40625 0 19.693 5.122)" gradientUnits="userSpaceOnUse"><stop class="ya4lejb1r"/><stop offset="1" class="r9exlwbyv"/></radialGradient><radialGradient id="iMVVm5c" cx="0" cy="0" r="1" gradientTransform="rotate(-115.388 9.61 3.916)scale(4.08169 6.42739)" gradientUnits="userSpaceOnUse"><stop class="yc_s6bd2r"/><stop offset="1" class="e2_jykbzy"/></radialGradient><radialGradient id="iCHgfYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.16424 -8.99366 0 15.93 16.285)" gradientUnits="userSpaceOnUse"><stop offset=".53" class="oolzzy49q"/><stop offset="1" class="kc6n1tb_x"/></radialGradient><radialGradient id="iRhXhqc" cx="0" cy="0" r="1" gradientTransform="matrix(2.6875 .4375 -2.13811 13.1341 3.787 25.247)" gradientUnits="userSpaceOnUse"><stop class="d6r03hc-n"/><stop offset="1" class="h29l8x_8c"/></radialGradient><radialGradient id="iP2Hvba" cx="0" cy="0" r="1" gradientTransform="matrix(.79488 -.01787 .1758 7.81887 22.96 24.71)" gradientUnits="userSpaceOnUse"><stop offset=".249" class="dz1f1dx9q"/><stop offset="1" class="a2gn4iuzk"/></radialGradient><radialGradient id="i5mGxtl" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.49005 -3.73669 0 16 16.153)" gradientUnits="userSpaceOnUse"><stop offset=".232" class="w6969eyte"/><stop offset="1" class="nb487cbvy"/></radialGradient><radialGradient id="iXjSJye" cx="0" cy="0" r="1" gradientTransform="matrix(-2.27543 1.55452 -.96733 -1.41593 15.145 19.551)" gradientUnits="userSpaceOnUse"><stop class="zif_-obqz"/><stop offset="1" class="j3eudux9e"/></radialGradient><radialGradient id="iJgYxTb" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.28924 -4.48731 0 15.393 15.97)" gradientUnits="userSpaceOnUse"><stop offset=".344" class="rs3k7gc8p"/><stop offset=".987" class="zm4f_vbug"/></radialGradient><radialGradient id="iMpxC9c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.58005 5.35185 0 15.92 19.652)" gradientUnits="userSpaceOnUse"><stop offset=".027" class="h7qlxhb-a"/><stop offset=".737" class="wly33_qqy"/></radialGradient><radialGradient id="itNDY9n" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.2121 -3.45057 0 15.93 16.245)" gradientUnits="userSpaceOnUse"><stop class="o-v48ln2d"/><stop offset=".799" class="zh1uzn9mk"/></radialGradient><radialGradient id="ihv7Yvc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.42846 -2.39851 0 15.93 15.33)" gradientUnits="userSpaceOnUse"><stop offset=".668" class="uhy930l9u"/><stop offset="1" class="kpp268b5e"/></radialGradient><radialGradient id="iaDupSG" cx="0" cy="0" r="1" gradientTransform="matrix(-3.64175 0 0 -2.53212 12.7 10.59)" gradientUnits="userSpaceOnUse"><stop offset=".866" class="srn41o2oz"/><stop offset=".972" class="dfc36bbxx"/></radialGradient><radialGradient id="iY1MAqc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.47656 .18752 -.0868 -1.14638 12.387 10.59)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><radialGradient id="iQPlnte" cx="0" cy="0" r="1" gradientTransform="rotate(58.678 .422 21.395)scale(3.13534 5.04105)" gradientUnits="userSpaceOnUse"><stop offset=".793" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="iuKsYfd" cx="0" cy="0" r="1" gradientTransform="rotate(-33.074 27.289 -27.216)scale(2.07337 1.66975)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="ipayw1c" cx="0" cy="0" r="1" gradientTransform="matrix(1.29458 -1.62268 3.19197 2.54657 19.526 10.662)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="iCNteWb" cx="0" cy="0" r="1" gradientTransform="matrix(1.03903 -.98438 2.30833 2.4365 20.398 8.45)" gradientUnits="userSpaceOnUse"><stop offset=".269" class="rb2mtukpy"/><stop offset=".879" class="u4h3exu9c"/></radialGradient><radialGradient id="i10Ekjz" cx="0" cy="0" r="1" gradientTransform="matrix(1.97272 .98047 -.09594 .19302 19.898 7.15)" gradientUnits="userSpaceOnUse"><stop class="qf5kn-bed"/><stop offset="1" class="gir6ssbjp"/></radialGradient><radialGradient id="inVcylv" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1641 -.71876 .94072 -1.52358 11.602 8.778)" gradientUnits="userSpaceOnUse"><stop offset=".521" class="fuhh3957a"/><stop offset=".94" class="tsc202y0r"/></radialGradient><radialGradient id="i2WQNHd" cx="0" cy="0" r="1" gradientTransform="rotate(154.069 9.531 11.785)scale(3.78757 11.2112)" gradientUnits="userSpaceOnUse"><stop class="ium6abcxp"/><stop offset="1" class="h7lqrlw1r"/></radialGradient><radialGradient id="i5mLR3d" cx="0" cy="0" r="1" gradientTransform="matrix(2.5033 -1.90625 3.00378 3.94458 8.94 18.81)" gradientUnits="userSpaceOnUse"><stop class="g3ev-1bmq"/><stop offset="1" class="hdbb6nacd"/></radialGradient><radialGradient id="iM3a2tJ" cx="0" cy="0" r="1" gradientTransform="matrix(-5.9544 1.19435 -2.01845 -10.06296 19.451 10.381)" gradientUnits="userSpaceOnUse"><stop offset=".248" class="s2aq-7bkx"/><stop offset="1" class="w39e-ubuo"/></radialGradient><radialGradient id="iaZucLn" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.13592 1.13266 0 14.095 9.653)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="vgks6xbbq"/><stop offset="1" class="o2h54cbxy"/></radialGradient><radialGradient id="iXFuPVd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.04388 1.15848 0 18.427 9.458)" gradientUnits="userSpaceOnUse"><stop offset=".313" class="hdonfccjk"/><stop offset="1" class="dmh0gtb6x"/></radialGradient><radialGradient id="iQDYkPd" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.73704 -10.9444 0 16 8.459)" gradientUnits="userSpaceOnUse"><stop offset=".633" class="h7v8xj0og"/><stop offset="1" class="qvn3d4blm"/></radialGradient><radialGradient id="imPSNyb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.6875 3.6875 0 15.813 17.552)" gradientUnits="userSpaceOnUse"><stop class="qmlvydbxi"/><stop offset="1" class="hrzgmt_rb"/></radialGradient><radialGradient id="iYx6R9b" cx="0" cy="0" r="1" gradientTransform="rotate(137.827 8.077 6.841)scale(3.58407 2.1419)" gradientUnits="userSpaceOnUse"><stop offset=".121" class="jzg39_bqw"/><stop offset="1" class="n-jpw1buj"/></radialGradient><radialGradient id="i6j0lec" cx="0" cy="0" r="1" gradientTransform="matrix(0 .22684 -.76458 0 16.465 12.237)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="iQ6QiRd" cx="0" cy="0" r="1" gradientTransform="rotate(156.852 7.091 7.552)scale(1.64873 2.52797)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="ieH7ygb" cx="0" cy="0" r="1" gradientTransform="rotate(140.585 9.628 16.862)scale(2.13884 2.10129)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="kieesbm_x"/><stop offset="1" class="w58utkb1j"/></radialGradient><radialGradient id="ixtcX4c" cx="0" cy="0" r="1" gradientTransform="rotate(-37.286 48.766 -28.99)scale(.99065 .51735)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="hmj-ymbzq"/><stop offset="1" class="ekxsm__ep"/></radialGradient><radialGradient id="i4qNnzb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.85126 .74829 0 26.113 24.77)" gradientUnits="userSpaceOnUse"><stop class="j2-8_acvh"/><stop offset="1" class="x6aj7b3cp"/></radialGradient><radialGradient id="iyZZy9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.82813 1.14062 0 26.137 21.59)" gradientUnits="userSpaceOnUse"><stop class="ag_y78bhq"/><stop offset="1" class="r_2nh8m3w"/></radialGradient><radialGradient id="inpGiKb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.14844 2.01125 0 25.638 21.973)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="isjnp_l6m"/><stop offset="1" class="y9bk_9fsc"/></radialGradient><radialGradient id="iilZaVb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .82316 -1.30932 0 18.214 9.97)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="itiiDRd" cx="0" cy="0" r="1" gradientTransform="matrix(-.2353 -.30322 .41746 -.32395 17.982 10.055)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ieeqLDe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8232 -1.30939 0 13.786 9.97)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="i8SOJkb" cx="0" cy="0" r="1" gradientTransform="matrix(-.00785 -.5013 .60257 -.00943 13.495 10.192)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iwQ8Ode" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8017 -1.35439 0 25.892 25.285)" gradientUnits="userSpaceOnUse"><stop offset=".106" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="irW7BIc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .85938 -1.45182 0 25.892 26.579)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="inbZ3we" cx="0" cy="0" r="1" gradientTransform="matrix(0 .71875 -1.21425 0 25.892 27.829)" gradientUnits="userSpaceOnUse"><stop offset=".109" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><radialGradient id="iM97O2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .79938 -1.7273 0 25.892 29.18)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="r0i0_6b9f"/><stop offset="1" class="dcb4tlblp"/></radialGradient><linearGradient id="iDtMJPd" x1="15.92" x2="15.92" y1="4.01" y2="4.063" gradientUnits="userSpaceOnUse"><stop class="xjz9wom2l"/><stop offset="1" class="pqe0dnzfz"/></linearGradient><linearGradient id="iRUQFuA" x1="16" x2="16" y1="4.809" y2="14.841" gradientUnits="userSpaceOnUse"><stop class="ws6qwsbwq"/><stop offset="1" class="ddiuouxdx"/></linearGradient><linearGradient id="iwfggmj" x1="8.94" x2="5.35" y1="28.434" y2="28.434" gradientUnits="userSpaceOnUse"><stop class="es32odbdd"/><stop offset="1" class="wevrdub6o"/></linearGradient><linearGradient id="iALKSDc" x1="26.503" x2="22.96" y1="22.864" y2="29.17" gradientUnits="userSpaceOnUse"><stop class="kcb1h97-p"/><stop offset="1" class="c6jm60b1r"/></linearGradient><linearGradient id="iWWiqVc" x1="20" x2="19.066" y1="18.497" y2="18.497" gradientUnits="userSpaceOnUse"><stop class="lzh17ac1w"/><stop offset="1" class="yrr42qhfr"/></linearGradient><linearGradient id="iTynXDq" x1="12" x2="12.334" y1="18.497" y2="18.497" gradientUnits="userSpaceOnUse"><stop offset=".143" class="pescu9bef"/><stop offset="1" class="fl69hubql"/></linearGradient><linearGradient id="iLPDeKe" x1="10.649" x2="13.77" y1="10.725" y2="10.151" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="iXL2DWc" x1="22.49" x2="21.757" y1="9.982" y2="12.768" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="ivI0HOd" x1="20.82" x2="20.82" y1="9.427" y2="11.753" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><linearGradient id="ieFNJzc" x1="17.162" x2="15.95" y1="29.122" y2="21.997" gradientUnits="userSpaceOnUse"><stop class="h3q0cq17v"/><stop offset="1" class="zykvaibcy"/></linearGradient><linearGradient id="iPFNhJb" x1="23.014" x2="22.787" y1="29.653" y2="29.653" gradientUnits="userSpaceOnUse"><stop class="w-ul8jbeq"/><stop offset="1" class="vtbjbdc7x"/></linearGradient><linearGradient id="ih8UXud" x1="8.94" x2="9.064" y1="29.653" y2="29.653" gradientUnits="userSpaceOnUse"><stop class="w-ul8jbeq"/><stop offset="1" class="vtbjbdc7x"/></linearGradient><linearGradient id="iztGjPb" x1="13.787" x2="20.318" y1="28.341" y2="28.341" gradientUnits="userSpaceOnUse"><stop class="ym_13nbvu"/><stop offset="1" class="kehse99iu"/></linearGradient><linearGradient id="ilChuRd" x1="16.835" x2="16" y1="11.6" y2="11.637" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="ijSa3lx" x1="16" x2="16" y1="12.659" y2="12.226" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="ikcmtHe" x1="16" x2="16" y1="10.145" y2="10.653" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="iHgpfsd" x1="14.559" x2="14.855" y1="14.251" y2="13.669" gradientUnits="userSpaceOnUse"><stop offset=".008" class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="iafQmKd" x1="25.61" x2="25.61" y1="21.591" y2="24.77" gradientUnits="userSpaceOnUse"><stop class="rl_kfsb7q"/><stop offset=".997" class="va-kb9bvg"/></linearGradient><linearGradient id="iNy2gpb" x1="25.638" x2="25.638" y1="22.294" y2="21.7" gradientUnits="userSpaceOnUse"><stop class="lmnxagbed"/><stop offset="1" class="ztn8dybrr"/></linearGradient><linearGradient id="id6M5we" x1="19.003" x2="18.685" y1="10.024" y2="10.22" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iwUr9kf" x1="14.541" x2="14.223" y1="10.024" y2="10.221" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iJIk3uM" x1="27.483" x2="23.454" y1="28.043" y2="28.043" gradientUnits="userSpaceOnUse"><stop offset=".146" class="pxu01k21v"/><stop offset=".861" class="fusa66-jk"/></linearGradient><linearGradient id="i16b61b" x1="23.975" x2="25.684" y1="26.036" y2="26.036" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="i5m3wFg" x1="23.896" x2="25.606" y1="27.341" y2="27.341" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><linearGradient id="iDCWWxd" x1="23.975" x2="25.684" y1="28.645" y2="28.645" gradientUnits="userSpaceOnUse"><stop class="lf8a5e78i"/><stop offset="1" class="ar7lpj8pp"/></linearGradient><filter id="i5f7W1N" width="20.537" height="10.328" x="5.481" y="4.809" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.384314 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1806"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.388235 0 0 0 0 0.243137 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1806" result="effect2_innerShadow_4002_1806"/></filter><filter id="ivtpQTp" width="8" height="6.44" x="12" y="15.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.47451 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1806"/></filter><filter id="iTLSDFG" width="2.74" height="2.74" x="9.66" y="9.22" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1806" stdDeviation=".125"/></filter><filter id="i3dUO9b" width="3.327" height="3.327" x="19.157" y="8.927" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1806" stdDeviation=".25"/></filter><filter id="i5pMKCd" width="8.45" height="4.612" x="11.73" y="25.56" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1806" stdDeviation=".125"/></filter><filter id="iP8P6en" width="8.05" height="4.28" x="11.88" y="25.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.258824 0 0 0 0 0.67451 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1806"/></filter><filter id="i87rFFd" width="10.66" height="10.004" x="10.92" y="6.982" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.34902 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1806"/></filter><filter id="iqAL0Wd" width="3.871" height="4.695" x="13.872" y="9.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1806" stdDeviation=".5"/></filter><filter id="icSbmzw" width="2.271" height="3.095" x="14.865" y="9.825" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1806" stdDeviation=".1"/></filter><filter id="iDbwHZb" width="3.833" height="1.572" x="14.023" y="13.108" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1806" stdDeviation=".05"/></filter><filter id="iIutl0b" width="7.625" height="9.853" x="21.853" y="10.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.529412 0 0 0 0 0.470588 0 0 0 0 0.588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1806"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.776471 0 0 0 0 0.796078 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1806" result="effect2_innerShadow_4002_1806"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.517647 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_4002_1806" result="effect3_innerShadow_4002_1806"/></filter><filter id="iuKqRFb" width=".795" height=".703" x="17.47" y="9.525" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1806" stdDeviation=".05"/></filter><filter id="i3OHxhe" width=".898" height=".921" x="18.324" y="9.602" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1806" stdDeviation=".1"/></filter><filter id="i58ClTc" width=".995" height="1.05" x="13.816" y="9.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1806" stdDeviation=".1"/></filter><filter id="iBDzKii" width=".923" height=".712" x="13.049" y="9.517" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1806" stdDeviation=".05"/></filter><filter id="itopuxe" width="4.468" height="5.556" x="23.454" y="24.424" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.211765 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1806"/></filter><filter id="ihJpucc" width="2.097" height=".3" x="23.825" y="25.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1806" stdDeviation=".05"/></filter><filter id="iV5cdGw" width="2.097" height=".3" x="23.747" y="27.112" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1806" stdDeviation=".05"/></filter><filter id="i9j1Btp" width="2.097" height=".3" x="23.825" y="28.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1806" stdDeviation=".05"/></filter><filter id="iFHnwkC" width="2.573" height="1.468" x="12.133" y="7.316" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0784314 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1806"/></filter><filter id="iZOhWDZ" width="2.573" height="1.468" x="17.293" y="7.316" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0784314 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1806"/></filter><filter id="iKB2epd" width="2.123" height=".868" x="17.56" y="7.574" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1806" stdDeviation=".075"/></filter><filter id="idECEtf" width="2.123" height=".868" x="12.3" y="7.574" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1806" stdDeviation=".075"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-farmer-medium-dark" /></template>
<style>
.a2gn4iuzk {
  stop-color: var(--svg-color--28a96b, #28A96B);
  stop-opacity: 0;
}

.a7-bqfbyr {
  d: path("M22.96 18.04c-.63-.53-1.33-.99-2.07-1.36v5.9c0 .23-.18.41-.41.41h-9.07c-.23 0-.41-.18-.41-.41v-5.92c-.74.37-1.43.82-2.06 1.35v11.97h14.02z");
}

.aavxil_wd {
  d: path("M13.784 9.486a.906.906 0 0 0-.873 1.144h1.75a1 1 0 0 0 .033-.239a.91.91 0 0 0-.91-.905");
}

.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.ag_y78bhq {
  stop-color: var(--svg-color--c7c1cc, #C7C1CC);
}

.ar7lpj8pp {
  stop-color: var(--svg-color--7a4b42, #7A4B42);
  stop-opacity: 0;
}

.ayvvxxi-n {
  stroke: var(--svg-color--463c3b, #463C3B);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M19.483 8.242s-.6-.581-1.723-.448");
}

.b8oigeb5i {
  d: path("M10.508 7.72c.418-.64 1.996-.738 2.566-.738l-1.726 3.18h-.53c-.177 0-.35-.075-.433-.23c-.285-.528-.438-1.467.123-2.211");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bzqk1ib9o {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.15 9.677c.064.086-.071.192-.224.306c-.154.115-.267.195-.332.11c-.064-.087.008-.25.16-.365c.154-.114.33-.137.395-.05");
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
}

.c-12gcc3n {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.484 13.286c-.199-.106-.392.12-.276.301a2.07 2.07 0 0 0 1.732.943c.728 0 1.363-.38 1.732-.942a.2.2 0 0 0-.024-.256a.21.21 0 0 0-.25-.047l-.002.001a3.1 3.1 0 0 1-1.456.354a3.1 3.1 0 0 1-1.456-.354Z");
}

.c-rau6psn {
  d: path("M26.113 21.77h-1v3h1z");
}

.c6jm60b1r {
  stop-color: var(--svg-color--368d6e, #368D6E);
}

.cf28mtbaf {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m15.427 10.535l-.53 1.71c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cm4fmf3_y {
  fill: var(--svg-color--45bb85, #45BB85);
  d: path("M15.93 15.5c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.d6r03hc-n {
  stop-color: var(--svg-color--63c890, #63C890);
}

.dcb4tlblp {
  stop-color: var(--svg-color--986e66, #986E66);
  stop-opacity: 0;
}

.ddiuouxdx {
  stop-color: var(--svg-color--6d4b49, #6D4B49);
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dk4xvv5-b {
  d: path("M21.492 7.72c-.418-.64-1.996-.738-2.566-.738l1.726 3.18h.53c.177 0 .35-.075.433-.23c.286-.528.438-1.467-.123-2.211");
}

.dmh0gtb6x {
  stop-color: var(--svg-color--855450, #855450);
  stop-opacity: 0;
}

.dz1f1dx9q {
  stop-color: var(--svg-color--28a96b, #28A96B);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e2_jykbzy {
  stop-color: var(--svg-color--6e4f4b, #6E4F4B);
  stop-opacity: 0;
}

.ekxsm__ep {
  stop-color: var(--svg-color--93776e, #93776E);
  stop-opacity: 0;
}

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.es32odbdd {
  stop-color: var(--svg-color--399965, #399965);
}

.f5y8e2b5f {
  cx: 13.511px;
  cy: 9.873px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.395px;
  ry: 0.2px;
}

.fl69hubql {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
  stop-opacity: 0;
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.ft5dv1b6b {
  fill: none;
}

.fuhh3957a {
  stop-color: var(--svg-color--0d030b, #0D030B);
}

.fusa66-jk {
  stop-color: var(--svg-color--704b4b, #704B4B);
}

.g3ev-1bmq {
  stop-color: var(--svg-color--3da0db, #3DA0DB);
}

.getcacc0o {
  d: path("m16.85 19.69l-.65.58c-.16.14-.39.14-.55 0l-.65-.58a3.45 3.45 0 0 1-1.14-2.55v-3.09c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v3.09c0 .97-.41 1.9-1.13 2.55");
}

.gfb6ihb5l {
  fill: var(--svg-color--3661c6, #3661C6);
  d: path("M19.42 25.81h-6.94a.49.49 0 0 0-.5.492v3.62h7.95v-3.62a.513.513 0 0 0-.51-.492");
}

.gir6ssbjp {
  stop-color: var(--svg-color--3b3538, #3B3538);
  stop-opacity: 0;
}

.gk8wqabxd {
  fill: var(--svg-color--000, #000);
  d: path("M17.697 10.391c0-.288.23-.518.519-.518a.516.516 0 0 1 .46.757h-.917a.47.47 0 0 1-.062-.239");
}

.gm26ipb5u {
  fill: var(--svg-color--b8b1c0, #B8B1C0);
  d: path("M22.755 11.044a.6.6 0 0 0-.602.601v6.852a1.5 1.5 0 0 0 1.5 1.5h4.125a1.5 1.5 0 0 0 1.5-1.5v-6.852a.602.602 0 1 0-1.203 0v4.45a.879.879 0 0 1-1.758 0v-4.45a.602.602 0 1 0-1.203 0v4.45a.879.879 0 0 1-1.757 0v-4.45a.6.6 0 0 0-.602-.601");
}

.goa0n2bcm {
  fill: var(--svg-color--2c1c28, #2C1C28);
  fill-rule: evenodd;
  d: path("M12.85 8.668a.425.425 0 0 1-.587-.614l.296.305l-.296-.306h.001l.002-.002l.004-.004l.01-.01a1 1 0 0 1 .144-.113a2.3 2.3 0 0 1 .403-.227a2.85 2.85 0 0 1 1.505-.208a.425.425 0 0 1-.1.844a2 2 0 0 0-1.06.14a1.5 1.5 0 0 0-.312.187z");
}

.h29l8x_8c {
  stop-color: var(--svg-color--63c890, #63C890);
  stop-opacity: 0;
}

.h3q0cq17v {
  stop-color: var(--svg-color--3560c5, #3560C5);
}

.h7lqrlw1r {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
  stop-opacity: 0;
}

.h7qlxhb-a {
  stop-color: var(--svg-color--e9cee6, #E9CEE6);
}

.h7v8xj0og {
  stop-color: var(--svg-color--6f4354, #6F4354);
  stop-opacity: 0;
}

.hdbb6nacd {
  stop-color: var(--svg-color--3aa1e0, #3AA1E0);
  stop-opacity: 0;
}

.hdonfccjk {
  stop-color: var(--svg-color--855450, #855450);
}

.hmj-ymbzq {
  stop-color: var(--svg-color--93776e, #93776E);
}

.hrzgmt_rb {
  stop-color: var(--svg-color--6b4c57, #6B4C57);
  stop-opacity: 0;
}

.i-vq35b-c {
  d: path("M20.82 12.26a1.67 1.67 0 1 0 0-3.34a1.67 1.67 0 0 0 0 3.34");
}

.isjnp_l6m {
  stop-color: var(--svg-color--85808c, #85808C);
  stop-opacity: 0;
}

.ium6abcxp {
  stop-color: var(--svg-color--47b2f6, #47B2F6);
}

.iwyjp3bzl {
  d: path("M24.877 19.989H26.4v1.734a.25.25 0 0 1-.25.25h-1.023a.25.25 0 0 1-.25-.25z");
}

.j2-8_acvh {
  stop-color: var(--svg-color--88625f, #88625F);
}

.j2km41bzo {
  d: path("M8.94 29.98V18.01h-.006a10.95 10.95 0 0 0-3.994 8.47v3.5z");
}

.j3eudux9e {
  stop-color: var(--svg-color--519473, #519473);
  stop-opacity: 0;
}

.jfgc20bja {
  fill: var(--svg-color--2c1c28, #2C1C28);
  fill-rule: evenodd;
  d: path("M19.15 8.668a.425.425 0 0 0 .587-.614c-.493.51 0 0 0 0l-.001-.002l-.002-.001l-.004-.004l-.01-.01a1 1 0 0 0-.144-.113a2.3 2.3 0 0 0-.403-.227a2.85 2.85 0 0 0-1.505-.208a.425.425 0 0 0 .1.844c.477-.056.831.04 1.06.14a1.5 1.5 0 0 1 .312.187z");
}

.jzg39_bqw {
  stop-color: var(--svg-color--886764, #886764);
}

.kc6n1tb_x {
  stop-color: var(--svg-color--399967, #399967);
  stop-opacity: 0;
}

.kcb1h97-p {
  stop-color: var(--svg-color--63d591, #63D591);
}

.kehse99iu {
  stop-color: var(--svg-color--389dff, #389DFF);
}

.kh-vytb5g {
  cx: 13.511px;
  cy: 9.873px;
  rx: 0.395px;
  ry: 0.2px;
}

.kieesbm_x {
  stop-color: var(--svg-color--815f52, #815F52);
}

.kpp268b5e {
  stop-color: var(--svg-color--361b15, #361B15);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l9ee6nb0e {
  d: path("M15.93 15.5c-6.07 0-10.99 4.91-10.99 10.98v3.5h21.98v-3.5c0-6.07-4.92-10.98-10.99-10.98");
}

.leuf9sauo {
  d: path("M22.96 29.98V18.01h.006a10.95 10.95 0 0 1 3.994 8.47v3.5z");
}

.lf8a5e78i {
  stop-color: var(--svg-color--664139, #664139);
}

.lgo9yub8v {
  stop-color: var(--svg-color--7f5f58, #7F5F58);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmnxagbed {
  stop-color: var(--svg-color--89829d, #89829D);
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.ltcbfxk7p {
  stop-color: var(--svg-color--644841, #644841);
}

.lzh17ac1w {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m6ls0kv6u {
  fill: var(--svg-color--87024e, #87024E);
  d: path("M15.94 13.69c-.54 0-1.05-.13-1.48-.36c-.15-.08-.3.09-.21.23c.36.55.98.92 1.69.92s1.33-.37 1.69-.92c.09-.14-.07-.3-.21-.23c-.43.23-.94.36-1.48.36");
}

.m8uu_ox5v {
  d: path("M14.611 10.285c0-.293-.238-.488-.302-.547l-.292.283l.18.367z");
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mhv_y3b6k {
  d: path("M19.022 10.272a.85.85 0 0 0-.234-.47l-.264.29l.119.231z");
}

.n-jpw1buj {
  stop-color: var(--svg-color--886764, #886764);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nb487cbvy {
  stop-color: var(--svg-color--3d8f6c, #3D8F6C);
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.o-v48ln2d {
  stop-color: var(--svg-color--69424f, #69424F);
}

.o2h54cbxy {
  stop-color: var(--svg-color--70444c, #70444C);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oolzzy49q {
  stop-color: var(--svg-color--399967, #399967);
}

.p-ay64wcm {
  d: path("M18.216 9.486a.905.905 0 0 1 .872 1.144H17.34a.91.91 0 0 1 .877-1.144");
}

.pa44uorzy {
  d: path("m10.1 5.55l-.18.36h12l-.17-.33c-.3-.59-.68-1.11-1.12-1.57h-9.42c-.43.45-.81.97-1.11 1.54");
}

.pescu9bef {
  stop-color: var(--svg-color--6a9e7e, #6A9E7E);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pqe0dnzfz {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
  stop-opacity: 0;
}

.pqwgsffdo {
  fill: var(--svg-color--795147, #795147);
  d: path("m15.62 10.31l-.53 1.71c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.pxu01k21v {
  stop-color: var(--svg-color--976c5f, #976C5F);
}

.qerlyfbcx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.975 28.567h1.796");
}

.qf5kn-bed {
  stop-color: var(--svg-color--3b3538, #3B3538);
}

.qmlvydbxi {
  stop-color: var(--svg-color--6b4c57, #6B4C57);
}

.qpzzpebjw {
  d: path("M15.93 18.67c-1.14 0-2.06-.92-2.06-2.06v-2.56c0-1.14.92-2.06 2.06-2.06s2.06.92 2.06 2.06v2.56a2.07 2.07 0 0 1-2.06 2.06");
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qt3yiofev {
  d: path("m15.62 10.31l-.53 1.71c-.11.35.15.7.52.7h.78c.37 0 .63-.35.52-.7l-.52-1.71a.403.403 0 0 0-.77 0");
}

.qvn3d4blm {
  stop-color: var(--svg-color--604145, #604145);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.r_2nh8m3w {
  stop-color: var(--svg-color--a099a8, #A099A8);
}

.r0i0_6b9f {
  stop-color: var(--svg-color--947068, #947068);
}

.r9exlwbyv {
  stop-color: var(--svg-color--4f3b60, #4F3B60);
}

.rb2mtukpy {
  stop-color: var(--svg-color--10080c, #10080C);
}

.rfgguobud {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.897 27.263h1.796");
}

.rg3gb5b2x {
  d: path("M23.455 25.306a.73.73 0 0 1 .726-.732h2.391a1.2 1.2 0 0 1 1.2 1.2v3.206a1 1 0 0 1-1 1h-2.591a.731.731 0 0 1-.32-1.389a.735.735 0 0 1 0-1.314a.735.735 0 0 1 0-1.314a.74.74 0 0 1-.407-.657");
}

.ris4zbcww {
  d: path("M21.92 5.91h-12l.18-.36a6.549 6.549 0 0 1 11.65.03z");
}

.rl_kfsb7q {
  stop-color: var(--svg-color--784853, #784853);
}

.rs3k7gc8p {
  stop-color: var(--svg-color--2a5923, #2A5923);
}

.s2aq-7bkx {
  stop-color: var(--svg-color--95685b, #95685B);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.smdfnv1yk {
  fill: var(--svg-color--000, #000);
  d: path("M14.303 10.391a.516.516 0 0 0-.519-.518a.516.516 0 0 0-.461.757h.918a.5.5 0 0 0 .062-.239");
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.tbu3unbef {
  d: path("M20.82 11.753a1.163 1.163 0 1 0 0-2.326a1.163 1.163 0 0 0 0 2.326");
}

.tiq3j9qxy {
  d: path("M11.03 11.71a1.12 1.12 0 1 0 0-2.24a1.12 1.12 0 0 0 0 2.24");
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.tsc202y0r {
  stop-color: var(--svg-color--3f3532, #3F3532);
}

.txflnfjuw {
  d: path("M11.564 4.81c-.85.03-2.678.228-4.102 1.335c-1.238.963-1.477 2.117-1.477 3.086v.477c-.093 1.781 1.446 4.93 6.883 4.93h6.264c5.437 0 6.976-3.149 6.883-4.93V9.23c0-.969-.24-2.123-1.477-3.086c-1.423-1.107-3.252-1.304-4.101-1.336z");
}

.u_dfs4d2m {
  d: path("M18.15 9.677c.064.086-.071.192-.224.306c-.154.115-.267.195-.332.11c-.064-.087.008-.25.16-.365c.154-.114.33-.137.395-.05");
}

.u-kx8qjfv {
  d: path("M19.082 6.982h-6.168c-1.127 0-2.086 1.008-1.987 2.126l.184 4.942c.168 1.71 1.532 2.936 3.193 2.936h3.394c1.661 0 3.026-1.226 3.194-2.936l.187-5.04c.04-1.078-.91-2.028-1.997-2.028");
}

.u4h3exu9c {
  stop-color: var(--svg-color--2a2627, #2A2627);
}

.uhy930l9u {
  stop-color: var(--svg-color--361b15, #361B15);
  stop-opacity: 0;
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.va-kb9bvg {
  stop-color: var(--svg-color--7d5248, #7D5248);
}

.vgks6xbbq {
  stop-color: var(--svg-color--70444c, #70444C);
}

.vidx7_6lw {
  d: path("M19.42 25.81h-6.94c-.28 0-.5.22-.5.5v3.68h7.95v-3.68a.517.517 0 0 0-.51-.5");
}

.vtbjbdc7x {
  stop-color: var(--svg-color--356ebb, #356EBB);
  stop-opacity: 0;
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w-ul8jbeq {
  stop-color: var(--svg-color--356ebb, #356EBB);
}

.w39e-ubuo {
  stop-color: var(--svg-color--734a4b, #734A4B);
}

.w58utkb1j {
  stop-color: var(--svg-color--643838, #643838);
}

.w6969eyte {
  stop-color: var(--svg-color--387c46, #387C46);
}

.wevrdub6o {
  stop-color: var(--svg-color--5cc585, #5CC585);
}

.wly33_qqy {
  stop-color: var(--svg-color--9c8f92, #9C8F92);
}

.wmgsz54km {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.975 25.958h1.796");
}

.ws6qwsbwq {
  stop-color: var(--svg-color--5a3136, #5A3136);
}

.wuonwfy3p {
  d: path("M26.772 23.12c.55 0 1 .45 1 1v2.29h-2v-2.29c0-.55.44-1 1-1");
}

.x6aj7b3cp {
  stop-color: var(--svg-color--88625f, #88625F);
  stop-opacity: 0;
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xjz9wom2l {
  stop-color: var(--svg-color--4e2d3a, #4E2D3A);
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.y4ttqibxw {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.426 9.21c.663 0 1.222.457 1.375 1.074a.278.278 0 0 1-.272.346h-2.264a.234.234 0 0 1-.23-.276c.127-.65.7-1.144 1.391-1.144");
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.y9bk_9fsc {
  stop-color: var(--svg-color--85808c, #85808C);
}

.ya-1vfowe {
  d: path("M11.03 12.26a1.67 1.67 0 1 0 0-3.34a1.67 1.67 0 0 0 0 3.34");
}

.ya4lejb1r {
  stop-color: var(--svg-color--6e5980, #6E5980);
}

.yc_s6bd2r {
  stop-color: var(--svg-color--6e4f4b, #6E4F4B);
}

.ym_13nbvu {
  stop-color: var(--svg-color--3ca9ff, #3CA9FF);
}

.yrr42qhfr {
  stop-color: var(--svg-color--5aa37a, #5AA37A);
  stop-opacity: 0;
}

.z-7tj_h3r {
  d: path("M12.964 21.473L16 19.35l2.987 2.084c.421.325 1.013.465 1.013-.354v-4.81c-1.24-.48-2.59-.77-4-.77s-2.76.24-4 .72v4.69c0 .954.594.823.964.563");
}

.zh1uzn9mk {
  stop-color: var(--svg-color--6d484c, #6D484C);
}

.zif_-obqz {
  stop-color: var(--svg-color--519473, #519473);
}

.zlungxbgo {
  stroke: var(--svg-color--463c3b, #463C3B);
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M12.5 8.242s.6-.581 1.723-.448");
}

.zm4f_vbug {
  stop-color: var(--svg-color--2a5923, #2A5923);
  stop-opacity: 0;
}

.zso009b_h {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.574 9.21c-.662 0-1.222.457-1.375 1.074a.278.278 0 0 0 .272.346h2.264c.144 0 .26-.132.23-.276a1.42 1.42 0 0 0-1.39-1.144");
}

.ztn8dybrr {
  stop-color: var(--svg-color--89829d, #89829D);
  stop-opacity: 0;
}

.zykvaibcy {
  stop-color: var(--svg-color--329fea, #329FEA);
}

</style>
