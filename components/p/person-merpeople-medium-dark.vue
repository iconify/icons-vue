<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iyxhEIc)"><path class="td6euhb6l"/></g><path fill="url(#itsSeme)" class="i6tnjcu8m"/><g filter="url(#iPdx6Qc)"><path fill="url(#icQ8Rgb)" class="if2-x0_3s"/></g><path class="isoj7sbli"/><path fill="url(#iv93sCz)" class="x5s8xacrq"/><path fill="url(#ibSlkKM)" class="x5s8xacrq"/><path fill="url(#iEyOfww)" class="x5s8xacrq"/><g filter="url(#i6c0E1Q)"><path fill="url(#iJgbE9c)" class="bb2fbgrpu"/></g><g filter="url(#iwvrqzb)"><path class="astnuhlxb"/><path fill="url(#iUVADwe)" class="gejm97-ji"/><path fill="url(#i8m0Qud)" class="gejm97-ji"/></g><g filter="url(#i0paX2c)"><path class="y7rown2ml"/><path fill="url(#ibOJFtd)" class="yr50mjbls"/><path fill="url(#iGJVNqK)" class="yr50mjbls"/></g><g filter="url(#iVojBPd)"><path fill="url(#i5hBc1c)" class="uwupv_ztt"/><path fill="url(#iskeGDX)" class="uwupv_ztt"/></g><path fill="url(#iYcj16d)" class="uwupv_ztt"/><path fill="url(#iZqERtb)" class="uwupv_ztt"/><g filter="url(#ixFx34c)"><path class="pnus4mbvq"/><path fill="url(#ilxV82b)" class="lrtdxszpp"/></g><g filter="url(#i12MWlb)"><path stroke="url(#iFIIACe)" class="izop3bc_a"/></g><g filter="url(#iC4992d)"><path stroke="url(#iFh5wUb)" class="xwn-kfb_d"/></g><g filter="url(#iVh42db)"><path stroke="url(#iUCaIqe)" class="w-8ib2bba"/></g><g filter="url(#iutGISb)"><path stroke="url(#ilygUee)" class="lk8uk6bqv"/></g><g filter="url(#iWOFGkb)"><path class="gvhsobr-k"/></g><g filter="url(#i1vqpGe)"><path stroke="url(#ikzmZXc)" class="w-3uv5bmy"/></g><path fill="url(#iFyxlqe)" class="km_8uqbsr"/><path fill="url(#iMYoQvd)" class="ifesvnbka"/><g filter="url(#iiRW4Id)"><path fill="url(#ibqyRje)" class="zj4248bze"/><path fill="url(#iT55Ugd)" class="zj4248bze"/></g><path fill="url(#iBaCuwc)" class="zj4248bze"/><path fill="url(#iEclupe)" class="zj4248bze"/><path fill="url(#itHmdLM)" class="zj4248bze"/><path fill="url(#i9REkze)" class="zj4248bze"/><path fill="url(#i0o3BGd)" class="zj4248bze"/><path fill="url(#iCpY8yD)" class="zj4248bze"/><path fill="url(#ig0HLqc)" class="zj4248bze"/><g filter="url(#iShHTGH)"><path class="y_efh-bqt"/></g><g filter="url(#ixcCKMK)"><path class="ag1l6absl"/><path fill="url(#iwaMEAX)" class="gbq9vo8su"/><path fill="url(#iaCAH5d)" class="gbq9vo8su"/><path fill="url(#i0Rs5Mf)" class="gbq9vo8su"/><path fill="url(#i8v0axe)" class="gbq9vo8su"/><path fill="url(#iPUUIhX)" class="gbq9vo8su"/></g><g filter="url(#iMQzQhe)"><path stroke="url(#iK5xsDb)" class="pl3p6ccjp"/></g><path fill="url(#i00kcEd)" class="avt3f3myu"/><g filter="url(#iQYrsmc)"><path fill="url(#iCaIh8E)" class="q04qidcke"/><path fill="url(#iVUnote)" class="q04qidcke"/><path fill="url(#i2s6Ymd)" class="q04qidcke"/><path fill="url(#iOSTqdd)" class="q04qidcke"/><path fill="url(#ifZW73x)" class="q04qidcke"/></g><g filter="url(#iy8Zaad)"><path class="r_-ih_bsf"/></g><g filter="url(#i1TBPqd)"><path class="dn71ccbtg"/></g><g filter="url(#iSHoPnb)"><path class="h2pmyvbme"/><path fill="url(#iDtfTjB)" class="s9dmqn09q"/><path fill="url(#i8ZQeCK)" class="s9dmqn09q"/></g><g filter="url(#iqwjZge)"><path class="chiw_cbro"/><path fill="url(#iXTPCEF)" class="t8xg2tg3f"/><path fill="url(#iVVV0ed)" class="t8xg2tg3f"/></g><path class="pck9pabxc"/><path fill="url(#iwhfUve)" class="jyu3lwbui"/><path class="uk9jj-hst"/><g filter="url(#iYCQpsd)"><path class="p2zt-able"/><path fill="url(#iOSHPBc)" class="rh8nd8b0x"/></g><g filter="url(#iJoM0Mb)"><path fill="url(#iT8GEBc)" class="hb_ogew6a"/></g><path class="sjee296no"/><path fill="url(#iCc1IFP)" class="mqmfq5v9o"/><path class="dtfbqac-i"/><g filter="url(#i9k80jb)"><path fill="url(#iSaoYNe)" class="f0qkucb4f"/></g><g filter="url(#izS3nyr)"><ellipse transform="rotate(-27.914 16.124 6.566)" class="onateobba"/><ellipse fill="url(#iN4oxGb)" transform="rotate(-27.914 16.124 6.566)" class="lxf-5k96n"/></g><path fill="url(#i7UcKqd)" class="ukvl8u6wk"/><path fill="url(#ir6Wrwe)" class="ukvl8u6wk"/><path fill="url(#iAoZC0d)" class="ukvl8u6wk"/><path fill="url(#i5Dcsuk)" class="ukvl8u6wk"/><path fill="url(#inSpP5b)" class="iz3r0kbij"/><path fill="url(#imV9XnB)" class="iz3r0kbij"/><g filter="url(#iWkMZqc)"><path fill="url(#i1MZIKc)" class="b1eox6-wm"/></g><g filter="url(#ip15hXc)"><path fill="url(#icLgOib)" class="rppkiibbv"/></g><g filter="url(#iv7h3Od)" class="mc2zb0bvp"><path class="y2184wbml"/></g><g filter="url(#i9uxJWV)"><path stroke="url(#ioY1wje)" class="ry_er4bde"/></g><defs><radialGradient id="itsSeme" cx="0" cy="0" r="1" gradientTransform="rotate(-17.313 87.822 -23.113)scale(13.0953 16.0195)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="g1dp7ccjz"/><stop offset="1" class="s536pit3i"/></radialGradient><radialGradient id="icQ8Rgb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.61906 1.93752 -6.36477 -11.88867 22.702 20.617)" gradientUnits="userSpaceOnUse"><stop class="h8_lbz_nz"/><stop offset="1" class="jkj1op9ie"/></radialGradient><radialGradient id="ibSlkKM" cx="0" cy="0" r="1" gradientTransform="rotate(-49.88 21.65 1.225)scale(1.27707 1.06889)" gradientUnits="userSpaceOnUse"><stop offset=".693" class="ayo868b3w"/><stop offset="1" class="ztc1zd6vw"/></radialGradient><radialGradient id="iEyOfww" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8737 -1.06183 0 7.249 16.475)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="l8_ed6khd"/><stop offset="1" class="y31txn93j"/></radialGradient><radialGradient id="i8m0Qud" cx="0" cy="0" r="1" gradientTransform="matrix(.88953 2.91279 -1.06086 .32398 23.622 10.366)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="j0d1qvflz"/><stop offset="1" class="d7uo-wzfl"/></radialGradient><radialGradient id="ibOJFtd" cx="0" cy="0" r="1" gradientTransform="matrix(-.57032 .46875 -.2011 -.24468 25.71 7.406)" gradientUnits="userSpaceOnUse"><stop class="qwuga_k0r"/><stop offset="1" class="ifav_lb6f"/></radialGradient><radialGradient id="iGJVNqK" cx="0" cy="0" r="1" gradientTransform="rotate(-140.258 14.327 -.219)scale(.90426 .73334)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="su_ucv75j"/><stop offset="1" class="k6t64cc1v"/></radialGradient><radialGradient id="i5hBc1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.46875 -5.71107 0 19.177 12.742)" gradientUnits="userSpaceOnUse"><stop offset=".377" class="dw0qvsbps"/><stop offset="1" class="yafg_whjr"/></radialGradient><radialGradient id="iskeGDX" cx="0" cy="0" r="1" gradientTransform="rotate(58.499 -1.805 23.135)scale(1.85402 1.92266)" gradientUnits="userSpaceOnUse"><stop offset=".221" class="pygktylau"/><stop offset="1" class="dqd47gnac"/></radialGradient><radialGradient id="iZqERtb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.00003 -7.0781 9.3879 -5.30536 19.333 16.96)" gradientUnits="userSpaceOnUse"><stop offset=".786" class="gv9be6ybc"/><stop offset="1" class="nqt5hcbes"/></radialGradient><radialGradient id="ilxV82b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.47103 2.30187 -1.86833 -2.81728 17.116 9.537)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="zt7j0xb8q"/><stop offset="1" class="se2yt0xth"/></radialGradient><radialGradient id="iFyxlqe" cx="0" cy="0" r="1" gradientTransform="matrix(.42967 1.15888 -1.37665 .51041 20.26 7.687)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="cbylncbjf"/><stop offset="1" class="hj2nkngkt"/></radialGradient><radialGradient id="iMYoQvd" cx="0" cy="0" r="1" gradientTransform="matrix(.84724 .26628 -.82148 2.6138 14.057 7.968)" gradientUnits="userSpaceOnUse"><stop class="i4otoyosx"/><stop offset=".746" class="zqff1532o"/></radialGradient><radialGradient id="ibqyRje" cx="0" cy="0" r="1" gradientTransform="matrix(-2.99992 0 0 -5.30683 19.143 7.147)" gradientUnits="userSpaceOnUse"><stop class="e4t6-lb6y"/><stop offset="1" class="hhi9hubjb"/><stop offset="1" class="hhi9hubjb"/></radialGradient><radialGradient id="iT55Ugd" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 8.253 7.481)scale(1.93324 1.59604)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="fajfg00jo"/><stop offset="1" class="wpa_x2uhd"/></radialGradient><radialGradient id="iEclupe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.65896 .81547 0 18.936 6.393)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="o847wybrn"/><stop offset="1" class="z-0dlhbai"/></radialGradient><radialGradient id="itHmdLM" cx="0" cy="0" r="1" gradientTransform="matrix(.00226 -.62793 .68334 .00245 16.212 6.42)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="pxeuj6buu"/><stop offset="1" class="lg98p_5je"/></radialGradient><radialGradient id="i9REkze" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.63 4.164)scale(4.88499 12.4787)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="sim-rnb6d"/><stop offset="1" class="vx5g9qbgu"/></radialGradient><radialGradient id="i0o3BGd" cx="0" cy="0" r="1" gradientTransform="matrix(1.94288 -1.67357 .49434 .5739 13.635 5.578)" gradientUnits="userSpaceOnUse"><stop offset=".539" class="sf65_-b_u"/><stop offset="1" class="n9ebefe8q"/></radialGradient><radialGradient id="iCpY8yD" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.866 12.166)scale(1.43943 .5754)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="p54kb3bjj"/><stop offset="1" class="rm9y2hb6m"/></radialGradient><radialGradient id="ig0HLqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.4001 -5.73032 0 17.559 5.502)" gradientUnits="userSpaceOnUse"><stop offset=".72" class="nso85qbdr"/><stop offset="1" class="yvof5m88m"/></radialGradient><radialGradient id="iaCAH5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .14008 -.44023 0 17.8 7.927)" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></radialGradient><radialGradient id="i8v0axe" cx="0" cy="0" r="1" gradientTransform="rotate(155.369 8.103 5.75)scale(.96026 1.54321)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="cjboikbop"/><stop offset="1" class="l6ffphqdg"/></radialGradient><radialGradient id="i00kcEd" cx="0" cy="0" r="1" gradientTransform="matrix(1.2521 -.61557 2.47658 5.0375 17.25 9.226)" gradientUnits="userSpaceOnUse"><stop offset=".562" class="etju2kb3q"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iVUnote" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.00918 5.08098 0 14.531 5.487)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="i2s6Ymd" cx="0" cy="0" r="1" gradientTransform="matrix(.06545 -1.44179 2.55455 .11596 20.322 6.239)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iOSTqdd" cx="0" cy="0" r="1" gradientTransform="rotate(-146.667 10.339 -1.658)scale(1.6201 1.18923)" gradientUnits="userSpaceOnUse"><stop class="jx9hffbwe"/><stop offset="1" class="mzj8iibqz"/></radialGradient><radialGradient id="ifZW73x" cx="0" cy="0" r="1" gradientTransform="matrix(.38544 .68757 -1.5921 .8925 17.013 1.724)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="e8ajgab-k"/><stop offset="1" class="gxf7b0v7y"/></radialGradient><radialGradient id="iDtfTjB" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26308 0 0 -.46878 17.677 3.02)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="i8ZQeCK" cx="0" cy="0" r="1" gradientTransform="matrix(1.8467 -2.92394 3.23942 2.04595 14.416 5.282)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iXTPCEF" cx="0" cy="0" r="1" gradientTransform="matrix(1.53714 -1.46452 2.68117 2.81412 19.043 5.209)" gradientUnits="userSpaceOnUse"><stop offset=".857" class="stq0hsb2e"/><stop offset="1" class="i6xvtdb8e"/></radialGradient><radialGradient id="iVVV0ed" cx="0" cy="0" r="1" gradientTransform="matrix(1.86394 .21786 -.09122 .7804 18.535 4.361)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iwhfUve" cx="0" cy="0" r="1" gradientTransform="matrix(0 .46556 -.74053 0 18.784 6.62)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iOSHPBc" cx="0" cy="0" r="1" gradientTransform="matrix(-.13308 -.17149 .2361 -.18323 18.654 6.67)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iCc1IFP" cx="0" cy="0" r="1" gradientTransform="matrix(0 .46559 -.74057 0 16.28 6.62)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iN4oxGb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.379 -4.56)scale(.28356 .34084)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ir6Wrwe" cx="0" cy="0" r="1" gradientTransform="matrix(.36068 1.28726 -1.22815 .34412 20.182 6.629)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xron-kbnx"/><stop offset="1" class="bzyp_ibbo"/></radialGradient><radialGradient id="iAoZC0d" cx="0" cy="0" r="1" gradientTransform="matrix(.45206 -.62037 .52 .37891 20.389 6.941)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="w_o-5kbak"/><stop offset="1" class="mb4bnzbbk"/></radialGradient><radialGradient id="i5Dcsuk" cx="0" cy="0" r="1" gradientTransform="matrix(.33684 -.88969 1.18874 .45006 20.454 7.04)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="sxoyafbbn"/><stop offset="1" class="tri7bg95c"/></radialGradient><radialGradient id="imV9XnB" cx="0" cy="0" r="1" gradientTransform="matrix(-.95156 0 0 -1.06256 14.711 6.997)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="srn41o2oz"/><stop offset="1" class="dfc36bbxx"/></radialGradient><radialGradient id="i1MZIKc" cx="0" cy="0" r="1" gradientTransform="rotate(170.259 7.058 4.126)scale(.5336 .5471)" gradientUnits="userSpaceOnUse"><stop class="m_eaw6bxg"/><stop offset="1" class="nk_trfbso"/></radialGradient><filter id="iyxhEIc" width="16.97" height="13.626" x="7.639" y="16.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1293"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.576471 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1293" result="effect2_innerShadow_4002_1293"/></filter><filter id="iPdx6Qc" width="8.803" height="12.453" x="15.083" y="15.257" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1293" stdDeviation=".5"/></filter><filter id="i6c0E1Q" width="9.329" height="6.572" x="5.433" y="10.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.427451 0 0 0 0 0.305882 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1293"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.301961 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1293" result="effect2_innerShadow_4002_1293"/></filter><filter id="iwvrqzb" width="5.98" height="8.393" x="20.337" y="7.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.478431 0 0 0 0 0.282353 0 0 0 0 0.419608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1293"/></filter><filter id="i0paX2c" width="1.41" height="1.949" x="24.485" y="7.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.411765 0 0 0 0 0.243137 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1293"/></filter><filter id="iVojBPd" width="6.555" height="7.624" x="14.255" y="10.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.470588 0 0 0 0 0.0117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1293"/></filter><filter id="ixFx34c" width="4.212" height="3.197" x="15.358" y="10.239" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.435294 0 0 0 0 0.247059 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1293"/></filter><filter id="i12MWlb" width="11.112" height="3.615" x="10.829" y="25.843" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1293" stdDeviation=".2"/></filter><filter id="iC4992d" width="3.297" height="3.17" x="8.245" y="23.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1293" stdDeviation=".2"/></filter><filter id="iVh42db" width="3.085" height="3.032" x="11.506" y="23.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1293" stdDeviation=".2"/></filter><filter id="iutGISb" width="4.07" height="2.867" x="20.64" y="11.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1293" stdDeviation=".25"/></filter><filter id="iWOFGkb" width="2.394" height="7.066" x="24.256" y="7.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1293" stdDeviation=".3"/></filter><filter id="i1vqpGe" width="2.251" height="3.579" x="23.392" y="7.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1293" stdDeviation=".2"/></filter><filter id="iiRW4Id" width="6.365" height="7.132" x="14.627" y="3.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.494118 0 0 0 0 0.352941 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1293"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".05"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.215686 0 0 0 0 0.215686 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1293" result="effect2_innerShadow_4002_1293"/></filter><filter id="iShHTGH" width="3.002" height="3.664" x="15.95" y="5.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1293" stdDeviation=".5"/></filter><filter id="ixcCKMK" width="1.177" height="1.764" x="16.943" y="6.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1293" stdDeviation=".025"/></filter><filter id="iMQzQhe" width="2.047" height=".816" x="16.509" y="8.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1293" stdDeviation=".025"/></filter><filter id="iQYrsmc" width="7.387" height="5.008" x="13.839" y="1.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1293"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1293" result="effect2_innerShadow_4002_1293"/></filter><filter id="iy8Zaad" width="1.385" height=".768" x="18.444" y="4.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1293"/></filter><filter id="i1TBPqd" width="1.385" height=".76" x="15.428" y="4.956" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.0862745 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1293"/></filter><filter id="iSHoPnb" width="3.791" height="3.444" x="14.036" y="2.409" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1293"/><feGaussianBlur result="effect2_foregroundBlur_4002_1293" stdDeviation=".075"/></filter><filter id="iqwjZge" width="3.346" height="3.034" x="17.628" y="2.815" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1293" stdDeviation=".025"/></filter><filter id="iYCQpsd" width=".537" height=".485" x="18.32" y="6.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1293" stdDeviation=".05"/></filter><filter id="iJoM0Mb" width=".682" height=".695" x="18.76" y="6.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1293" stdDeviation=".1"/></filter><filter id="i9k80jb" width=".736" height=".767" x="16.21" y="6.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1293" stdDeviation=".1"/></filter><filter id="izS3nyr" width=".609" height=".489" x="15.82" y="6.321" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1293" stdDeviation=".05"/></filter><filter id="iWkMZqc" width=".976" height="1.578" x="13.936" y="6.209" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1293" stdDeviation=".125"/></filter><filter id="ip15hXc" width="1.543" height="2.092" x="19.868" y="5.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1293" stdDeviation=".25"/></filter><filter id="iv7h3Od" width="2.561" height="1.264" x="18.267" y="3.144" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1293" stdDeviation=".1"/></filter><filter id="i9uxJWV" width="6.781" height="4.219" x="7.807" y="12.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1293" stdDeviation=".25"/></filter><linearGradient id="iv93sCz" x1="6.762" x2="7.023" y1="16.843" y2="16.843" gradientUnits="userSpaceOnUse"><stop class="l0b9ugpej"/><stop offset="1" class="pk36xgbhu"/></linearGradient><linearGradient id="iJgbE9c" x1="10.656" x2="11.312" y1="14.335" y2="16.773" gradientUnits="userSpaceOnUse"><stop class="gc13cebqz"/><stop offset="1" class="ojh7dt-de"/></linearGradient><linearGradient id="iUVADwe" x1="22.218" x2="22.984" y1="14.335" y2="12.945" gradientUnits="userSpaceOnUse"><stop class="nn2tl5ewa"/><stop offset="1" class="x8msyybfl"/></linearGradient><linearGradient id="iYcj16d" x1="13.802" x2="15.755" y1="16.085" y2="16.085" gradientUnits="userSpaceOnUse"><stop class="x8wsft-hb"/><stop offset="1" class="m0mihob_v"/></linearGradient><linearGradient id="iFIIACe" x1="11.768" x2="20.875" y1="27.015" y2="28.857" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iFh5wUb" x1="10.518" x2="8.203" y1="25.808" y2="25.435" gradientUnits="userSpaceOnUse"><stop offset=".302" class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iUCaIqe" x1="14.013" x2="13.482" y1="24.145" y2="26.255" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="ilygUee" x1="24.406" x2="22.549" y1="14.21" y2="15.252" gradientUnits="userSpaceOnUse"><stop offset=".358" class="sg2mogblb"/><stop offset="1" class="cqk4cq7dd"/></linearGradient><linearGradient id="ikzmZXc" x1="24.517" x2="24.517" y1="7.765" y2="10.144" gradientUnits="userSpaceOnUse"><stop offset=".355" class="mov-1s2fl"/><stop offset="1" class="mh93d6z2r"/></linearGradient><linearGradient id="iBaCuwc" x1="20.491" x2="19.04" y1="8.114" y2="8.114" gradientUnits="userSpaceOnUse"><stop class="agilw2byy"/><stop offset="1" class="h3kh2yb2k"/></linearGradient><linearGradient id="iwaMEAX" x1="18.013" x2="17.532" y1="7.534" y2="7.554" gradientUnits="userSpaceOnUse"><stop class="eqmylox_y"/><stop offset="1" class="sicchzd0u"/></linearGradient><linearGradient id="i0Rs5Mf" x1="17.532" x2="17.532" y1="8.187" y2="7.921" gradientUnits="userSpaceOnUse"><stop class="qsncw6btn"/><stop offset="1" class="v7xhdx32s"/></linearGradient><linearGradient id="iPUUIhX" x1="17.532" x2="17.532" y1="6.635" y2="6.949" gradientUnits="userSpaceOnUse"><stop class="fok393bvn"/><stop offset="1" class="y4umwkb_f"/></linearGradient><linearGradient id="iK5xsDb" x1="16.842" x2="17.025" y1="9.089" y2="8.61" gradientUnits="userSpaceOnUse"><stop class="t_m5csgaz"/><stop offset="1" class="ln8xouyxx"/></linearGradient><linearGradient id="iCaIh8E" x1="21.464" x2="14.8" y1="3.897" y2="3.897" gradientUnits="userSpaceOnUse"><stop class="s5pji6bqr"/><stop offset="1" class="c7qpv738k"/></linearGradient><linearGradient id="iT8GEBc" x1="19.231" x2="19.051" y1="6.652" y2="6.763" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iSaoYNe" x1="16.707" x2="16.527" y1="6.652" y2="6.763" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i7UcKqd" x1="21.226" x2="20.533" y1="6.667" y2="7.916" gradientUnits="userSpaceOnUse"><stop class="pkjt6qfem"/><stop offset="1" class="qw3t0fbxr"/></linearGradient><linearGradient id="inSpP5b" x1="14.175" x2="15.012" y1="7.071" y2="6.998" gradientUnits="userSpaceOnUse"><stop class="lsjj5yb-k"/><stop offset="1" class="ac3zxpbrp"/></linearGradient><linearGradient id="icLgOib" x1="20.64" x2="20.64" y1="6.448" y2="7.54" gradientUnits="userSpaceOnUse"><stop class="x9ttejxmc"/><stop offset="1" class="nal-rljch"/></linearGradient><linearGradient id="ioY1wje" x1="13.839" x2="13.674" y1="13.023" y2="17.912" gradientUnits="userSpaceOnUse"><stop class="sqg5tercc"/><stop offset="1" class="nd5f-ubgy"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-merpeople-medium-dark" /></template>
<style>
.ac3zxpbrp {
  stop-color: var(--svg-color--623549, #623549);
}

.ag1l6absl {
  fill: var(--svg-color--845b55, #845B55);
  d: path("m17.313 6.736l-.305 1.055c-.063.217.087.434.298.434h.452c.211 0 .36-.22.298-.434l-.305-1.055c-.065-.233-.37-.233-.438 0");
}

.agilw2byy {
  stop-color: var(--svg-color--936b5d, #936B5D);
}

.astnuhlxb {
  fill: var(--svg-color--856050, #856050);
  d: path("m23.587 12.28l-2.844-1.464l-.406 2.718l3.348 1.708a1.8 1.8 0 0 0 1.84-.121c.527-.363.82-.979.79-1.618c-.06-1.273-.081-2.688-.103-3.586v-1.39a.531.531 0 0 0-1.063 0v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.238-.2c-.125-.129-.17-.309-.17-.488v-.667a.531.531 0 1 0-1.062 0v1.201a1 1 0 0 0 .235.644l.373.444a.2.2 0 0 1 .046.151c-.065.582-.148 1.353-.197 1.853a.202.202 0 0 1-.293.16");
}

.avt3f3myu {
  d: path("M17.532 8.809c-.291 0-.565-.069-.795-.189c-.079-.04-.163.049-.114.12c.193.291.527.486.909.486c.381 0 .716-.195.909-.486c.05-.074-.035-.16-.114-.12c-.23.12-.5.189-.795.189");
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.ayo868b3w {
  stop-color: var(--svg-color--542825, #542825);
  stop-opacity: 0;
}

.b1eox6-wm {
  d: path("M14.614 6.459a.548.548 0 0 0 .048 1.078q-.03-.539-.048-1.078");
}

.bb2fbgrpu {
  d: path("m6.569 15.067l-.755.857a.526.526 0 0 0 .776.71l.554-.583a.384.384 0 0 1 .476-.065l.018.01a.1.1 0 0 1 .019.155l-.317.316a.528.528 0 0 0 .716.774l.557-.479a.2.2 0 0 1 .13-.048h1.765a2.5 2.5 0 0 0 1.64-.613l2.365-2.055v-3.25c-.257.025-.59.285-.723.418l-3.247 3.04a.5.5 0 0 1-.284.132l-3.068.355a.98.98 0 0 0-.622.326");
}

.bbyb_mbsk {
  stop-color: var(--svg-color--664842, #664842);
}

.bzyp_ibbo {
  stop-color: var(--svg-color--71404f, #71404F);
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

.chiw_cbro {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m20.523 5.799l-.017-.362a.843.843 0 0 0-.806-.818h-.803a1.39 1.39 0 0 1-1.22-.723s.415-1.188 1.096-1.014c.481.123.994.309 1.398.573c1.002.653.88 1.79.352 2.344");
}

.cjboikbop {
  stop-color: var(--svg-color--744a4a, #744A4A);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cqk4cq7dd {
  stop-color: var(--svg-color--8e6961, #8E6961);
  stop-opacity: 0;
}

.d7uo-wzfl {
  stop-color: var(--svg-color--714945, #714945);
  stop-opacity: 0;
}

.dfc36bbxx {
  stop-color: var(--svg-color--836158, #836158);
}

.dn71ccbtg {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M15.575 5.374a1.6 1.6 0 0 1 .998-.206a.16.16 0 1 1-.039.316a1.27 1.27 0 0 0-.839.19l-.01.007v.002a.16.16 0 0 1-.196-.252z");
}

.dqd47gnac {
  stop-color: var(--svg-color--ff8e3e, #FF8E3E);
  stop-opacity: 0;
}

.dtfbqac-i {
  fill: var(--svg-color--000, #000);
  d: path("M16.572 6.86a.29.29 0 0 0-.293-.294a.292.292 0 0 0-.261.428h.52a.3.3 0 0 0 .034-.135");
}

.dw0qvsbps {
  stop-color: var(--svg-color--ff8738, #FF8738);
}

.dwl_ftd7p {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
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

.eqmylox_y {
  stop-color: var(--svg-color--a17c72, #A17C72);
}

.etju2kb3q {
  stop-color: var(--svg-color--87004e, #87004E);
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f0qkucb4f {
  d: path("M16.747 6.8c0-.166-.135-.277-.171-.31l-.166.16l.102.207z");
}

.fajfg00jo {
  stop-color: var(--svg-color--855e5a, #855E5A);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fok393bvn {
  stop-color: var(--svg-color--865c56, #865C56);
}

.ft5dv1b6b {
  fill: none;
}

.g1dp7ccjz {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
  stop-opacity: 0;
}

.gbq9vo8su {
  d: path("m17.313 6.736l-.305 1.055c-.063.217.087.434.298.434h.452c.211 0 .36-.22.298-.434l-.305-1.055c-.065-.233-.37-.233-.438 0");
}

.gc13cebqz {
  stop-color: var(--svg-color--725147, #725147);
}

.gejm97-ji {
  d: path("m23.587 12.28l-2.844-1.464l-.406 2.718l3.348 1.708a1.8 1.8 0 0 0 1.84-.121c.527-.363.82-.979.79-1.618c-.06-1.273-.081-2.688-.103-3.586v-1.39a.531.531 0 0 0-1.063 0v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.238-.2c-.125-.129-.17-.309-.17-.488v-.667a.531.531 0 1 0-1.062 0v1.201a1 1 0 0 0 .235.644l.373.444a.2.2 0 0 1 .046.151c-.065.582-.148 1.353-.197 1.853a.202.202 0 0 1-.293.16");
}

.gv9be6ybc {
  stop-color: var(--svg-color--e15c10, #E15C10);
  stop-opacity: 0;
}

.gvhsobr-k {
  stroke: var(--svg-color--947068, #947068);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M25.156 14.007v-3.781l.594-.406V8.742");
}

.gxf7b0v7y {
  stop-color: var(--svg-color--392f31, #392F31);
  stop-opacity: 0;
}

.h2pmyvbme {
  fill: var(--svg-color--2d171f, #2D171F);
  d: path("m17.665 3.924l-.038-.078a.38.38 0 0 0-.353-.24h-.73c-1.06 0-1.918.868-1.918 1.939v.158c-.195-.149-.44-.462-.44-.969c0-.615.449-.926.735-1.124c.08-.056.148-.103.19-.146l.057-.06c.2-.212.558-.591 1.182-.757c.175-.047.353-.073.52-.086c.47-.036.807.376.807.85v.505z");
}

.h3kh2yb2k {
  stop-color: var(--svg-color--936b5d, #936B5D);
  stop-opacity: 0;
}

.h8_lbz_nz {
  stop-color: var(--svg-color--4edd83, #4EDD83);
}

.hb_ogew6a {
  d: path("M19.242 6.792a.5.5 0 0 0-.133-.266l-.15.164l.068.13z");
}

.hhi9hubjb {
  stop-color: var(--svg-color--754c4c, #754C4C);
}

.hj2nkngkt {
  stop-color: var(--svg-color--221925, #221925);
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.i4otoyosx {
  stop-color: var(--svg-color--3e3330, #3E3330);
}

.i6tnjcu8m {
  d: path("M13.356 19.136c0-1.425.76-2.101 1.16-2.242l5.66-.34c1.61.719 2.954 2.781 3.141 5.281c.188 2.5-.203 4.953-2.265 6.563c-1.65 1.287-3.959 1.552-4.938 1.531h-2.472c-2.625 0-3.247-1.89-3.356-2.297a11 11 0 0 0-.184-.598a.43.43 0 0 0-.221-.26c-.528-.244-1.52-.486-1.947-1.388a3.1 3.1 0 0 1-.28-1.63c.022-.213.232-.344.441-.296c.52.119.95.252 1.57.567a3.4 3.4 0 0 1 1.237 1.226c.065.11.238.112.304.003c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.765-.748 2.275-1.198 2.513c-.288.131-.62.277-.865.388c-.14.063-.21.223-.141.36c.474.956 1.468.869 2.858.869c1.851 0 2.96-1.324 2.843-2.723c-.062-1.812-1.562-2.515-2.57-3.148c-.523-.329-2.055-1.145-2.055-2.926");
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

.if2-x0_3s {
  d: path("M21.317 26.71c0-5.343-3.922-7.968-5.234-9l3.25-1.453c1.125.521 3.035 2.358 3.453 5.11c.484 3.187-.927 4.927-1.469 5.343");
}

.ifav_lb6f {
  stop-color: var(--svg-color--91746b, #91746B);
  stop-opacity: 0;
}

.ifesvnbka {
  d: path("M14.743 7.864a.94.94 0 0 1-.52-.177v.534c0 .512.306.969.77 1.158a2.4 2.4 0 0 1-.199-.677z");
}

.isoj7sbli {
  fill: var(--svg-color--633e43, #633E43);
  d: path("M6.762 16.087a.486.486 0 0 1 .973 0v.775a.486.486 0 1 1-.973 0z");
}

.iz3r0kbij {
  d: path("M14.637 6.077a.923.923 0 0 0 .074 1.839a45 45 0 0 1-.074-1.839");
}

.izop3bc_a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M11.429 26.909c-.007.65.436 1.948 2.266 1.948h3.177c1.01-.014 3.317-.516 4.469-2.414");
}

.j0d1qvflz {
  stop-color: var(--svg-color--714945, #714945);
}

.jkj1op9ie {
  stop-color: var(--svg-color--4edd83, #4EDD83);
  stop-opacity: 0;
}

.jx9hffbwe {
  stop-color: var(--svg-color--402c32, #402C32);
}

.jyu3lwbui {
  d: path("M18.785 6.347a.512.512 0 0 1 .494.647h-.99a.514.514 0 0 1 .496-.647");
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k6t64cc1v {
  stop-color: var(--svg-color--673a31, #673A31);
  stop-opacity: 0;
}

.km_8uqbsr {
  d: path("M20.322 7.864a.94.94 0 0 0 .519-.177v.534c0 .512-.306.969-.77 1.158q.147-.312.199-.677z");
}

.l0b9ugpej {
  stop-color: var(--svg-color--86635c, #86635C);
}

.l6ffphqdg {
  stop-color: var(--svg-color--744a4a, #744A4A);
}

.l8_ed6khd {
  stop-color: var(--svg-color--744165, #744165);
  stop-opacity: 0;
}

.lg98p_5je {
  stop-color: var(--svg-color--70424e, #70424E);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lk8uk6bqv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m21.39 12.46l2.57 1.367");
}

.ln8xouyxx {
  stop-color: var(--svg-color--866163, #866163);
  stop-opacity: 0;
}

.lrtdxszpp {
  d: path("M19.57 10.487c-1.778-.422-3.256-.227-4.111.002l.002.015v.778a2.054 2.054 0 1 0 4.107 0v-.778z");
}

.lsjj5yb-k {
  stop-color: var(--svg-color--6a4544, #6A4544);
}

.lxf-5k96n {
  cx: 16.124px;
  cy: 6.566px;
  rx: 0.224px;
  ry: 0.113px;
}

.m_eaw6bxg {
  stop-color: var(--svg-color--57353c, #57353C);
}

.m0mihob_v {
  stop-color: var(--svg-color--fb711e, #FB711E);
  stop-opacity: 0;
}

.mb4bnzbbk {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mh93d6z2r {
  stop-color: var(--svg-color--94766c, #94766C);
  stop-opacity: 0;
}

.mov-1s2fl {
  stop-color: var(--svg-color--94766c, #94766C);
}

.mqmfq5v9o {
  d: path("M16.279 6.347a.512.512 0 0 0-.494.647h.99a.516.516 0 0 0-.496-.647");
}

.mzj8iibqz {
  stop-color: var(--svg-color--402c32, #402C32);
  stop-opacity: 0;
}

.n9ebefe8q {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
  stop-opacity: 0;
}

.nal-rljch {
  stop-color: var(--svg-color--7d5449, #7D5449);
}

.nd5f-ubgy {
  stop-color: var(--svg-color--815658, #815658);
  stop-opacity: 0;
}

.nk_trfbso {
  stop-color: var(--svg-color--5b3336, #5B3336);
}

.nn2tl5ewa {
  stop-color: var(--svg-color--80474d, #80474D);
}

.nqt5hcbes {
  stop-color: var(--svg-color--e15c10, #E15C10);
}

.nso85qbdr {
  stop-color: var(--svg-color--794755, #794755);
  stop-opacity: 0;
}

.o847wybrn {
  stop-color: var(--svg-color--875455, #875455);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojh7dt-de {
  stop-color: var(--svg-color--7e4e5c, #7E4E5C);
}

.onateobba {
  cx: 16.124px;
  cy: 6.566px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.224px;
  ry: 0.113px;
}

.ovvtmacpn {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
  stop-opacity: 0;
}

.p2zt-able {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.748 6.455c.036.05-.04.109-.127.173c-.086.065-.15.11-.187.062c-.037-.049.004-.14.09-.206c.087-.065.187-.078.224-.029");
}

.p54kb3bjj {
  stop-color: var(--svg-color--98786d, #98786D);
}

.pck9pabxc {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.904 6.191c.375 0 .691.258.778.608a.157.157 0 0 1-.154.195h-1.28a.132.132 0 0 1-.13-.156a.8.8 0 0 1 .786-.647");
}

.pk36xgbhu {
  stop-color: var(--svg-color--674042, #674042);
  stop-opacity: 0;
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkjt6qfem {
  stop-color: var(--svg-color--9c7b71, #9C7B71);
}

.pl3p6ccjp {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.532 8.809c-.291 0-.565-.069-.795-.189c-.079-.04-.163.049-.114.12c.193.291.527.486.909.486c.381 0 .716-.195.909-.486c.05-.074-.035-.16-.114-.12c-.23.12-.5.189-.795.189Z");
}

.pnus4mbvq {
  fill: var(--svg-color--885b53, #885B53);
  d: path("M19.57 10.487c-1.778-.422-3.256-.227-4.111.002l.002.015v.778a2.054 2.054 0 1 0 4.107 0v-.778z");
}

.pxeuj6buu {
  stop-color: var(--svg-color--70424e, #70424E);
}

.pygktylau {
  stop-color: var(--svg-color--ff8e3e, #FF8E3E);
}

.q04qidcke {
  d: path("M20.318 3.335c.295.101.56.307.727.603a1.36 1.36 0 0 1-.06 1.45a.9.9 0 0 0-.156.501v.682a1 1 0 0 0-.383-.154l.045-.922a.83.83 0 0 0-.79-.821h-.804a1.39 1.39 0 0 1-1.27-.828a.38.38 0 0 0-.353-.24h-.73c-1.06 0-1.917.867-1.917 1.939l.017.882a1 1 0 0 0-.413.151V5.89a.9.9 0 0 0-.155-.501a1.37 1.37 0 0 1-.083-1.404c.168-.317.439-.539.746-.646c.329-.117.609-.339.794-.637a1.334 1.334 0 0 1 1.66-.524a.85.85 0 0 0 .684 0a1.334 1.334 0 0 1 1.665.542c.176.293.453.505.776.616");
}

.qsncw6btn {
  stop-color: var(--svg-color--7d465b, #7D465B);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qw3t0fbxr {
  stop-color: var(--svg-color--815758, #815758);
}

.qwuga_k0r {
  stop-color: var(--svg-color--91746b, #91746B);
}

.r_-ih_bsf {
  fill: var(--svg-color--2e201f, #2E201F);
  d: path("M19.674 5.437c-.1-.088-.217-.18-.394-.236c-.175-.055-.394-.07-.696-.033a.16.16 0 1 0 .039.316c.276-.034.445-.016.561.02c.114.036.19.094.281.173a.16.16 0 1 0 .21-.24");
}

.rh8nd8b0x {
  d: path("M18.748 6.455c.036.05-.04.109-.127.173c-.086.065-.15.11-.187.062c-.037-.049.004-.14.09-.206c.087-.065.187-.078.224-.029");
}

.rm9y2hb6m {
  stop-color: var(--svg-color--98786d, #98786D);
  stop-opacity: 0;
}

.rppkiibbv {
  d: path("M20.368 7.54q.034-.546.064-1.092a.548.548 0 0 1-.064 1.092");
}

.ry_er4bde {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m13.839 13.023l-2.97 2.719H8.558");
}

.s536pit3i {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
}

.s5pji6bqr {
  stop-color: var(--svg-color--443237, #443237);
}

.s9dmqn09q {
  d: path("m17.665 3.924l-.038-.078a.38.38 0 0 0-.353-.24h-.73c-1.06 0-1.918.868-1.918 1.939v.158c-.195-.149-.44-.462-.44-.969c0-.615.449-.926.735-1.124c.08-.056.148-.103.19-.146l.057-.06c.2-.212.558-.591 1.182-.757c.175-.047.353-.073.52-.086c.47-.036.807.376.807.85v.505z");
}

.se2yt0xth {
  stop-color: var(--svg-color--56332d, #56332D);
  stop-opacity: 0;
}

.sf65_-b_u {
  stop-color: var(--svg-color--4f2c2a, #4F2C2A);
}

.sg2mogblb {
  stop-color: var(--svg-color--8e6961, #8E6961);
}

.sicchzd0u {
  stop-color: var(--svg-color--a17c72, #A17C72);
  stop-opacity: 0;
}

.sim-rnb6d {
  stop-color: var(--svg-color--815f58, #815F58);
  stop-opacity: 0;
}

.sjee296no {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.16 6.191a.8.8 0 0 0-.778.608c-.025.1.052.195.154.195h1.28a.132.132 0 0 0 .13-.156a.804.804 0 0 0-.786-.647");
}

.sqg5tercc {
  stop-color: var(--svg-color--815658, #815658);
}

.srn41o2oz {
  stop-color: var(--svg-color--836158, #836158);
  stop-opacity: 0;
}

.stq0hsb2e {
  stop-color: var(--svg-color--545051, #545051);
  stop-opacity: 0;
}

.su_ucv75j {
  stop-color: var(--svg-color--673a31, #673A31);
}

.sxoyafbbn {
  stop-color: var(--svg-color--805d4c, #805D4C);
  stop-opacity: 0;
}

.t_m5csgaz {
  stop-color: var(--svg-color--866163, #866163);
}

.t8xg2tg3f {
  d: path("m20.523 5.799l-.017-.362a.843.843 0 0 0-.806-.818h-.803a1.39 1.39 0 0 1-1.22-.723s.415-1.188 1.096-1.014c.481.123.994.309 1.398.573c1.002.653.88 1.79.352 2.344");
}

.td6euhb6l {
  fill: var(--svg-color--35bb78, #35BB78);
  d: path("M13.356 19.136c0-1.425.76-2.101 1.16-2.242l5.66-.34c1.61.719 2.954 2.781 3.141 5.281c.188 2.5-.203 4.953-2.265 6.563c-1.65 1.287-3.959 1.552-4.938 1.531h-2.472c-2.625 0-3.247-1.89-3.356-2.297a11 11 0 0 0-.184-.598a.43.43 0 0 0-.221-.26c-.528-.244-1.52-.486-1.947-1.388a3.1 3.1 0 0 1-.28-1.63c.022-.213.232-.344.441-.296c.52.119.95.252 1.57.567a3.4 3.4 0 0 1 1.237 1.226c.065.11.238.112.304.003c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.765-.748 2.275-1.198 2.513c-.288.131-.62.277-.865.388c-.14.063-.21.223-.141.36c.474.956 1.468.869 2.858.869c1.851 0 2.96-1.324 2.843-2.723c-.062-1.812-1.562-2.515-2.57-3.148c-.523-.329-2.055-1.145-2.055-2.926");
}

.tri7bg95c {
  stop-color: var(--svg-color--805d4c, #805D4C);
}

.uc2wxkyln {
  stop-color: var(--svg-color--40b87c, #40B87C);
  stop-opacity: 0;
}

.uk9jj-hst {
  fill: var(--svg-color--000, #000);
  d: path("M18.492 6.86c0-.164.13-.294.293-.294a.292.292 0 0 1 .261.428h-.519a.3.3 0 0 1-.035-.135");
}

.ukvl8u6wk {
  d: path("M20.356 7.916q.058-.915.106-1.831a.924.924 0 0 1-.106 1.831");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uwupv_ztt {
  d: path("M14.255 10.891c0-.039.022-.074.058-.09c.2-.089.63-.262 1.09-.346a.05.05 0 0 1 .058.049v.778a2.054 2.054 0 1 0 4.107 0v-.778a.05.05 0 0 1 .058-.05c.462.085.92.259 1.125.348c.036.015.058.05.058.09v6.386a.6.6 0 0 1-.6.6h-5.354a.6.6 0 0 1-.6-.6z");
}

.v7xhdx32s {
  stop-color: var(--svg-color--7d465b, #7D465B);
  stop-opacity: 0;
}

.vx5g9qbgu {
  stop-color: var(--svg-color--815f58, #815F58);
}

.w_o-5kbak {
  stop-color: var(--svg-color--7c4c46, #7C4C46);
}

.w-3uv5bmy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M23.992 7.765v1.121a.5.5 0 0 0 .146.354l.904.904");
}

.w-8ib2bba {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M13.991 23.955c-.307.353-1.133 1.1-1.885 1.832");
}

.w0a4mmrgb {
  stop-color: var(--svg-color--200e25, #200E25);
  stop-opacity: 0;
}

.wpa_x2uhd {
  stop-color: var(--svg-color--855e5a, #855E5A);
  stop-opacity: 0;
}

.x5s8xacrq {
  d: path("M6.762 16.087a.486.486 0 0 1 .973 0v.775a.486.486 0 1 1-.973 0z");
}

.x8msyybfl {
  stop-color: var(--svg-color--855f51, #855F51);
  stop-opacity: 0;
}

.x8wsft-hb {
  stop-color: var(--svg-color--db6229, #DB6229);
}

.x9ttejxmc {
  stop-color: var(--svg-color--825d56, #825D56);
}

.xron-kbnx {
  stop-color: var(--svg-color--71404f, #71404F);
  stop-opacity: 0;
}

.xwn-kfb_d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M8.845 24.474c.41.162 1.402.783 2.096 1.97");
}

.y_efh-bqt {
  fill: var(--svg-color--6f3f46, #6F3F46);
  d: path("m17.302 6.849l-.34 1.055c-.057.217.082.434.279.434h.42c.197 0 .335-.22.277-.434l-.283-1.055c-.061-.234-.29-.234-.353 0");
}

.y_rv32tfd {
  stop-color: var(--svg-color--40b87c, #40B87C);
}

.y2184wbml {
  fill: var(--svg-color--49373d, #49373D);
  d: path("M19.938 3.899h-1.194a.277.277 0 1 1 .044-.552c.31.05.721.118.997.187c.623.154.795.457.843.674a.87.87 0 0 0-.69-.31");
}

.y31txn93j {
  stop-color: var(--svg-color--744165, #744165);
}

.y4umwkb_f {
  stop-color: var(--svg-color--865c56, #865C56);
  stop-opacity: 0;
}

.y7rown2ml {
  fill: var(--svg-color--7b564b, #7B564B);
  d: path("M25.683 7.995h-.003a.53.53 0 0 0-.53.532v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.24-.2c-.124-.129-.169-.309-.169-.488V7.95l.56-.558a.44.44 0 0 1 .638.604");
}

.yafg_whjr {
  stop-color: var(--svg-color--eb6820, #EB6820);
}

.yr50mjbls {
  d: path("M25.683 7.995h-.003a.53.53 0 0 0-.53.532v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.24-.2c-.124-.129-.169-.309-.169-.488V7.95l.56-.558a.44.44 0 0 1 .638.604");
}

.yvof5m88m {
  stop-color: var(--svg-color--723d48, #723D48);
}

.z-0dlhbai {
  stop-color: var(--svg-color--875455, #875455);
  stop-opacity: 0;
}

.zj4248bze {
  d: path("M14.763 8.733a2.25 2.25 0 0 0 2.23 1.955h1.083a2.25 2.25 0 0 0 2.23-1.955c.067-1.08.135-2.157.185-3.238a.83.83 0 0 0-.791-.821h-.803a1.39 1.39 0 0 1-1.27-.828a.38.38 0 0 0-.353-.24h-.73c-1.06 0-1.918.868-1.918 1.939c0 1.067.067 2.118.137 3.188");
}

.zqff1532o {
  stop-color: var(--svg-color--201524, #201524);
}

.zt7j0xb8q {
  stop-color: var(--svg-color--45241f, #45241F);
}

.ztc1zd6vw {
  stop-color: var(--svg-color--542825, #542825);
}

</style>
