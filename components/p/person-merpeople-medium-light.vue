<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iuoOJLd)"><path class="td6euhb6l"/></g><path fill="url(#itsSeme)" class="i6tnjcu8m"/><g filter="url(#ily4DRb)"><path fill="url(#icQ8Rgb)" class="if2-x0_3s"/></g><path class="n2hacibqs"/><path fill="url(#iE8cmhe)" class="r_cv6ppfn"/><path fill="url(#iF9FxXd)" class="r_cv6ppfn"/><path fill="url(#ivj2jme)" class="r_cv6ppfn"/><g filter="url(#id5ho4c)"><path fill="url(#iFYshWc)" class="bb2fbgrpu"/></g><g filter="url(#i0jlYKb)"><path class="jq26pbbuc"/><path fill="url(#iLhkbUb)" class="gejm97-ji"/><path fill="url(#iB8RLPd)" class="gejm97-ji"/><path fill="url(#iZo0w8d)" class="gejm97-ji"/></g><g filter="url(#iBI1mJB)"><path class="hhs_ktgwp"/><path fill="url(#iJjujkd)" class="yr50mjbls"/><path fill="url(#iCmdqhd)" class="yr50mjbls"/></g><g filter="url(#iTAIxCc)"><path fill="url(#i5hBc1c)" class="uwupv_ztt"/><path fill="url(#iskeGDX)" class="uwupv_ztt"/></g><path fill="url(#iYcj16d)" class="uwupv_ztt"/><path fill="url(#iZqERtb)" class="uwupv_ztt"/><g filter="url(#i24srSv)"><path class="g10datb6e"/><path fill="url(#iB2TyZr)" class="lrtdxszpp"/></g><g filter="url(#ijzMPKb)"><path stroke="url(#iFIIACe)" class="izop3bc_a"/></g><g filter="url(#iDwZmYb)"><path stroke="url(#iFh5wUb)" class="aqae8acff"/></g><g filter="url(#iC8uqse)"><path stroke="url(#iUCaIqe)" class="w-8ib2bba"/></g><g filter="url(#iP4XrOa)"><path stroke="url(#i2tRpMe)" class="lk8uk6bqv"/></g><g filter="url(#i8QCrdd)"><path class="sxbkuzihq"/></g><g filter="url(#imsOW3N)"><path stroke="url(#ifH5Qfb)" class="w-3uv5bmy"/></g><g filter="url(#iYmD4md)"><path stroke="url(#iLWnLac)" class="ry_er4bde"/></g><path fill="url(#igO1v2c)" class="es_ec_zku"/><path fill="url(#iuxX79b)" class="evfll0tzs"/><path fill="url(#iTDElVb)" class="evfll0tzs"/><path fill="url(#iuxX79b)" class="evfll0tzs"/><path fill="url(#iTDElVb)" class="evfll0tzs"/><g filter="url(#iBYcDSG)"><path fill="url(#i2V0P5b)" class="nv3ul6l6h"/></g><path fill="url(#iizx6Hd)" class="nv3ul6l6h"/><path fill="url(#izP3OOb)" class="nv3ul6l6h"/><path fill="url(#iJhCFXd)" class="nv3ul6l6h"/><path fill="url(#i08iEGb)" class="nv3ul6l6h"/><path fill="url(#i3KbWdc)" class="nv3ul6l6h"/><path fill="url(#il3apvb)" class="nv3ul6l6h"/><path fill="url(#iIS3NOb)" class="nv3ul6l6h"/><path fill="url(#irVVYQb)" class="nv3ul6l6h"/><g filter="url(#iKLraFe)"><path class="o1lmyoq6y"/></g><g filter="url(#iEJJ6rb)"><path fill="url(#iLeFZgb)" class="dnnikzlft"/><path fill="url(#iwiNTie)" class="dnnikzlft"/><path fill="url(#iP5H0pc)" class="dnnikzlft"/><path fill="url(#i0L9IFb)" class="dnnikzlft"/></g><g filter="url(#iELof4v)"><path stroke="url(#i0KkUCc)" class="pkl2bklef"/></g><path fill="url(#iEC5GlJ)" class="ojcsn4b4p"/><g filter="url(#irnpbQc)"><path fill="url(#iKkR2Kb)" class="xeiaglb6x"/><path fill="url(#iOAwwSb)" class="xeiaglb6x"/><path fill="url(#i0lwMKc)" class="xeiaglb6x"/><path fill="url(#iJFF6je)" class="xeiaglb6x"/><path fill="url(#ihWKAei)" class="xeiaglb6x"/></g><g filter="url(#ithEBCc)"><path class="otx7-wbah"/></g><g filter="url(#ickBLfe)"><path class="ss0po6bla"/></g><g filter="url(#ijWvCvd)"><path fill="url(#i8Yc6Oe)" class="lijsgbc3d"/><path fill="url(#i7XOruc)" class="lijsgbc3d"/></g><g filter="url(#iAxxFnc)"><path fill="url(#iBANNrb)" class="uwj5xnfkj"/><path fill="url(#iQGPM3s)" class="uwj5xnfkj"/><path fill="url(#inEddid)" class="uwj5xnfkj"/><path fill="url(#iTMF5id)" class="uwj5xnfkj"/><path fill="url(#iLwQJiJ)" class="uwj5xnfkj"/><path fill="url(#ic1lNpe)" class="uwj5xnfkj"/></g><path class="go_35jbir"/><path fill="url(#i4qfZpQ)" class="lfurq4bwg"/><path class="aa_qax-gk"/><g filter="url(#iI4AO0I)"><path class="q28fyhb-x"/><path fill="url(#inzsxCc)" class="eq10tutlo"/></g><g filter="url(#ixN93hb)"><path fill="url(#iFv3Zud)" class="x_l-rmbrg"/></g><path class="sc66hv5ah"/><path fill="url(#iqDKNWd)" class="ona8jmyio"/><path class="yefommbih"/><g filter="url(#icJiJQe)"><path fill="url(#iopsxJd)" class="uk34iobtb"/></g><g filter="url(#il2Y5ec)"><ellipse transform="rotate(-27.914 16.096 6.602)" class="ojz-wi0ni"/><ellipse fill="url(#iTXuugd)" transform="rotate(-27.914 16.096 6.602)" class="bv2x_2b0w"/></g><path fill="url(#iIHkqfe)" class="vr22ulb0g"/><path fill="url(#ilQYzep)" class="vr22ulb0g"/><path fill="url(#idC00Ab)" class="vr22ulb0g"/><path fill="url(#iRAb0fe)" class="aqb4b0ltd"/><path fill="url(#iyifDqA)" class="aqb4b0ltd"/><g filter="url(#iPv7LUX)"><path class="mjkanubbn"/></g><g filter="url(#iAa7lBc)"><path class="sky6ld7vt"/></g><defs><radialGradient id="itsSeme" cx="0" cy="0" r="1" gradientTransform="rotate(-17.313 87.822 -23.113)scale(13.0953 16.0195)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="g1dp7ccjz"/><stop offset="1" class="s536pit3i"/></radialGradient><radialGradient id="icQ8Rgb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.61906 1.93752 -6.36477 -11.88867 22.702 20.617)" gradientUnits="userSpaceOnUse"><stop class="h8_lbz_nz"/><stop offset="1" class="jkj1op9ie"/></radialGradient><radialGradient id="iF9FxXd" cx="0" cy="0" r="1" gradientTransform="matrix(.82293 -.97657 .81738 .68878 6.74 17.01)" gradientUnits="userSpaceOnUse"><stop offset=".603" class="ephtlqrgv"/><stop offset="1" class="rtl5rdb5z"/></radialGradient><radialGradient id="ivj2jme" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8737 -1.06183 0 7.227 16.494)" gradientUnits="userSpaceOnUse"><stop offset=".735" class="uqhx2ybtm"/><stop offset="1" class="t_y7qszcu"/></radialGradient><radialGradient id="iB8RLPd" cx="0" cy="0" r="1" gradientTransform="matrix(.88953 2.91279 -1.06086 .32398 23.622 10.366)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="vy9mn1ofo"/><stop offset="1" class="w7is8p55o"/></radialGradient><radialGradient id="iZo0w8d" cx="0" cy="0" r="1" gradientTransform="matrix(.53214 0 0 2.90625 23.327 8.716)" gradientUnits="userSpaceOnUse"><stop class="jleiqdg7d"/><stop offset="1" class="ss6kf5hyw"/></radialGradient><radialGradient id="iJjujkd" cx="0" cy="0" r="1" gradientTransform="matrix(-.57032 .46875 -.2011 -.24468 25.71 7.406)" gradientUnits="userSpaceOnUse"><stop class="wxsmjrbxz"/><stop offset="1" class="gn_mwgb8p"/></radialGradient><radialGradient id="iCmdqhd" cx="0" cy="0" r="1" gradientTransform="rotate(-140.258 14.327 -.219)scale(.90426 .73334)" gradientUnits="userSpaceOnUse"><stop offset=".193" class="zk5jp9hiu"/><stop offset="1" class="t4q17cblu"/></radialGradient><radialGradient id="i5hBc1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.46875 -5.71107 0 19.177 12.742)" gradientUnits="userSpaceOnUse"><stop offset=".377" class="dw0qvsbps"/><stop offset="1" class="yafg_whjr"/></radialGradient><radialGradient id="iskeGDX" cx="0" cy="0" r="1" gradientTransform="rotate(58.499 -1.805 23.135)scale(1.85402 1.92266)" gradientUnits="userSpaceOnUse"><stop offset=".221" class="pygktylau"/><stop offset="1" class="dqd47gnac"/></radialGradient><radialGradient id="iZqERtb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.00003 -7.0781 9.3879 -5.30536 19.333 16.96)" gradientUnits="userSpaceOnUse"><stop offset=".786" class="gv9be6ybc"/><stop offset="1" class="nqt5hcbes"/></radialGradient><radialGradient id="iB2TyZr" cx="0" cy="0" r="1" gradientTransform="matrix(-3.47103 2.30187 -1.86833 -2.81728 17.116 9.537)" gradientUnits="userSpaceOnUse"><stop offset=".206" class="h76_kibtg"/><stop offset="1" class="s9a9mab_m"/></radialGradient><radialGradient id="igO1v2c" cx="0" cy="0" r="1" gradientTransform="matrix(-.35248 2.04453 -2.42874 -.41872 20.672 7.636)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="uhnyo9buy"/><stop offset="1" class="e1m_j1-ji"/></radialGradient><radialGradient id="iuxX79b" cx="0" cy="0" r="1" gradientTransform="matrix(.73687 1.5513 -.70514 .33494 14.305 7.8)" gradientUnits="userSpaceOnUse"><stop class="dk-6ihb5y"/><stop offset="1" class="rp1-yvvbr"/></radialGradient><radialGradient id="iTDElVb" cx="0" cy="0" r="1" gradientTransform="rotate(81.457 2.924 12.417)scale(.69821 .61247)" gradientUnits="userSpaceOnUse"><stop offset=".263" class="oscuplh_u"/><stop offset="1" class="q-uhenb9x"/></radialGradient><radialGradient id="i2V0P5b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.02407 0 0 -5.34956 19.139 7.187)" gradientUnits="userSpaceOnUse"><stop class="c8rk37lbz"/><stop offset="1" class="yl6fh-g8k"/></radialGradient><radialGradient id="izP3OOb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.00195 -6.62657 0 17.768 3.263)" gradientUnits="userSpaceOnUse"><stop offset=".683" class="n1z0rzy_u"/><stop offset=".957" class="wjzhlgrlu"/></radialGradient><radialGradient id="iJhCFXd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.77565 .95987 0 18.93 6.54)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="aqc0pptzr"/><stop offset="1" class="z_smlmblg"/></radialGradient><radialGradient id="i08iEGb" cx="0" cy="0" r="1" gradientTransform="rotate(-93.012 11.175 -4.464)scale(.63915 .69554)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="kgvcakboi"/><stop offset="1" class="gubsnccaz"/></radialGradient><radialGradient id="i3KbWdc" cx="0" cy="0" r="1" gradientTransform="matrix(.69809 0 0 3.54822 14.691 7.41)" gradientUnits="userSpaceOnUse"><stop class="ijumd0ryg"/><stop offset="1" class="oa_7ckp0d"/></radialGradient><radialGradient id="il3apvb" cx="0" cy="0" r="1" gradientTransform="rotate(-54.413 12.367 -11.017)scale(2.59909 .5887)" gradientUnits="userSpaceOnUse"><stop offset=".451" class="u_gcnab-s"/><stop offset="1" class="v09_-gbcb"/></radialGradient><radialGradient id="iIS3NOb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.39615 -5.92508 6.52667 -1.5379 17.426 9.543)" gradientUnits="userSpaceOnUse"><stop offset=".924" class="noikzrben"/><stop offset="1" class="xx6a4jo2h"/></radialGradient><radialGradient id="irVVYQb" cx="0" cy="0" r="1" gradientTransform="matrix(1.18287 .41691 -.2501 .7096 18.647 4.075)" gradientUnits="userSpaceOnUse"><stop offset=".258" class="xx6a4jo2h"/><stop offset="1" class="noikzrben"/></radialGradient><radialGradient id="i0KkUCc" cx="0" cy="0" r="1" gradientTransform="matrix(.20082 -.35832 1.04273 .58439 16.863 9.09)" gradientUnits="userSpaceOnUse"><stop class="slil38b7x"/><stop offset="1" class="fk4041bff"/></radialGradient><radialGradient id="iEC5GlJ" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.41691 1.67735 0 17.515 9.235)" gradientUnits="userSpaceOnUse"><stop class="hwx_eib-x"/><stop offset="1" class="iazz9lb4s"/></radialGradient><radialGradient id="iOAwwSb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.10132 3.72313 0 14.49 6.272)" gradientUnits="userSpaceOnUse"><stop class="ytx-8cb1b"/><stop offset="1" class="y3fq4efvh"/></radialGradient><radialGradient id="i0lwMKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.10132 3.72313 0 20.326 6.272)" gradientUnits="userSpaceOnUse"><stop class="ugkkbdcpr"/><stop offset="1" class="lty0cjbuw"/></radialGradient><radialGradient id="iJFF6je" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88096 -.71748 .3821 -1.00174 19.89 2.642)" gradientUnits="userSpaceOnUse"><stop class="ofjdtziny"/><stop offset="1" class="znwnmpxvd"/></radialGradient><radialGradient id="ihWKAei" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 6.958 16.041)scale(1.00105 2.31796)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="mvigw0raw"/><stop offset="1" class="tmhk4ybst"/></radialGradient><radialGradient id="i8Yc6Oe" cx="0" cy="0" r="1" gradientTransform="rotate(160.16 8.607 2.822)scale(2.34109 .65158)" gradientUnits="userSpaceOnUse"><stop class="f6hra4b6c"/><stop offset="1" class="gz-wtrqbh"/></radialGradient><radialGradient id="i7XOruc" cx="0" cy="0" r="1" gradientTransform="matrix(1.86157 -2.94749 3.2655 2.06242 14.373 5.308)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="nd6y13bdf"/><stop offset=".233" class="z45w8t_um"/><stop offset="1" class="jm3h91bib"/></radialGradient><radialGradient id="iBANNrb" cx="0" cy="0" r="1" gradientTransform="rotate(13.307 -4.024 85.66)scale(2.01256 1.12556)" gradientUnits="userSpaceOnUse"><stop class="dzh_o9bpc"/><stop offset="1" class="d2ds5d49n"/></radialGradient><radialGradient id="iQGPM3s" cx="0" cy="0" r="1" gradientTransform="rotate(-120.119 11.937 -2.953)scale(2.47683 1.38131)" gradientUnits="userSpaceOnUse"><stop class="zmfxcpbii"/><stop offset="1" class="t1qc5-b8a"/></radialGradient><radialGradient id="inEddid" cx="0" cy="0" r="1" gradientTransform="rotate(-120.695 11.688 -2.87)scale(1.48149 1.06113)" gradientUnits="userSpaceOnUse"><stop offset=".057" class="rk366-b7y"/><stop offset="1" class="m70pgaboa"/></radialGradient><radialGradient id="iTMF5id" cx="0" cy="0" r="1" gradientTransform="rotate(166.509 9.957 2.78)scale(2.85444 3.08575)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="gxl2qg7tq"/><stop offset="1" class="j1i4w4hfh"/></radialGradient><radialGradient id="iLwQJiJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.06787 .22197 -1.01482 -.3103 19.512 3.086)" gradientUnits="userSpaceOnUse"><stop offset=".461" class="howk4obit"/><stop offset="1" class="r0f0npb-q"/></radialGradient><radialGradient id="ic1lNpe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15377 2.17184 -5.60056 -2.97524 19.51 2.61)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="h-4ltow4h"/><stop offset="1" class="rr64b4bjv"/></radialGradient><radialGradient id="i4qfZpQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 .46931 -.7465 0 18.777 6.657)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="inzsxCc" cx="0" cy="0" r="1" gradientTransform="matrix(-.13415 -.17288 .238 -.1847 18.645 6.706)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iqDKNWd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .46934 -.74653 0 16.252 6.657)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iTXuugd" cx="0" cy="0" r="1" gradientTransform="matrix(-.00447 -.2858 .34355 -.00538 16.087 6.785)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ilQYzep" cx="0" cy="0" r="1" gradientTransform="matrix(.36359 1.29763 -1.23804 .34689 20.186 6.665)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="mjrn6wykw"/><stop offset="1" class="l68saw0rr"/></radialGradient><radialGradient id="idC00Ab" cx="0" cy="0" r="1" gradientTransform="matrix(.4557 -.62537 .52418 .38196 20.394 6.98)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="wvh6w6olb"/><stop offset="1" class="hw3g0j7tn"/></radialGradient><radialGradient id="iyifDqA" cx="0" cy="0" r="1" gradientTransform="matrix(-.96892 -.14171 .13932 -.95254 14.672 7.037)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="qbxa2xbde"/><stop offset="1" class="g54wl109l"/><stop offset="1" class="umfyx2bzt"/></radialGradient><filter id="iuoOJLd" width="16.97" height="13.626" x="7.639" y="16.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1299"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.576471 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1299" result="effect2_innerShadow_4002_1299"/></filter><filter id="ily4DRb" width="8.803" height="12.453" x="15.083" y="15.257" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1299" stdDeviation=".5"/></filter><filter id="id5ho4c" width="9.329" height="6.572" x="5.433" y="10.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.564706 0 0 0 0 0.431373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1299"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.454902 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1299" result="effect2_innerShadow_4002_1299"/></filter><filter id="i0jlYKb" width="5.98" height="8.393" x="20.337" y="7.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.733333 0 0 0 0 0.447059 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1299"/></filter><filter id="iBI1mJB" width="1.41" height="1.949" x="24.485" y="7.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.52549 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1299"/></filter><filter id="iTAIxCc" width="6.555" height="7.624" x="14.255" y="10.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.470588 0 0 0 0 0.0117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1299"/></filter><filter id="i24srSv" width="4.212" height="3.197" x="15.358" y="10.239" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.490196 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1299"/></filter><filter id="ijzMPKb" width="11.112" height="3.615" x="10.829" y="25.843" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1299" stdDeviation=".2"/></filter><filter id="iDwZmYb" width="3.297" height="3.17" x="8.245" y="23.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1299" stdDeviation=".2"/></filter><filter id="iC8uqse" width="3.085" height="3.032" x="11.506" y="23.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1299" stdDeviation=".2"/></filter><filter id="iP4XrOa" width="4.07" height="2.867" x="20.64" y="11.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1299" stdDeviation=".25"/></filter><filter id="i8QCrdd" width="1.994" height="6.666" x="24.456" y="8.042" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1299" stdDeviation=".2"/></filter><filter id="imsOW3N" width="2.251" height="3.579" x="23.392" y="7.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1299" stdDeviation=".2"/></filter><filter id="iYmD4md" width="6.781" height="4.219" x="7.807" y="12.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1299" stdDeviation=".25"/></filter><filter id="iBYcDSG" width="6.662" height="7.339" x="14.586" y="3.618" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.611765 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1299"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.54902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1299" result="effect2_innerShadow_4002_1299"/></filter><filter id="iKLraFe" width="3.015" height="3.633" x="15.852" y="5.755" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1299" stdDeviation=".5"/></filter><filter id="iEJJ6rb" width="1.286" height="1.877" x="16.872" y="6.497" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1299" stdDeviation=".05"/></filter><filter id="iELof4v" width="2.362" height="1.121" x="16.334" y="8.413" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1299" stdDeviation=".05"/></filter><filter id="irnpbQc" width="7.446" height="5.045" x="13.791" y="1.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.733333 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1299"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.87451 0 0 0 0 0.678431 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1299" result="effect2_innerShadow_4002_1299"/></filter><filter id="ithEBCc" width="1.395" height=".773" x="18.434" y="4.972" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1299"/></filter><filter id="ickBLfe" width="1.395" height=".764" x="15.394" y="4.981" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1299"/></filter><filter id="ijWvCvd" width="3.72" height="3.369" x="14.042" y="2.462" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1299" stdDeviation=".05"/></filter><filter id="iAxxFnc" width="3.496" height="3.179" x="17.562" y="2.811" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1299" stdDeviation=".05"/></filter><filter id="iI4AO0I" width=".539" height=".487" x="18.31" y="6.361" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1299" stdDeviation=".05"/></filter><filter id="ixN93hb" width=".684" height=".697" x="18.754" y="6.362" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1299" stdDeviation=".1"/></filter><filter id="icJiJQe" width=".739" height=".77" x="16.184" y="6.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1299" stdDeviation=".1"/></filter><filter id="il2Y5ec" width=".612" height=".492" x="15.789" y="6.356" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1299" stdDeviation=".05"/></filter><filter id="iPv7LUX" width=".979" height="1.587" x="13.919" y="6.245" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1299" stdDeviation=".125"/></filter><filter id="iAa7lBc" width="1.048" height="1.601" x="20.135" y="6.235" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1299" stdDeviation=".125"/></filter><linearGradient id="iE8cmhe" x1="6.74" x2="7.001" y1="16.863" y2="16.863" gradientUnits="userSpaceOnUse"><stop class="kqw3-db6l"/><stop offset="1" class="xs-t_4b3c"/></linearGradient><linearGradient id="iFYshWc" x1="10.656" x2="11.312" y1="14.335" y2="16.773" gradientUnits="userSpaceOnUse"><stop class="mi8-q85ch"/><stop offset="1" class="hvuy2t1_w"/></linearGradient><linearGradient id="iLhkbUb" x1="22.218" x2="22.984" y1="14.335" y2="12.945" gradientUnits="userSpaceOnUse"><stop class="vgacj_36t"/><stop offset="1" class="dgl3o-btz"/></linearGradient><linearGradient id="iYcj16d" x1="13.802" x2="15.755" y1="16.085" y2="16.085" gradientUnits="userSpaceOnUse"><stop class="x8wsft-hb"/><stop offset="1" class="m0mihob_v"/></linearGradient><linearGradient id="iFIIACe" x1="11.768" x2="20.875" y1="27.015" y2="28.857" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iFh5wUb" x1="10.518" x2="8.203" y1="25.808" y2="25.435" gradientUnits="userSpaceOnUse"><stop offset=".302" class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iUCaIqe" x1="14.013" x2="13.482" y1="24.145" y2="26.255" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="i2tRpMe" x1="24.406" x2="22.549" y1="14.21" y2="15.252" gradientUnits="userSpaceOnUse"><stop offset=".358" class="g4q-gfbef"/><stop offset="1" class="d9k3vwbhb"/></linearGradient><linearGradient id="ifH5Qfb" x1="24.517" x2="24.517" y1="7.765" y2="10.144" gradientUnits="userSpaceOnUse"><stop offset=".355" class="yvdgctcxa"/><stop offset="1" class="x5d3t83ks"/></linearGradient><linearGradient id="iLWnLac" x1="13.839" x2="13.674" y1="13.023" y2="17.912" gradientUnits="userSpaceOnUse"><stop class="pm5zsub1k"/><stop offset="1" class="u4028acsl"/></linearGradient><linearGradient id="iizx6Hd" x1="20.498" x2="17.98" y1="8.162" y2="8.162" gradientUnits="userSpaceOnUse"><stop class="u0hok99ej"/><stop offset="1" class="tq4h8zb2j"/></linearGradient><linearGradient id="iLeFZgb" x1="17.515" x2="18.009" y1="7.667" y2="7.667" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="hk633lr2o"/></linearGradient><linearGradient id="iwiNTie" x1="16.894" x2="17.515" y1="7.577" y2="7.611" gradientUnits="userSpaceOnUse"><stop class="z_vmdubsa"/><stop offset=".203" class="umam-bfga"/><stop offset="1" class="oanih0n0r"/></linearGradient><linearGradient id="iP5H0pc" x1="17.515" x2="17.515" y1="7.897" y2="8.39" gradientUnits="userSpaceOnUse"><stop class="y-mxywbmo"/><stop offset=".845" class="ed0uty_4k"/></linearGradient><linearGradient id="i0L9IFb" x1="17.515" x2="17.515" y1="6.597" y2="6.84" gradientUnits="userSpaceOnUse"><stop class="f6ma3ccql"/><stop offset="1" class="donh02dkd"/></linearGradient><linearGradient id="iKkR2Kb" x1="20.617" x2="14.761" y1="3.912" y2="3.912" gradientUnits="userSpaceOnUse"><stop class="wbaoi1vzd"/><stop offset="1" class="q37q-zblj"/></linearGradient><linearGradient id="iFv3Zud" x1="19.227" x2="19.045" y1="6.689" y2="6.8" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iopsxJd" x1="16.683" x2="16.501" y1="6.689" y2="6.801" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iIHkqfe" x1="21.238" x2="20.54" y1="6.704" y2="7.963" gradientUnits="userSpaceOnUse"><stop class="zlaemgbzs"/><stop offset="1" class="hye7ay5ht"/></linearGradient><linearGradient id="iRAb0fe" x1="14.131" x2="14.974" y1="7.111" y2="7.038" gradientUnits="userSpaceOnUse"><stop class="dp9jyhbkn"/><stop offset="1" class="a0uazvbjh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-merpeople-medium-light" /></template>
<style>
.a0uazvbjh {
  stop-color: var(--svg-color--bd776c, #BD776C);
}

.aa_qax-gk {
  fill: var(--svg-color--000, #000);
  d: path("M18.482 6.898c0-.164.132-.296.296-.296a.295.295 0 0 1 .263.432h-.523a.3.3 0 0 1-.036-.136");
}

.aqae8acff {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M8.845 24.473c.41.163 1.402.784 2.096 1.97");
}

.aqb4b0ltd {
  d: path("M14.591 6.112a.931.931 0 0 0 .08 1.851a45 45 0 0 1-.08-1.85");
}

.aqc0pptzr {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
}

.bb2fbgrpu {
  d: path("m6.569 15.067l-.755.857a.526.526 0 0 0 .776.71l.554-.583a.384.384 0 0 1 .476-.065l.018.01a.1.1 0 0 1 .019.155l-.317.316a.528.528 0 0 0 .716.774l.557-.479a.2.2 0 0 1 .13-.048h1.765a2.5 2.5 0 0 0 1.64-.613l2.365-2.055v-3.25c-.257.025-.59.285-.723.418l-3.247 3.04a.5.5 0 0 1-.284.132l-3.068.355a.98.98 0 0 0-.622.326");
}

.bv2x_2b0w {
  cx: 16.096px;
  cy: 6.602px;
  rx: 0.225px;
  ry: 0.114px;
}

.c8rk37lbz {
  stop-color: var(--svg-color--ffc59f, #FFC59F);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d2ds5d49n {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
  stop-opacity: 0;
}

.d9k3vwbhb {
  stop-color: var(--svg-color--e7b494, #E7B494);
  stop-opacity: 0;
}

.dgl3o-btz {
  stop-color: var(--svg-color--b97d7e, #B97D7E);
  stop-opacity: 0;
}

.dk-6ihb5y {
  stop-color: var(--svg-color--f8bf95, #F8BF95);
}

.dnnikzlft {
  d: path("m17.294 6.774l-.308 1.063c-.063.22.088.438.301.438h.455c.213 0 .364-.222.301-.438l-.307-1.063c-.066-.236-.373-.236-.442 0");
}

.donh02dkd {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
  stop-opacity: 0;
}

.dp9jyhbkn {
  stop-color: var(--svg-color--c48874, #C48874);
}

.dqd47gnac {
  stop-color: var(--svg-color--ff8e3e, #FF8E3E);
  stop-opacity: 0;
}

.dw0qvsbps {
  stop-color: var(--svg-color--ff8738, #FF8738);
}

.dzh_o9bpc {
  stop-color: var(--svg-color--ffffc7, #FFFFC7);
}

.e1m_j1-ji {
  stop-color: var(--svg-color--da8f78, #DA8F78);
}

.ed0uty_4k {
  stop-color: var(--svg-color--cb8685, #CB8685);
}

.ephtlqrgv {
  stop-color: var(--svg-color--ad674f, #AD674F);
  stop-opacity: 0;
}

.eq10tutlo {
  d: path("M18.74 6.49c.037.05-.04.11-.127.175c-.088.066-.153.112-.19.062c-.036-.049.005-.142.092-.207c.088-.065.188-.078.225-.03");
}

.es_ec_zku {
  d: path("M20.327 7.91a.95.95 0 0 0 .523-.178v.539c0 .516-.308.976-.776 1.167q.15-.316.2-.682z");
}

.evfll0tzs {
  d: path("M14.703 7.91a.95.95 0 0 1-.524-.178v.539c0 .516.308.976.776 1.167a2.4 2.4 0 0 1-.2-.682z");
}

.f6hra4b6c {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
}

.f6ma3ccql {
  stop-color: var(--svg-color--e0a78c, #E0A78C);
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.fk4041bff {
  stop-color: var(--svg-color--d0978e, #D0978E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g10datb6e {
  fill: var(--svg-color--e8ae8f, #E8AE8F);
  d: path("M19.57 10.487c-1.778-.422-3.256-.227-4.111.002l.002.015v.778a2.054 2.054 0 1 0 4.107 0v-.778z");
}

.g1dp7ccjz {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
  stop-opacity: 0;
}

.g4q-gfbef {
  stop-color: var(--svg-color--e7b494, #E7B494);
}

.g54wl109l {
  stop-color: var(--svg-color--c77937, #C77937);
}

.gejm97-ji {
  d: path("m23.587 12.28l-2.844-1.464l-.406 2.718l3.348 1.708a1.8 1.8 0 0 0 1.84-.121c.527-.363.82-.979.79-1.618c-.06-1.273-.081-2.688-.103-3.586v-1.39a.531.531 0 0 0-1.063 0v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.238-.2c-.125-.129-.17-.309-.17-.488v-.667a.531.531 0 1 0-1.062 0v1.201a1 1 0 0 0 .235.644l.373.444a.2.2 0 0 1 .046.151c-.065.582-.148 1.353-.197 1.853a.202.202 0 0 1-.293.16");
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gn_mwgb8p {
  stop-color: var(--svg-color--e6bc9b, #E6BC9B);
  stop-opacity: 0;
}

.go_35jbir {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.898 6.224c.378 0 .697.26.784.613a.16.16 0 0 1-.155.197h-1.291a.133.133 0 0 1-.131-.157a.81.81 0 0 1 .793-.653");
}

.gubsnccaz {
  stop-color: var(--svg-color--c2847c, #C2847C);
  stop-opacity: 0;
}

.gv9be6ybc {
  stop-color: var(--svg-color--e15c10, #E15C10);
  stop-opacity: 0;
}

.gxl2qg7tq {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
  stop-opacity: 0;
}

.gz-wtrqbh {
  stop-color: var(--svg-color--fffcbe, #FFFCBE);
  stop-opacity: 0;
}

.h-4ltow4h {
  stop-color: var(--svg-color--e1b395, #E1B395);
  stop-opacity: 0;
}

.h76_kibtg {
  stop-color: var(--svg-color--9d5b42, #9D5B42);
}

.h8_lbz_nz {
  stop-color: var(--svg-color--4edd83, #4EDD83);
}

.hhs_ktgwp {
  fill: var(--svg-color--daa789, #DAA789);
  d: path("M25.683 7.995h-.003a.53.53 0 0 0-.53.532v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.24-.2c-.124-.129-.169-.309-.169-.488V7.95l.56-.558a.44.44 0 0 1 .638.604");
}

.hk633lr2o {
  stop-color: var(--svg-color--fecaa8, #FECAA8);
}

.howk4obit {
  stop-color: var(--svg-color--ffed93, #FFED93);
}

.hvuy2t1_w {
  stop-color: var(--svg-color--c78d89, #C78D89);
}

.hw3g0j7tn {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
  stop-opacity: 0;
}

.hwx_eib-x {
  stop-color: var(--svg-color--89024e, #89024E);
}

.hye7ay5ht {
  stop-color: var(--svg-color--e0a48c, #E0A48C);
}

.i6tnjcu8m {
  d: path("M13.356 19.136c0-1.425.76-2.101 1.16-2.242l5.66-.34c1.61.719 2.954 2.781 3.141 5.281c.188 2.5-.203 4.953-2.265 6.563c-1.65 1.287-3.959 1.552-4.938 1.531h-2.472c-2.625 0-3.247-1.89-3.356-2.297a11 11 0 0 0-.184-.598a.43.43 0 0 0-.221-.26c-.528-.244-1.52-.486-1.947-1.388a3.1 3.1 0 0 1-.28-1.63c.022-.213.232-.344.441-.296c.52.119.95.252 1.57.567a3.4 3.4 0 0 1 1.237 1.226c.065.11.238.112.304.003c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.765-.748 2.275-1.198 2.513c-.288.131-.62.277-.865.388c-.14.063-.21.223-.141.36c.474.956 1.468.869 2.858.869c1.851 0 2.96-1.324 2.843-2.723c-.062-1.812-1.562-2.515-2.57-3.148c-.523-.329-2.055-1.145-2.055-2.926");
}

.iazz9lb4s {
  stop-color: var(--svg-color--87004d, #87004D);
}

.if2-x0_3s {
  d: path("M21.317 26.71c0-5.343-3.922-7.968-5.234-9l3.25-1.453c1.125.521 3.035 2.358 3.453 5.11c.484 3.187-.927 4.927-1.469 5.343");
}

.ijumd0ryg {
  stop-color: var(--svg-color--dba085, #DBA085);
}

.izop3bc_a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M11.429 26.909c-.007.65.436 1.948 2.266 1.948h3.177c1.01-.014 3.317-.516 4.469-2.414");
}

.j1i4w4hfh {
  stop-color: var(--svg-color--ebcd93, #EBCD93);
}

.jkj1op9ie {
  stop-color: var(--svg-color--4edd83, #4EDD83);
  stop-opacity: 0;
}

.jleiqdg7d {
  stop-color: var(--svg-color--d59a75, #D59A75);
}

.jm3h91bib {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
  stop-opacity: 0;
}

.jq26pbbuc {
  fill: var(--svg-color--ebb690, #EBB690);
  d: path("m23.587 12.28l-2.844-1.464l-.406 2.718l3.348 1.708a1.8 1.8 0 0 0 1.84-.121c.527-.363.82-.979.79-1.618c-.06-1.273-.081-2.688-.103-3.586v-1.39a.531.531 0 0 0-1.063 0v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.238-.2c-.125-.129-.17-.309-.17-.488v-.667a.531.531 0 1 0-1.062 0v1.201a1 1 0 0 0 .235.644l.373.444a.2.2 0 0 1 .046.151c-.065.582-.148 1.353-.197 1.853a.202.202 0 0 1-.293.16");
}

.kgvcakboi {
  stop-color: var(--svg-color--c2847c, #C2847C);
}

.kqw3-db6l {
  stop-color: var(--svg-color--dea48a, #DEA48A);
}

.l68saw0rr {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
}

.lfurq4bwg {
  d: path("M18.778 6.381a.516.516 0 0 1 .498.653h-.998a.518.518 0 0 1 .5-.652");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lijsgbc3d {
  d: path("m17.649 3.939l-.038-.08a.38.38 0 0 0-.356-.241h-.736a1.944 1.944 0 0 0-1.933 1.954v.16c-.197-.15-.444-.466-.444-.977c0-.62.452-.933.74-1.133c.082-.056.15-.104.191-.147l.058-.06c.202-.215.563-.597 1.192-.764c.18-.047.36-.074.53-.087c.472-.035.808.377.808.85v.517z");
}

.lk8uk6bqv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m21.39 12.46l2.57 1.367");
}

.lrtdxszpp {
  d: path("M19.57 10.487c-1.778-.422-3.256-.227-4.111.002l.002.015v.778a2.054 2.054 0 1 0 4.107 0v-.778z");
}

.lty0cjbuw {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
  stop-opacity: 0;
}

.m0mihob_v {
  stop-color: var(--svg-color--fb711e, #FB711E);
  stop-opacity: 0;
}

.m70pgaboa {
  stop-color: var(--svg-color--dfb086, #DFB086);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mi8-q85ch {
  stop-color: var(--svg-color--d5a280, #D5A280);
}

.mjkanubbn {
  fill: var(--svg-color--b57562, #B57562);
  d: path("M14.6 6.495a.553.553 0 0 0 .049 1.087q-.03-.544-.048-1.087");
}

.mjrn6wykw {
  stop-color: var(--svg-color--ce8d79, #CE8D79);
  stop-opacity: 0;
}

.mvigw0raw {
  stop-color: var(--svg-color--ddca94, #DDCA94);
}

.n1z0rzy_u {
  stop-color: var(--svg-color--c98d87, #C98D87);
  stop-opacity: 0;
}

.n2hacibqs {
  fill: var(--svg-color--bb7b69, #BB7B69);
  d: path("M6.74 16.107a.486.486 0 0 1 .973 0v.775a.486.486 0 1 1-.973 0z");
}

.nd6y13bdf {
  stop-color: var(--svg-color--d5a088, #D5A088);
}

.noikzrben {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
  stop-opacity: 0;
}

.nqt5hcbes {
  stop-color: var(--svg-color--e15c10, #E15C10);
}

.nv3ul6l6h {
  d: path("M14.724 8.787a2.265 2.265 0 0 0 2.247 1.97h1.092c1.138 0 2.099-.84 2.248-1.97c.068-1.09.136-2.175.187-3.264a.84.84 0 0 0-.798-.829h-.81a1.4 1.4 0 0 1-1.279-.834a.38.38 0 0 0-.356-.242h-.736a1.944 1.944 0 0 0-1.933 1.954c0 1.077.067 2.136.138 3.215");
}

.o1lmyoq6y {
  fill: var(--svg-color--c48377, #C48377);
  d: path("m17.266 6.993l-.4.958c-.06.218.081.437.28.437h.426c.2 0 .34-.222.281-.437l-.287-1.064c-.062-.235-.236-.13-.3.106");
}

.oa_7ckp0d {
  stop-color: var(--svg-color--dba085, #DBA085);
  stop-opacity: 0;
}

.oanih0n0r {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ofjdtziny {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
}

.ojcsn4b4p {
  d: path("M17.515 8.863c-.294 0-.57-.07-.802-.19c-.079-.04-.164.049-.114.12c.194.295.531.49.916.49c.384 0 .722-.195.916-.49c.05-.074-.036-.16-.115-.12a1.7 1.7 0 0 1-.801.19");
}

.ojz-wi0ni {
  cx: 16.096px;
  cy: 6.602px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.225px;
  ry: 0.114px;
}

.ona8jmyio {
  d: path("M16.251 6.381a.516.516 0 0 0-.497.653h.997a.52.52 0 0 0-.5-.652");
}

.oscuplh_u {
  stop-color: var(--svg-color--d79b77, #D79B77);
}

.otx7-wbah {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M19.674 5.464a1.1 1.1 0 0 0-.398-.238c-.176-.056-.396-.07-.701-.033a.16.16 0 1 0 .039.318c.278-.034.449-.016.566.02a.8.8 0 0 1 .283.175a.16.16 0 1 0 .211-.242");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkl2bklef {
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M16.748 8.606c.22.116.485.182.767.182c.285 0 .546-.066.767-.182a.164.164 0 0 1 .194.032a.155.155 0 0 1 .017.197m-1.745-.229l1.683.188m-1.683-.188a.16.16 0 0 0-.195.034a.154.154 0 0 0-.016.196m.211-.23l-.15.188m1.895.041l-.062-.041m.062.041l-.062-.041m.062.041a1.17 1.17 0 0 1-.978.523c-.41 0-.771-.208-.978-.522m1.894-.042a1.1 1.1 0 0 1-1.832 0m-.062.042l.062-.042m-.062.042l.062-.042");
}

.pm5zsub1k {
  stop-color: var(--svg-color--d99e8b, #D99E8B);
}

.pygktylau {
  stop-color: var(--svg-color--ff8e3e, #FF8E3E);
}

.q-uhenb9x {
  stop-color: var(--svg-color--d79b77, #D79B77);
  stop-opacity: 0;
}

.q28fyhb-x {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.74 6.49c.037.05-.04.11-.127.175c-.088.066-.153.112-.19.062c-.036-.049.005-.142.092-.207c.088-.065.188-.078.225-.03");
}

.q37q-zblj {
  stop-color: var(--svg-color--e7c991, #E7C991);
}

.qbxa2xbde {
  stop-color: var(--svg-color--dca187, #DCA187);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_cv6ppfn {
  d: path("M6.74 16.107a.486.486 0 0 1 .973 0v.775a.486.486 0 1 1-.973 0z");
}

.r0f0npb-q {
  stop-color: var(--svg-color--ffed93, #FFED93);
  stop-opacity: 0;
}

.rk366-b7y {
  stop-color: var(--svg-color--dfb086, #DFB086);
}

.rp1-yvvbr {
  stop-color: var(--svg-color--dc998e, #DC998E);
}

.rr64b4bjv {
  stop-color: var(--svg-color--e1b395, #E1B395);
}

.rtl5rdb5z {
  stop-color: var(--svg-color--ad674f, #AD674F);
}

.ry_er4bde {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m13.839 13.023l-2.97 2.719H8.558");
}

.s536pit3i {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
}

.s9a9mab_m {
  stop-color: var(--svg-color--b26d4f, #B26D4F);
  stop-opacity: 0;
}

.sc66hv5ah {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.132 6.224a.81.81 0 0 0-.784.613c-.026.1.051.197.155.197h1.29a.133.133 0 0 0 .132-.157a.81.81 0 0 0-.793-.653");
}

.sky6ld7vt {
  fill: var(--svg-color--e6aa8b, #E6AA8B);
  d: path("M20.385 7.586q.034-.55.064-1.1a.553.553 0 0 1-.064 1.1");
}

.slil38b7x {
  stop-color: var(--svg-color--d0978e, #D0978E);
}

.ss0po6bla {
  fill: var(--svg-color--a06937, #A06937);
  d: path("M15.542 5.4a1.6 1.6 0 0 1 1.006-.208a.16.16 0 1 1-.04.32a1.28 1.28 0 0 0-.845.192l-.01.007h-.001a.16.16 0 0 1-.196-.253z");
}

.ss6kf5hyw {
  stop-color: var(--svg-color--d59a75, #D59A75);
  stop-opacity: 0;
}

.sxbkuzihq {
  stroke: var(--svg-color--ecbb9b, #ECBB9B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M25.156 14.007v-3.781l.594-.406V8.742");
}

.t_y7qszcu {
  stop-color: var(--svg-color--b4737f, #B4737F);
}

.t1qc5-b8a {
  stop-color: var(--svg-color--e4b78d, #E4B78D);
  stop-opacity: 0;
}

.t4q17cblu {
  stop-color: var(--svg-color--c48460, #C48460);
  stop-opacity: 0;
}

.td6euhb6l {
  fill: var(--svg-color--35bb78, #35BB78);
  d: path("M13.356 19.136c0-1.425.76-2.101 1.16-2.242l5.66-.34c1.61.719 2.954 2.781 3.141 5.281c.188 2.5-.203 4.953-2.265 6.563c-1.65 1.287-3.959 1.552-4.938 1.531h-2.472c-2.625 0-3.247-1.89-3.356-2.297a11 11 0 0 0-.184-.598a.43.43 0 0 0-.221-.26c-.528-.244-1.52-.486-1.947-1.388a3.1 3.1 0 0 1-.28-1.63c.022-.213.232-.344.441-.296c.52.119.95.252 1.57.567a3.4 3.4 0 0 1 1.237 1.226c.065.11.238.112.304.003c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.765-.748 2.275-1.198 2.513c-.288.131-.62.277-.865.388c-.14.063-.21.223-.141.36c.474.956 1.468.869 2.858.869c1.851 0 2.96-1.324 2.843-2.723c-.062-1.812-1.562-2.515-2.57-3.148c-.523-.329-2.055-1.145-2.055-2.926");
}

.tmhk4ybst {
  stop-color: var(--svg-color--ddca94, #DDCA94);
  stop-opacity: 0;
}

.tq4h8zb2j {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
  stop-opacity: 0;
}

.u_gcnab-s {
  stop-color: var(--svg-color--b67459, #B67459);
}

.u0hok99ej {
  stop-color: var(--svg-color--f7c29d, #F7C29D);
}

.u4028acsl {
  stop-color: var(--svg-color--d99e8b, #D99E8B);
  stop-opacity: 0;
}

.uc2wxkyln {
  stop-color: var(--svg-color--40b87c, #40B87C);
  stop-opacity: 0;
}

.ugkkbdcpr {
  stop-color: var(--svg-color--f6cb9c, #F6CB9C);
}

.uhnyo9buy {
  stop-color: var(--svg-color--f7bf94, #F7BF94);
}

.uk34iobtb {
  d: path("M16.723 6.837c0-.167-.136-.278-.172-.311l-.167.16l.102.21z");
}

.umam-bfga {
  stop-color: var(--svg-color--d29879, #D29879);
}

.umfyx2bzt {
  stop-color: var(--svg-color--dca187, #DCA187);
}

.uqhx2ybtm {
  stop-color: var(--svg-color--b4737f, #B4737F);
  stop-opacity: 0;
}

.uwj5xnfkj {
  d: path("m20.53 5.89l-.017-.365A.85.85 0 0 0 19.7 4.7h-.81a1.4 1.4 0 0 1-1.228-.729s.416-1.202 1.108-1.047c.505.114 1.045.293 1.459.563c1.009.658.832 1.844.3 2.403");
}

.uwupv_ztt {
  d: path("M14.255 10.891c0-.039.022-.074.058-.09c.2-.089.63-.262 1.09-.346a.05.05 0 0 1 .058.049v.778a2.054 2.054 0 1 0 4.107 0v-.778a.05.05 0 0 1 .058-.05c.462.085.92.259 1.125.348c.036.015.058.05.058.09v6.386a.6.6 0 0 1-.6.6h-5.354a.6.6 0 0 1-.6-.6z");
}

.v09_-gbcb {
  stop-color: var(--svg-color--b67459, #B67459);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vgacj_36t {
  stop-color: var(--svg-color--b97d7e, #B97D7E);
}

.vr22ulb0g {
  d: path("M20.362 7.963q.058-.922.107-1.846a.931.931 0 0 1-.107 1.846");
}

.vy9mn1ofo {
  stop-color: var(--svg-color--d38f77, #D38F77);
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

.w7is8p55o {
  stop-color: var(--svg-color--d38f77, #D38F77);
  stop-opacity: 0;
}

.wbaoi1vzd {
  stop-color: var(--svg-color--fff6b9, #FFF6B9);
}

.wjzhlgrlu {
  stop-color: var(--svg-color--bd7872, #BD7872);
}

.wvh6w6olb {
  stop-color: var(--svg-color--e3a17b, #E3A17B);
}

.wxsmjrbxz {
  stop-color: var(--svg-color--e6bc9b, #E6BC9B);
}

.x_l-rmbrg {
  d: path("M19.238 6.83a.5.5 0 0 0-.134-.268l-.15.165l.067.132z");
}

.x5d3t83ks {
  stop-color: var(--svg-color--e5b196, #E5B196);
  stop-opacity: 0;
}

.x8wsft-hb {
  stop-color: var(--svg-color--db6229, #DB6229);
}

.xeiaglb6x {
  d: path("M20.323 3.345c.297.102.564.31.733.608c.27.475.23 1.042-.061 1.461a.9.9 0 0 0-.157.506v.687a1 1 0 0 0-.386-.155l.046-.93a.84.84 0 0 0-.798-.827h-.81a1.4 1.4 0 0 1-1.28-.835a.38.38 0 0 0-.355-.242h-.736a1.944 1.944 0 0 0-1.933 1.955l.018.889a1 1 0 0 0-.417.152V5.92a.9.9 0 0 0-.156-.506A1.38 1.38 0 0 1 13.948 4c.168-.32.441-.543.751-.652c.332-.118.614-.341.801-.642a1.345 1.345 0 0 1 1.672-.528c.221.096.47.096.69 0a1.345 1.345 0 0 1 1.678.546c.179.295.458.51.783.62");
}

.xs-t_4b3c {
  stop-color: var(--svg-color--bc7c6a, #BC7C6A);
  stop-opacity: 0;
}

.xx6a4jo2h {
  stop-color: var(--svg-color--c17f5f, #C17F5F);
}

.y_rv32tfd {
  stop-color: var(--svg-color--40b87c, #40B87C);
}

.y-mxywbmo {
  stop-color: var(--svg-color--cb8685, #CB8685);
  stop-opacity: 0;
}

.y3fq4efvh {
  stop-color: var(--svg-color--e7b286, #E7B286);
  stop-opacity: 0;
}

.yafg_whjr {
  stop-color: var(--svg-color--eb6820, #EB6820);
}

.yefommbih {
  fill: var(--svg-color--000, #000);
  d: path("M16.547 6.898a.294.294 0 0 0-.296-.296a.294.294 0 0 0-.263.432h.524a.3.3 0 0 0 .035-.136");
}

.yl6fh-g8k {
  stop-color: var(--svg-color--c8917d, #C8917D);
}

.yr50mjbls {
  d: path("M25.683 7.995h-.003a.53.53 0 0 0-.53.532v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.24-.2c-.124-.129-.169-.309-.169-.488V7.95l.56-.558a.44.44 0 0 1 .638.604");
}

.ytx-8cb1b {
  stop-color: var(--svg-color--e7b286, #E7B286);
}

.yvdgctcxa {
  stop-color: var(--svg-color--e5b196, #E5B196);
}

.z_smlmblg {
  stop-color: var(--svg-color--e4a38d, #E4A38D);
  stop-opacity: 0;
}

.z_vmdubsa {
  stop-color: var(--svg-color--d29879, #D29879);
  stop-opacity: 0.915;
}

.z45w8t_um {
  stop-color: var(--svg-color--e4b99b, #E4B99B);
}

.zk5jp9hiu {
  stop-color: var(--svg-color--c48460, #C48460);
}

.zlaemgbzs {
  stop-color: var(--svg-color--f8c5a2, #F8C5A2);
}

.zmfxcpbii {
  stop-color: var(--svg-color--e3b593, #E3B593);
}

.znwnmpxvd {
  stop-color: var(--svg-color--ffffc1, #FFFFC1);
  stop-opacity: 0;
}

</style>
