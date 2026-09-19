<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iuPpOrM)"><path class="td6euhb6l"/></g><path fill="url(#itsSeme)" class="i6tnjcu8m"/><g filter="url(#imakbQd)"><path fill="url(#icQ8Rgb)" class="if2-x0_3s"/></g><path class="ldriecc8f"/><path fill="url(#iCXvyie)" class="x5s8xacrq"/><path fill="url(#iT0y2ld)" class="x5s8xacrq"/><g filter="url(#i3dBtev)"><path fill="url(#iXkaSgb)" class="bb2fbgrpu"/></g><g filter="url(#i4kYmWz)"><path class="esot3dbcv"/></g><g filter="url(#iiCLrqs)"><path class="d2nb27bcb"/><path fill="url(#iIttgtb)" class="yr50mjbls"/><path fill="url(#itpGGUZ)" class="yr50mjbls"/></g><path class="kkfk0mbtk"/><path fill="url(#ilDM90d)" class="c4xzopb1o"/><g filter="url(#iM8y4uc)"><path fill="url(#i5hBc1c)" class="uwupv_ztt"/><path fill="url(#iskeGDX)" class="uwupv_ztt"/></g><path fill="url(#iYcj16d)" class="uwupv_ztt"/><path fill="url(#iZqERtb)" class="uwupv_ztt"/><g filter="url(#iuiCrpe)"><path stroke="url(#iFIIACe)" class="izop3bc_a"/></g><g filter="url(#iaos6ge)"><path stroke="url(#iFh5wUb)" class="xwn-kfb_d"/></g><g filter="url(#irZOojI)"><path stroke="url(#iUCaIqe)" class="w-8ib2bba"/></g><path fill="url(#izcfrhe)" class="km_8uqbsr"/><path fill="url(#iy3nRpe)" class="ifesvnbka"/><g filter="url(#ifZz61d)"><path fill="url(#iNISjme)" class="pnx4wsrrl"/></g><path fill="url(#izZlefc)" class="pnx4wsrrl"/><path fill="url(#iAonLic)" class="pnx4wsrrl"/><path fill="url(#iBbrqqb)" class="pnx4wsrrl"/><path fill="url(#iEkeAnb)" class="pnx4wsrrl"/><path fill="url(#i3OcVry)" class="pnx4wsrrl"/><path fill="url(#iCOqqRb)" class="pnx4wsrrl"/><path fill="url(#iSKXkBd)" class="pnx4wsrrl"/><path fill="url(#iy8ZHje)" class="pnx4wsrrl"/><path fill="url(#ikJycPd)" class="pnx4wsrrl"/><g filter="url(#iuus1xd)"><path class="u8c66dblr"/></g><g filter="url(#izcxafZ)"><path class="ziaw6bd6t"/><path fill="url(#iNEEcmc)" class="ulx2x9bfe"/><path fill="url(#idZkzUd)" class="ulx2x9bfe"/><path fill="url(#iie3RLd)" class="ulx2x9bfe"/><path fill="url(#iekPOLd)" class="ulx2x9bfe"/><path fill="url(#iEmJvSc)" class="ulx2x9bfe"/></g><g filter="url(#i5h7iFe)"><path stroke="url(#iVVHgvd)" class="pl3p6ccjp"/></g><path fill="url(#iRUgkzc)" class="avt3f3myu"/><g filter="url(#iWVtF3d)"><path fill="url(#itqgEpX)" class="q04qidcke"/><path fill="url(#iVUnote)" class="q04qidcke"/><path fill="url(#ifmSJId)" class="q04qidcke"/><path fill="url(#iIVt5bb)" class="q04qidcke"/><path fill="url(#i8TCcXb)" class="q04qidcke"/></g><g filter="url(#ipXmFgb)"><path class="ho6zccbxe"/></g><g filter="url(#iJEsIId)"><path class="qn0bf-lre"/></g><g filter="url(#iVkHEtc)"><path class="q522thbho"/><path fill="url(#iDtfTjB)" class="f_mg0nbwh"/><path fill="url(#i8ZQeCK)" class="f_mg0nbwh"/></g><g filter="url(#ixE4TBS)"><path class="mg1i52lci"/><path fill="url(#iVVV0ed)" class="lityuf0_c"/></g><path class="pck9pabxc"/><path fill="url(#iwhfUve)" class="jyu3lwbui"/><path class="uk9jj-hst"/><g filter="url(#iLyWMHL)"><path class="p2zt-able"/><path fill="url(#iOSHPBc)" class="rh8nd8b0x"/></g><g filter="url(#iKlCOOj)"><path fill="url(#iT8GEBc)" class="hb_ogew6a"/></g><path class="wtcnn1bts"/><path fill="url(#iCc1IFP)" class="mqmfq5v9o"/><path class="dtfbqac-i"/><g filter="url(#iXQJxfc)"><path fill="url(#iSaoYNe)" class="f0qkucb4f"/></g><g filter="url(#iZINzVd)"><ellipse transform="rotate(-27.914 16.124 6.566)" class="onateobba"/><ellipse fill="url(#iN4oxGb)" transform="rotate(-27.914 16.124 6.566)" class="lxf-5k96n"/></g><path fill="url(#ic46cSt)" class="ukvl8u6wk"/><path fill="url(#ijEZmFJ)" class="ukvl8u6wk"/><path fill="url(#iqLJoPv)" class="ukvl8u6wk"/><path fill="url(#ioHRpMD)" class="ukvl8u6wk"/><path fill="url(#iatDoXc)" class="h5cqi1vlg"/><path fill="url(#iPsJYqd)" class="h5cqi1vlg"/><g filter="url(#iHCCAjm)"><path fill="url(#isOKAXT)" class="b1eox6-wm"/></g><g filter="url(#ijjkC2b)"><path fill="url(#iKkQHQe)" class="rppkiibbv"/></g><g filter="url(#inX08tw)"><path class="h3u9zlbhg"/></g><g filter="url(#iGsehIb)"><path stroke="url(#ivt5WEe)" class="lk8uk6bqv"/></g><g filter="url(#iAR2XEb)"><path class="zoxoeibbu"/></g><g filter="url(#iHSPHjc)"><path stroke="url(#iPdUGZb)" class="w-3uv5bmy"/></g><defs><radialGradient id="itsSeme" cx="0" cy="0" r="1" gradientTransform="rotate(-17.313 87.822 -23.113)scale(13.0953 16.0195)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="g1dp7ccjz"/><stop offset="1" class="s536pit3i"/></radialGradient><radialGradient id="icQ8Rgb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.61906 1.93752 -6.36477 -11.88867 22.702 20.617)" gradientUnits="userSpaceOnUse"><stop class="h8_lbz_nz"/><stop offset="1" class="jkj1op9ie"/></radialGradient><radialGradient id="iT0y2ld" cx="0" cy="0" r="1" gradientTransform="rotate(-49.88 21.65 1.225)scale(1.27707 1.06889)" gradientUnits="userSpaceOnUse"><stop offset=".693" class="h9204bbax"/><stop offset="1" class="apsk66b5a"/></radialGradient><radialGradient id="iIttgtb" cx="0" cy="0" r="1" gradientTransform="matrix(-.57032 .46875 -.2011 -.24468 25.71 7.406)" gradientUnits="userSpaceOnUse"><stop class="byz6es45f"/><stop offset="1" class="ufco8ab6y"/></radialGradient><radialGradient id="itpGGUZ" cx="0" cy="0" r="1" gradientTransform="rotate(-124.275 14.957 -2.267)scale(.70056 .17546)" gradientUnits="userSpaceOnUse"><stop class="gt631cbpo"/><stop offset="1" class="o57ll2bvc"/></radialGradient><radialGradient id="ilDM90d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.89062 2.15625 -2.03255 -2.7248 17.192 9.788)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="lbreh1bfv"/><stop offset="1" class="v_stkcbzd"/></radialGradient><radialGradient id="i5hBc1c" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.46875 -5.71107 0 19.177 12.742)" gradientUnits="userSpaceOnUse"><stop offset=".377" class="dw0qvsbps"/><stop offset="1" class="yafg_whjr"/></radialGradient><radialGradient id="iskeGDX" cx="0" cy="0" r="1" gradientTransform="rotate(58.499 -1.805 23.135)scale(1.85402 1.92266)" gradientUnits="userSpaceOnUse"><stop offset=".221" class="pygktylau"/><stop offset="1" class="dqd47gnac"/></radialGradient><radialGradient id="iZqERtb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.00003 -7.0781 9.3879 -5.30536 19.333 16.96)" gradientUnits="userSpaceOnUse"><stop offset=".786" class="gv9be6ybc"/><stop offset="1" class="nqt5hcbes"/></radialGradient><radialGradient id="izcfrhe" cx="0" cy="0" r="1" gradientTransform="matrix(.42967 1.15888 -1.37666 .51042 20.26 7.687)" gradientUnits="userSpaceOnUse"><stop offset=".215" class="rra4r9bnq"/><stop offset="1" class="pft2s7y0a"/></radialGradient><radialGradient id="iy3nRpe" cx="0" cy="0" r="1" gradientTransform="matrix(.84724 .26628 -.82148 2.6138 14.057 7.968)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset=".746" class="q53v6mhsp"/></radialGradient><radialGradient id="iNISjme" cx="0" cy="0" r="1" gradientTransform="matrix(-2.99992 0 0 -5.30683 19.143 7.147)" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="ahguepbtf"/></radialGradient><radialGradient id="iAonLic" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.55542 -10.6562 0 17.75 5.132)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="c2_7179_n"/><stop offset="1" class="em3vbzhtc"/></radialGradient><radialGradient id="iBbrqqb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.65896 .81547 0 18.936 6.393)" gradientUnits="userSpaceOnUse"><stop offset=".325" class="asp-974pn"/><stop offset="1" class="l2dudh2nh"/></radialGradient><radialGradient id="iEkeAnb" cx="0" cy="0" r="1" gradientTransform="matrix(.00226 -.62793 .68334 .00245 16.212 6.42)" gradientUnits="userSpaceOnUse"><stop offset=".378" class="ww86j5--q"/><stop offset="1" class="mfkgssbjj"/></radialGradient><radialGradient id="i3OcVry" cx="0" cy="0" r="1" gradientTransform="rotate(176.388 9.63 4.164)scale(4.88499 12.4787)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="o-j_7gbpq"/><stop offset="1" class="j-n0q842a"/></radialGradient><radialGradient id="iCOqqRb" cx="0" cy="0" r="1" gradientTransform="matrix(2.33723 -1.51968 .55631 .8556 14.395 4.665)" gradientUnits="userSpaceOnUse"><stop offset=".38" class="xjcxgac6b"/><stop offset="1" class="psn4zabca"/></radialGradient><radialGradient id="iSKXkBd" cx="0" cy="0" r="1" gradientTransform="rotate(95.368 7.866 12.166)scale(1.43943 .5754)" gradientUnits="userSpaceOnUse"><stop offset=".245" class="x73tbcc6t"/><stop offset="1" class="sbhjtg7pq"/></radialGradient><radialGradient id="iy8ZHje" cx="0" cy="0" r="1" gradientTransform="rotate(121.159 8.253 7.481)scale(1.93324 1.59604)" gradientUnits="userSpaceOnUse"><stop offset=".078" class="f28ypccjc"/><stop offset="1" class="zkb-swu-c"/></radialGradient><radialGradient id="idZkzUd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .14008 -.44023 0 17.8 7.927)" gradientUnits="userSpaceOnUse"><stop class="txgsuxr-c"/><stop offset="1" class="a4rldd3-z"/></radialGradient><radialGradient id="iekPOLd" cx="0" cy="0" r="1" gradientTransform="rotate(155.369 8.104 5.75)scale(.96026 1.54321)" gradientUnits="userSpaceOnUse"><stop offset=".714" class="p8isx8b7k"/><stop offset="1" class="w37r5utea"/></radialGradient><radialGradient id="iRUgkzc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.41358 1.66395 0 17.532 9.177)" gradientUnits="userSpaceOnUse"><stop class="w189cfbhy"/><stop offset="1" class="z5a_p6x5j"/></radialGradient><radialGradient id="iVUnote" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.00918 5.08098 0 14.531 5.487)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="ibt06e6rm"/><stop offset="1" class="k45xjwbmq"/></radialGradient><radialGradient id="ifmSJId" cx="0" cy="0" r="1" gradientTransform="rotate(-87.401 13.425 -7.513)scale(1.44327 2.55719)" gradientUnits="userSpaceOnUse"><stop class="c98z413ze"/><stop offset="1" class="ovvtmacpn"/></radialGradient><radialGradient id="iIVt5bb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35358 -.89025 .6535 -.9936 19.889 2.637)" gradientUnits="userSpaceOnUse"><stop class="wyv1gnbxf"/><stop offset="1" class="z6d-f52gr"/></radialGradient><radialGradient id="i8TCcXb" cx="0" cy="0" r="1" gradientTransform="rotate(58.465 6.967 16.062)scale(.99306 2.29944)" gradientUnits="userSpaceOnUse"><stop offset=".287" class="qco-2_b3r"/><stop offset="1" class="zwo50zm6y"/></radialGradient><radialGradient id="iDtfTjB" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26308 0 0 -.46878 17.677 3.02)" gradientUnits="userSpaceOnUse"><stop class="axstwemrb"/><stop offset="1" class="ez41_pbnb"/></radialGradient><radialGradient id="i8ZQeCK" cx="0" cy="0" r="1" gradientTransform="matrix(1.8467 -2.92394 3.23942 2.04595 14.416 5.282)" gradientUnits="userSpaceOnUse"><stop offset=".093" class="hnw0p1utu"/><stop offset=".311" class="dwl_ftd7p"/><stop offset="1" class="fch_lgr5q"/></radialGradient><radialGradient id="iVVV0ed" cx="0" cy="0" r="1" gradientTransform="matrix(1.86394 .21786 -.09122 .7804 18.535 4.361)" gradientUnits="userSpaceOnUse"><stop class="unyhdjbdq"/><stop offset="1" class="w0a4mmrgb"/></radialGradient><radialGradient id="iwhfUve" cx="0" cy="0" r="1" gradientTransform="matrix(0 .46556 -.74053 0 18.784 6.62)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iOSHPBc" cx="0" cy="0" r="1" gradientTransform="matrix(-.13308 -.17149 .2361 -.18323 18.654 6.67)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iCc1IFP" cx="0" cy="0" r="1" gradientTransform="matrix(0 .46559 -.74057 0 16.28 6.62)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="bbyb_mbsk"/></radialGradient><radialGradient id="iN4oxGb" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.379 -4.56)scale(.28356 .34084)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ijEZmFJ" cx="0" cy="0" r="1" gradientTransform="matrix(.36068 1.28726 -1.22815 .34412 20.182 6.629)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="xbtbagqno"/><stop offset="1" class="epf-qq6ay"/></radialGradient><radialGradient id="iqLJoPv" cx="0" cy="0" r="1" gradientTransform="matrix(.45206 -.62037 .52 .37891 20.389 6.941)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="akw4fybhj"/><stop offset="1" class="qoxj776_o"/></radialGradient><radialGradient id="ioHRpMD" cx="0" cy="0" r="1" gradientTransform="matrix(.33684 -.88969 1.18874 .45006 20.454 7.04)" gradientUnits="userSpaceOnUse"><stop offset=".803" class="c5e-i-5dw"/><stop offset=".966" class="szee5wb8m"/></radialGradient><radialGradient id="iPsJYqd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23692 1.19129 -1.17115 -.23291 14.512 6.725)" gradientUnits="userSpaceOnUse"><stop offset=".775" class="ay2574bqt"/><stop offset="1" class="g1u_xnbmn"/></radialGradient><radialGradient id="isOKAXT" cx="0" cy="0" r="1" gradientTransform="rotate(170.259 7.058 4.126)scale(.5336 .23535)" gradientUnits="userSpaceOnUse"><stop class="c4l15nbte"/><stop offset="1" class="r95ztqgly"/></radialGradient><filter id="iuPpOrM" width="16.97" height="13.626" x="7.639" y="16.304" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.623529 0 0 0 0 0.317647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1290"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.313726 0 0 0 0 0.576471 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1290" result="effect2_innerShadow_4002_1290"/></filter><filter id="imakbQd" width="8.803" height="12.453" x="15.083" y="15.257" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1290" stdDeviation=".5"/></filter><filter id="i3dBtev" width="9.329" height="6.572" x="5.433" y="10.796" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.188235 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1290"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.137255 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1290" result="effect2_innerShadow_4002_1290"/></filter><filter id="i4kYmWz" width="5.98" height="8.393" x="20.337" y="7.046" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.14902 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1290"/></filter><filter id="iiCLrqs" width="1.41" height="1.949" x="24.485" y="7.263" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.2 0 0 0 0 0.101961 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1290"/></filter><filter id="iM8y4uc" width="6.555" height="7.624" x="14.255" y="10.454" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.470588 0 0 0 0 0.0117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1290"/></filter><filter id="iuiCrpe" width="11.112" height="3.615" x="10.829" y="25.843" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1290" stdDeviation=".2"/></filter><filter id="iaos6ge" width="3.297" height="3.17" x="8.245" y="23.873" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1290" stdDeviation=".2"/></filter><filter id="irZOojI" width="3.085" height="3.032" x="11.506" y="23.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1290" stdDeviation=".2"/></filter><filter id="ifZz61d" width="6.865" height="7.282" x="14.627" y="3.606" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.333333 0 0 0 0 0.270588 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1290"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.145098 0 0 0 0 0.0705882 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1290" result="effect2_innerShadow_4002_1290"/></filter><filter id="iuus1xd" width="3.002" height="3.664" x="15.95" y="5.673" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1290" stdDeviation=".5"/></filter><filter id="izcxafZ" width="1.177" height="1.764" x="16.944" y="6.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1290" stdDeviation=".025"/></filter><filter id="i5h7iFe" width="2.047" height=".816" x="16.509" y="8.51" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1290" stdDeviation=".025"/></filter><filter id="iWVtF3d" width="7.387" height="5.008" x="13.839" y="1.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0901961 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1290"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0784314 0 0 0 0 0.0352941 0 0 0 0 0.0470588 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_1290" result="effect2_innerShadow_4002_1290"/></filter><filter id="ipXmFgb" width="1.385" height=".768" x="18.444" y="4.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1290"/></filter><filter id="iJEsIId" width="1.385" height=".76" x="15.428" y="4.956" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.2"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.054902 0 0 0 0 0.0588235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1290"/></filter><filter id="iVkHEtc" width="4.041" height="3.494" x="14.036" y="2.409" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.286275 0 0 0 0 0.243137 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1290"/><feGaussianBlur result="effect2_foregroundBlur_4002_1290" stdDeviation=".075"/></filter><filter id="ixE4TBS" width="3.67" height="3.355" x="17.478" y="2.643" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.329412 0 0 0 0 0.305882 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_1290"/><feGaussianBlur result="effect2_foregroundBlur_4002_1290" stdDeviation=".1"/></filter><filter id="iLyWMHL" width=".537" height=".485" x="18.32" y="6.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1290" stdDeviation=".05"/></filter><filter id="iKlCOOj" width=".682" height=".695" x="18.76" y="6.326" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1290" stdDeviation=".1"/></filter><filter id="iXQJxfc" width=".736" height=".767" x="16.21" y="6.29" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1290" stdDeviation=".1"/></filter><filter id="iZINzVd" width=".609" height=".489" x="15.82" y="6.321" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1290" stdDeviation=".05"/></filter><filter id="iHCCAjm" width=".976" height="1.578" x="13.936" y="6.209" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1290" stdDeviation=".125"/></filter><filter id="ijjkC2b" width="1.543" height="2.092" x="19.868" y="5.948" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1290" stdDeviation=".25"/></filter><filter id="inX08tw" width="2.661" height="1.364" x="18.217" y="3.129" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1290" stdDeviation=".125"/></filter><filter id="iGsehIb" width="4.07" height="2.867" x="20.64" y="11.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1290" stdDeviation=".25"/></filter><filter id="iAR2XEb" width="2.394" height="7.066" x="24.256" y="7.842" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1290" stdDeviation=".3"/></filter><filter id="iHSPHjc" width="2.251" height="3.579" x="23.392" y="7.165" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_1290" stdDeviation=".2"/></filter><linearGradient id="iCXvyie" x1="6.762" x2="7.023" y1="16.843" y2="16.843" gradientUnits="userSpaceOnUse"><stop class="tsah1w4pm"/><stop offset="1" class="h52qvf2wn"/></linearGradient><linearGradient id="iXkaSgb" x1="8.177" x2="13.645" y1="16.679" y2="13.429" gradientUnits="userSpaceOnUse"><stop class="c825x_9dc"/><stop offset="1" class="a8u1ptbeu"/></linearGradient><linearGradient id="iYcj16d" x1="13.802" x2="15.755" y1="16.085" y2="16.085" gradientUnits="userSpaceOnUse"><stop class="x8wsft-hb"/><stop offset="1" class="m0mihob_v"/></linearGradient><linearGradient id="iFIIACe" x1="11.768" x2="20.875" y1="27.015" y2="28.857" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iFh5wUb" x1="10.518" x2="8.203" y1="25.808" y2="25.435" gradientUnits="userSpaceOnUse"><stop offset=".302" class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="iUCaIqe" x1="14.013" x2="13.482" y1="24.145" y2="26.255" gradientUnits="userSpaceOnUse"><stop class="y_rv32tfd"/><stop offset="1" class="uc2wxkyln"/></linearGradient><linearGradient id="izZlefc" x1="20.491" x2="17.994" y1="8.114" y2="8.114" gradientUnits="userSpaceOnUse"><stop class="k53yjlbth"/><stop offset="1" class="prh5swccd"/></linearGradient><linearGradient id="ikJycPd" x1="17.559" x2="17.559" y1="10.734" y2="10.367" gradientUnits="userSpaceOnUse"><stop class="c2b4j9bss"/><stop offset="1" class="rjn5j4bgi"/></linearGradient><linearGradient id="iNEEcmc" x1="18.013" x2="17.532" y1="7.534" y2="7.554" gradientUnits="userSpaceOnUse"><stop offset=".36" class="d8gqn2snf"/><stop offset="1" class="oz5jd4bmy"/></linearGradient><linearGradient id="iie3RLd" x1="17.532" x2="17.532" y1="8.187" y2="7.921" gradientUnits="userSpaceOnUse"><stop class="abx50lnlm"/><stop offset="1" class="u-2msu4yh"/></linearGradient><linearGradient id="iEmJvSc" x1="17.532" x2="17.532" y1="6.492" y2="6.949" gradientUnits="userSpaceOnUse"><stop class="o2r2q6blp"/><stop offset="1" class="kh_x-hbqh"/></linearGradient><linearGradient id="iVVHgvd" x1="16.842" x2="17.025" y1="9.089" y2="8.61" gradientUnits="userSpaceOnUse"><stop class="ob3l4g_ys"/><stop offset="1" class="fglza-d-f"/></linearGradient><linearGradient id="itqgEpX" x1="21.464" x2="14.8" y1="3.897" y2="3.897" gradientUnits="userSpaceOnUse"><stop class="l1vex1b6a"/><stop offset="1" class="kydculhfm"/></linearGradient><linearGradient id="iT8GEBc" x1="19.231" x2="19.051" y1="6.652" y2="6.763" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iSaoYNe" x1="16.707" x2="16.527" y1="6.652" y2="6.763" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ic46cSt" x1="21.226" x2="20.533" y1="6.667" y2="7.916" gradientUnits="userSpaceOnUse"><stop class="lwf47ccyr"/><stop offset="1" class="bmcblacal"/></linearGradient><linearGradient id="iatDoXc" x1="14.175" x2="15.012" y1="7.071" y2="6.998" gradientUnits="userSpaceOnUse"><stop class="jrlin1f0e"/><stop offset="1" class="zzkrmpd6m"/></linearGradient><linearGradient id="iKkQHQe" x1="20.64" x2="20.64" y1="6.448" y2="7.54" gradientUnits="userSpaceOnUse"><stop class="q3b-p60-b"/><stop offset="1" class="v3ih9bcyp"/></linearGradient><linearGradient id="ivt5WEe" x1="24.406" x2="22.549" y1="14.21" y2="15.252" gradientUnits="userSpaceOnUse"><stop offset=".358" class="jr2rvqfzf"/><stop offset="1" class="aj14bpbvn"/></linearGradient><linearGradient id="iPdUGZb" x1="24.517" x2="24.517" y1="7.765" y2="10.144" gradientUnits="userSpaceOnUse"><stop offset=".355" class="v3ky_bckv"/><stop offset="1" class="z843vglpo"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-merpeople-dark" /></template>
<style>
.a4rldd3-z {
  stop-color: var(--svg-color--685554, #685554);
  stop-opacity: 0;
}

.a8u1ptbeu {
  stop-color: var(--svg-color--462e31, #462E31);
}

.abx50lnlm {
  stop-color: var(--svg-color--3e2230, #3E2230);
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.aj14bpbvn {
  stop-color: var(--svg-color--564342, #564342);
  stop-opacity: 0;
}

.akw4fybhj {
  stop-color: var(--svg-color--351b1e, #351B1E);
}

.apsk66b5a {
  stop-color: var(--svg-color--1d0b0c, #1D0B0C);
}

.asp-974pn {
  stop-color: var(--svg-color--432728, #432728);
}

.avt3f3myu {
  d: path("M17.532 8.809c-.291 0-.565-.069-.795-.189c-.079-.04-.163.049-.114.12c.193.291.527.486.909.486c.381 0 .716-.195.909-.486c.05-.074-.035-.16-.114-.12c-.23.12-.5.189-.795.189");
}

.axstwemrb {
  stop-color: var(--svg-color--423c3f, #423C3F);
}

.ay2574bqt {
  stop-color: var(--svg-color--301929, #301929);
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

.bmcblacal {
  stop-color: var(--svg-color--492f32, #492F32);
}

.byz6es45f {
  stop-color: var(--svg-color--605150, #605150);
}

.c2_7179_n {
  stop-color: var(--svg-color--432742, #432742);
  stop-opacity: 0;
}

.c2b4j9bss {
  stop-color: var(--svg-color--30171b, #30171B);
}

.c4l15nbte {
  stop-color: var(--svg-color--2c1d22, #2C1D22);
}

.c4xzopb1o {
  d: path("M19.864 10.562c-2.102-.57-3.82-.266-4.656 0v3.32h4.656z");
}

.c5e-i-5dw {
  stop-color: var(--svg-color--361c1e, #361C1E);
  stop-opacity: 0;
}

.c825x_9dc {
  stop-color: var(--svg-color--452d2e, #452D2E);
}

.c98z413ze {
  stop-color: var(--svg-color--4f4d4d, #4F4D4D);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d2nb27bcb {
  fill: var(--svg-color--412a28, #412A28);
  d: path("M25.683 7.995h-.003a.53.53 0 0 0-.53.532v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.24-.2c-.124-.129-.169-.309-.169-.488V7.95l.56-.558a.44.44 0 0 1 .638.604");
}

.d8gqn2snf {
  stop-color: var(--svg-color--66514e, #66514E);
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

.em3vbzhtc {
  stop-color: var(--svg-color--482320, #482320);
}

.epf-qq6ay {
  stop-color: var(--svg-color--301924, #301924);
}

.esot3dbcv {
  fill: var(--svg-color--4c322f, #4C322F);
  d: path("m23.587 12.28l-2.844-1.464l-.406 2.718l3.348 1.708a1.8 1.8 0 0 0 1.84-.121c.527-.363.82-.979.79-1.618c-.06-1.273-.081-2.688-.103-3.586v-1.39a.531.531 0 0 0-1.063 0v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.238-.2c-.125-.129-.17-.309-.17-.488v-.667a.531.531 0 1 0-1.062 0v1.201a1 1 0 0 0 .235.644l.373.444a.2.2 0 0 1 .046.151c-.065.582-.148 1.353-.197 1.853a.202.202 0 0 1-.293.16");
}

.ez41_pbnb {
  stop-color: var(--svg-color--423c3f, #423C3F);
  stop-opacity: 0;
}

.f_mg0nbwh {
  d: path("m17.665 3.924l-.038-.078a.38.38 0 0 0-.353-.24h-.73c-1.06 0-1.918.868-1.918 1.939v.158c-.195-.149-.44-.462-.44-.969c0-.615.449-.926.735-1.124c.08-.056.148-.103.19-.146l.057-.06c.2-.212.558-.591 1.182-.757a3 3 0 0 1 .52-.086c.47-.036.807.376.807.85v.505z");
}

.f0qkucb4f {
  d: path("M16.747 6.8c0-.166-.135-.277-.171-.31l-.166.16l.102.207z");
}

.f28ypccjc {
  stop-color: var(--svg-color--534445, #534445);
}

.fch_lgr5q {
  stop-color: var(--svg-color--1c0c20, #1C0C20);
  stop-opacity: 0;
}

.fglza-d-f {
  stop-color: var(--svg-color--40222d, #40222D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g1dp7ccjz {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
  stop-opacity: 0;
}

.g1u_xnbmn {
  stop-color: var(--svg-color--301929, #301929);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gt631cbpo {
  stop-color: var(--svg-color--4e4343, #4E4343);
}

.gv9be6ybc {
  stop-color: var(--svg-color--e15c10, #E15C10);
  stop-opacity: 0;
}

.h3u9zlbhg {
  fill: var(--svg-color--504a4c, #504A4C);
  d: path("M19.938 3.934h-1.194a.277.277 0 1 1 .044-.552c.31.05.721.119.997.187c.623.154.795.458.843.674a.87.87 0 0 0-.69-.309");
}

.h52qvf2wn {
  stop-color: var(--svg-color--564441, #564441);
  stop-opacity: 0;
}

.h5cqi1vlg {
  d: path("M14.632 6.08a.924.924 0 0 0 .08 1.836a45 45 0 0 1-.08-1.836");
}

.h8_lbz_nz {
  stop-color: var(--svg-color--4edd83, #4EDD83);
}

.h9204bbax {
  stop-color: var(--svg-color--1d0b0c, #1D0B0C);
  stop-opacity: 0;
}

.hb_ogew6a {
  d: path("M19.242 6.792a.5.5 0 0 0-.133-.266l-.15.164l.068.13z");
}

.hnw0p1utu {
  stop-color: var(--svg-color--0b0306, #0B0306);
}

.ho6zccbxe {
  fill: var(--svg-color--202020, #202020);
  d: path("M19.674 5.437c-.1-.088-.217-.18-.394-.236c-.175-.055-.394-.07-.696-.033a.16.16 0 1 0 .039.316c.276-.034.445-.016.561.02c.114.036.19.094.281.173a.16.16 0 1 0 .21-.24");
}

.i6tnjcu8m {
  d: path("M13.356 19.136c0-1.425.76-2.101 1.16-2.242l5.66-.34c1.61.719 2.954 2.781 3.141 5.281c.188 2.5-.203 4.953-2.265 6.563c-1.65 1.287-3.959 1.552-4.938 1.531h-2.472c-2.625 0-3.247-1.89-3.356-2.297a11 11 0 0 0-.184-.598a.43.43 0 0 0-.221-.26c-.528-.244-1.52-.486-1.947-1.388a3.1 3.1 0 0 1-.28-1.63c.022-.213.232-.344.441-.296c.52.119.95.252 1.57.567a3.4 3.4 0 0 1 1.237 1.226c.065.11.238.112.304.003c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.765-.748 2.275-1.198 2.513c-.288.131-.62.277-.865.388c-.14.063-.21.223-.141.36c.474.956 1.468.869 2.858.869c1.851 0 2.96-1.324 2.843-2.723c-.062-1.812-1.562-2.515-2.57-3.148c-.523-.329-2.055-1.145-2.055-2.926");
}

.ibt06e6rm {
  stop-color: var(--svg-color--3e3433, #3E3433);
}

.if2-x0_3s {
  d: path("M21.317 26.71c0-5.343-3.922-7.968-5.234-9l3.25-1.453c1.125.521 3.035 2.358 3.453 5.11c.484 3.187-.927 4.927-1.469 5.343");
}

.ifesvnbka {
  d: path("M14.743 7.864a.94.94 0 0 1-.52-.177v.534c0 .512.306.969.77 1.158a2.4 2.4 0 0 1-.199-.677z");
}

.izop3bc_a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M11.429 26.909c-.007.65.436 1.948 2.266 1.948h3.177c1.01-.014 3.317-.516 4.469-2.414");
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.jkj1op9ie {
  stop-color: var(--svg-color--4edd83, #4EDD83);
  stop-opacity: 0;
}

.jr2rvqfzf {
  stop-color: var(--svg-color--564342, #564342);
}

.jrlin1f0e {
  stop-color: var(--svg-color--372425, #372425);
}

.jyu3lwbui {
  d: path("M18.785 6.347a.512.512 0 0 1 .494.647h-.99a.514.514 0 0 1 .496-.647");
}

.k45xjwbmq {
  stop-color: var(--svg-color--3e3433, #3E3433);
  stop-opacity: 0;
}

.k53yjlbth {
  stop-color: var(--svg-color--563b38, #563B38);
}

.kh_x-hbqh {
  stop-color: var(--svg-color--4b302a, #4B302A);
  stop-opacity: 0;
}

.kkfk0mbtk {
  fill: var(--svg-color--472c2a, #472C2A);
  d: path("M19.864 10.562c-2.102-.57-3.82-.266-4.656 0v3.32h4.656z");
}

.km_8uqbsr {
  d: path("M20.322 7.864a.94.94 0 0 0 .519-.177v.534c0 .512-.306.969-.77 1.158q.147-.312.199-.677z");
}

.kydculhfm {
  stop-color: var(--svg-color--272127, #272127);
}

.l1vex1b6a {
  stop-color: var(--svg-color--443d40, #443D40);
}

.l2dudh2nh {
  stop-color: var(--svg-color--432728, #432728);
  stop-opacity: 0;
}

.lbreh1bfv {
  stop-color: var(--svg-color--1b0c0c, #1B0C0C);
}

.ldriecc8f {
  fill: var(--svg-color--322125, #322125);
  d: path("M6.762 16.087a.486.486 0 0 1 .973 0v.775a.486.486 0 1 1-.973 0z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lityuf0_c {
  d: path("m20.523 5.799l-.017-.362a.843.843 0 0 0-.806-.818h-.803a1.39 1.39 0 0 1-1.22-.723s.414-1.193 1.1-1.039c.5.113 1.037.29 1.447.558c1.001.653.826 1.83.3 2.384");
}

.lk8uk6bqv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m21.39 12.46l2.57 1.367");
}

.lwf47ccyr {
  stop-color: var(--svg-color--62504f, #62504F);
}

.lxf-5k96n {
  cx: 16.124px;
  cy: 6.566px;
  rx: 0.224px;
  ry: 0.113px;
}

.m0mihob_v {
  stop-color: var(--svg-color--fb711e, #FB711E);
  stop-opacity: 0;
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfkgssbjj {
  stop-color: var(--svg-color--361e27, #361E27);
  stop-opacity: 0;
}

.mg1i52lci {
  fill: var(--svg-color--1f151b, #1F151B);
  d: path("m20.523 5.799l-.017-.362a.843.843 0 0 0-.806-.818h-.803a1.39 1.39 0 0 1-1.22-.723s.414-1.193 1.1-1.039c.5.113 1.037.29 1.447.558c1.001.653.826 1.83.3 2.384");
}

.mqmfq5v9o {
  d: path("M16.279 6.347a.512.512 0 0 0-.494.647h.99a.516.516 0 0 0-.496-.647");
}

.nqt5hcbes {
  stop-color: var(--svg-color--e15c10, #E15C10);
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o2r2q6blp {
  stop-color: var(--svg-color--4b302a, #4B302A);
}

.o57ll2bvc {
  stop-color: var(--svg-color--4e4343, #4E4343);
  stop-opacity: 0;
}

.ob3l4g_ys {
  stop-color: var(--svg-color--584a4a, #584A4A);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
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

.oz5jd4bmy {
  stop-color: var(--svg-color--66514e, #66514E);
  stop-opacity: 0;
}

.p2zt-able {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.748 6.455c.036.05-.04.109-.127.173c-.086.065-.15.11-.187.062c-.037-.049.004-.14.09-.206c.087-.065.187-.078.224-.029");
}

.p8isx8b7k {
  stop-color: var(--svg-color--3e2b29, #3E2B29);
  stop-opacity: 0;
}

.pck9pabxc {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.904 6.191c.375 0 .691.258.778.608a.157.157 0 0 1-.154.195h-1.28a.132.132 0 0 1-.13-.156a.8.8 0 0 1 .786-.647");
}

.pft2s7y0a {
  stop-color: var(--svg-color--221c27, #221C27);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pl3p6ccjp {
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.532 8.809c-.291 0-.565-.069-.795-.189c-.079-.04-.163.049-.114.12c.193.291.527.486.909.486c.381 0 .716-.195.909-.486c.05-.074-.035-.16-.114-.12c-.23.12-.5.189-.795.189Z");
}

.pnx4wsrrl {
  d: path("M14.763 8.733a2.25 2.25 0 0 0 2.23 1.955h1.083a2.25 2.25 0 0 0 2.23-1.955c.067-1.08.135-2.157.185-3.238a.83.83 0 0 0-.79-.821h-.804a1.39 1.39 0 0 1-1.27-.828a.38.38 0 0 0-.352-.24h-.73c-1.06 0-1.918.868-1.918 1.939c0 1.067.066 2.118.136 3.188");
}

.prh5swccd {
  stop-color: var(--svg-color--563b38, #563B38);
  stop-opacity: 0;
}

.psn4zabca {
  stop-color: var(--svg-color--231112, #231112);
  stop-opacity: 0;
}

.pygktylau {
  stop-color: var(--svg-color--ff8e3e, #FF8E3E);
}

.q04qidcke {
  d: path("M20.318 3.335c.295.101.56.307.727.603a1.36 1.36 0 0 1-.06 1.45a.9.9 0 0 0-.156.501v.682a1 1 0 0 0-.383-.154l.045-.922a.83.83 0 0 0-.79-.821h-.804a1.39 1.39 0 0 1-1.27-.828a.38.38 0 0 0-.353-.24h-.73c-1.06 0-1.917.867-1.917 1.939l.017.882a1 1 0 0 0-.413.151V5.89a.9.9 0 0 0-.155-.501a1.37 1.37 0 0 1-.083-1.404c.168-.317.439-.539.746-.646c.329-.117.609-.339.794-.637a1.334 1.334 0 0 1 1.66-.524a.85.85 0 0 0 .684 0a1.334 1.334 0 0 1 1.665.542c.176.293.453.505.776.616");
}

.q3b-p60-b {
  stop-color: var(--svg-color--4c3838, #4C3838);
}

.q522thbho {
  fill: var(--svg-color--23181c, #23181C);
  d: path("m17.665 3.924l-.038-.078a.38.38 0 0 0-.353-.24h-.73c-1.06 0-1.918.868-1.918 1.939v.158c-.195-.149-.44-.462-.44-.969c0-.615.449-.926.735-1.124c.08-.056.148-.103.19-.146l.057-.06c.2-.212.558-.591 1.182-.757a3 3 0 0 1 .52-.086c.47-.036.807.376.807.85v.505z");
}

.q53v6mhsp {
  stop-color: var(--svg-color--1b141e, #1B141E);
}

.qco-2_b3r {
  stop-color: var(--svg-color--484646, #484646);
}

.qn0bf-lre {
  fill: var(--svg-color--202020, #202020);
  d: path("M15.575 5.374a1.6 1.6 0 0 1 .998-.206a.16.16 0 1 1-.039.316a1.27 1.27 0 0 0-.839.19l-.01.007v.002a.16.16 0 0 1-.196-.252z");
}

.qoxj776_o {
  stop-color: var(--svg-color--351b1e, #351B1E);
  stop-opacity: 0;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r95ztqgly {
  stop-color: var(--svg-color--271416, #271416);
}

.rh8nd8b0x {
  d: path("M18.748 6.455c.036.05-.04.109-.127.173c-.086.065-.15.11-.187.062c-.037-.049.004-.14.09-.206c.087-.065.187-.078.224-.029");
}

.rjn5j4bgi {
  stop-color: var(--svg-color--30171b, #30171B);
  stop-opacity: 0;
}

.rppkiibbv {
  d: path("M20.368 7.54q.034-.546.064-1.092a.548.548 0 0 1-.064 1.092");
}

.rra4r9bnq {
  stop-color: var(--svg-color--3c3b3c, #3C3B3C);
}

.s536pit3i {
  stop-color: var(--svg-color--4dcd7d, #4DCD7D);
}

.sbhjtg7pq {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
  stop-opacity: 0;
}

.szee5wb8m {
  stop-color: var(--svg-color--361c1e, #361C1E);
}

.td6euhb6l {
  fill: var(--svg-color--35bb78, #35BB78);
  d: path("M13.356 19.136c0-1.425.76-2.101 1.16-2.242l5.66-.34c1.61.719 2.954 2.781 3.141 5.281c.188 2.5-.203 4.953-2.265 6.563c-1.65 1.287-3.959 1.552-4.938 1.531h-2.472c-2.625 0-3.247-1.89-3.356-2.297a11 11 0 0 0-.184-.598a.43.43 0 0 0-.221-.26c-.528-.244-1.52-.486-1.947-1.388a3.1 3.1 0 0 1-.28-1.63c.022-.213.232-.344.441-.296c.52.119.95.252 1.57.567a3.4 3.4 0 0 1 1.237 1.226c.065.11.238.112.304.003c.206-.342.561-.818 1.045-1.12a4.7 4.7 0 0 1 1.846-.678a.347.347 0 0 1 .387.345c.037 1.765-.748 2.275-1.198 2.513c-.288.131-.62.277-.865.388c-.14.063-.21.223-.141.36c.474.956 1.468.869 2.858.869c1.851 0 2.96-1.324 2.843-2.723c-.062-1.812-1.562-2.515-2.57-3.148c-.523-.329-2.055-1.145-2.055-2.926");
}

.tsah1w4pm {
  stop-color: var(--svg-color--564441, #564441);
}

.txgsuxr-c {
  stop-color: var(--svg-color--685554, #685554);
}

.u-2msu4yh {
  stop-color: var(--svg-color--3e2230, #3E2230);
  stop-opacity: 0;
}

.u8c66dblr {
  fill: var(--svg-color--331e24, #331E24);
  d: path("m17.302 6.849l-.34 1.055c-.057.217.082.434.279.434h.42c.197 0 .335-.22.277-.434l-.283-1.055c-.061-.234-.29-.234-.353 0");
}

.uc2wxkyln {
  stop-color: var(--svg-color--40b87c, #40B87C);
  stop-opacity: 0;
}

.ufco8ab6y {
  stop-color: var(--svg-color--605150, #605150);
  stop-opacity: 0;
}

.uk9jj-hst {
  fill: var(--svg-color--000, #000);
  d: path("M18.492 6.86c0-.164.13-.294.293-.294a.292.292 0 0 1 .261.428h-.519a.3.3 0 0 1-.035-.135");
}

.ukvl8u6wk {
  d: path("M20.356 7.916q.058-.915.106-1.831a.924.924 0 0 1-.106 1.831");
}

.ulx2x9bfe {
  d: path("m17.313 6.736l-.305 1.055c-.062.217.087.434.299.434h.45c.212 0 .362-.22.3-.434l-.305-1.055c-.066-.233-.37-.233-.44 0");
}

.unyhdjbdq {
  stop-color: var(--svg-color--200e25, #200E25);
}

.uwupv_ztt {
  d: path("M14.255 10.891c0-.039.022-.074.058-.09c.2-.089.63-.262 1.09-.346a.05.05 0 0 1 .058.049v.778a2.054 2.054 0 1 0 4.107 0v-.778a.05.05 0 0 1 .058-.05c.462.085.92.259 1.125.348c.036.015.058.05.058.09v6.386a.6.6 0 0 1-.6.6h-5.354a.6.6 0 0 1-.6-.6z");
}

.v_stkcbzd {
  stop-color: var(--svg-color--38211f, #38211F);
  stop-opacity: 0;
}

.v3ih9bcyp {
  stop-color: var(--svg-color--3e2724, #3E2724);
}

.v3ky_bckv {
  stop-color: var(--svg-color--5b4a48, #5B4A48);
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

.w189cfbhy {
  stop-color: var(--svg-color--290018, #290018);
}

.w37r5utea {
  stop-color: var(--svg-color--3f2c2a, #3F2C2A);
}

.wtcnn1bts {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.16 6.191a.8.8 0 0 0-.777.608c-.026.1.05.195.153.195h1.28a.132.132 0 0 0 .131-.156a.804.804 0 0 0-.787-.647");
}

.ww86j5--q {
  stop-color: var(--svg-color--361e27, #361E27);
}

.wyv1gnbxf {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
}

.x5s8xacrq {
  d: path("M6.762 16.087a.486.486 0 0 1 .973 0v.775a.486.486 0 1 1-.973 0z");
}

.x73tbcc6t {
  stop-color: var(--svg-color--6b5b59, #6B5B59);
}

.x8wsft-hb {
  stop-color: var(--svg-color--db6229, #DB6229);
}

.xbtbagqno {
  stop-color: var(--svg-color--301924, #301924);
  stop-opacity: 0;
}

.xjcxgac6b {
  stop-color: var(--svg-color--231112, #231112);
}

.xwn-kfb_d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M8.845 24.474c.41.162 1.402.783 2.096 1.97");
}

.y_rv32tfd {
  stop-color: var(--svg-color--40b87c, #40B87C);
}

.yafg_whjr {
  stop-color: var(--svg-color--eb6820, #EB6820);
}

.yr50mjbls {
  d: path("M25.683 7.995h-.003a.53.53 0 0 0-.53.532v.5c0 .14-.14.234-.256.156a1.5 1.5 0 0 1-.24-.2c-.124-.129-.169-.309-.169-.488V7.95l.56-.558a.44.44 0 0 1 .638.604");
}

.z5a_p6x5j {
  stop-color: var(--svg-color--290017, #290017);
}

.z6d-f52gr {
  stop-color: var(--svg-color--5e5a5b, #5E5A5B);
  stop-opacity: 0;
}

.z843vglpo {
  stop-color: var(--svg-color--5b4a48, #5B4A48);
  stop-opacity: 0;
}

.ziaw6bd6t {
  fill: var(--svg-color--402929, #402929);
  d: path("m17.313 6.736l-.305 1.055c-.062.217.087.434.299.434h.45c.212 0 .362-.22.3-.434l-.305-1.055c-.066-.233-.37-.233-.44 0");
}

.zkb-swu-c {
  stop-color: var(--svg-color--534445, #534445);
  stop-opacity: 0;
}

.zoxoeibbu {
  stroke: var(--svg-color--564342, #564342);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M25.156 14.007v-3.781l.594-.406V8.742");
}

.zwo50zm6y {
  stop-color: var(--svg-color--484646, #484646);
  stop-opacity: 0;
}

.zzkrmpd6m {
  stop-color: var(--svg-color--281919, #281919);
}

</style>
