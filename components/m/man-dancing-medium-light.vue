<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i25lg7c)"><path fill="url(#iDxo0eI)" class="mt-vedbkv"/><path fill="url(#iUnhLfc)" class="mt-vedbkv"/></g><g filter="url(#iDibUie)"><path fill="url(#imwSJ8b)" class="vqp8gziqg"/><path fill="url(#i8zPUwe)" class="vqp8gziqg"/></g><g filter="url(#i2p2dOO)"><path clip-rule="evenodd" class="irtsewoae"/><path fill="url(#iQZzNfc)" clip-rule="evenodd" class="d7z8f74ij"/><path fill="url(#i1ctYud)" clip-rule="evenodd" class="d7z8f74ij"/></g><g filter="url(#i8IBcCd)"><path fill="url(#iacCiae)" class="a1bm4qc3u"/></g><g filter="url(#imsvwAd)"><path fill="url(#iMovpyz)" class="vuihc-bcj"/><path fill="url(#iZUw8Bd)" class="vuihc-bcj"/><path fill="url(#it7XaSd)" class="vuihc-bcj"/><path fill="url(#icED1YI)" class="vuihc-bcj"/></g><g filter="url(#i9jqYAe)"><path fill="url(#iKJ5SJE)" class="vm6ce_jmk"/><path fill="url(#iNtDdEc)" class="vm6ce_jmk"/><path fill="url(#iZSwmbe)" class="vm6ce_jmk"/><path fill="url(#iCEHRqb)" class="vm6ce_jmk"/></g><path fill="url(#izAx3Ud)" clip-rule="evenodd" class="eiz9jcf6n"/><path fill="url(#iQp1XNe)" clip-rule="evenodd" class="eiz9jcf6n"/><g filter="url(#i67k5cc)"><path clip-rule="evenodd" class="bzjjhsbjs"/></g><path fill="url(#ihi3Nge)" class="z5ewkjg-x"/><g filter="url(#iqHbU0c)"><path class="hi05lwx5z"/></g><path fill="url(#igOfCoc)" class="eqxpq3aoz"/><path fill="url(#iXmPazd)" class="eqxpq3aoz"/><path fill="url(#iw40SNu)" class="eqxpq3aoz"/><g filter="url(#iNkJRlc)"><path class="hebmvfbjm"/></g><g filter="url(#i5GkpFd)"><path class="hd_pc76ps"/></g><g filter="url(#irrsBCc)"><path class="s5iez-b2n"/><path fill="url(#inF27se)" class="a9sssdqqd"/></g><g filter="url(#iW16h3b)"><path class="ean-3xbkn"/></g><g filter="url(#iWnJ6id)"><path class="n-o01qbda"/><path fill="url(#ixP2S7d)" class="eeo67f0sx"/></g><g filter="url(#i35KUqs)"><circle fill="url(#i4G1Wfd)" class="lyqmr2bbc"/></g><g filter="url(#iu7d3bc)"><circle fill="url(#iXXLOli)" class="bhb8ipbdm"/></g><g filter="url(#iliHqod)"><circle fill="url(#imFUp4b)" class="ol6g7lb1q"/></g><g filter="url(#iAypa0g)"><rect transform="rotate(32.175 10.93 16.017)" class="cc5akeb5x"/></g><g filter="url(#id3e4Yb)"><path fill="url(#i2rOsvc)" class="ball_rb6t"/><path fill="url(#iRbbF7d)" class="ball_rb6t"/></g><g filter="url(#iOBwKte)"><path fill="url(#iRRrLYL)" class="yqnsa3b2w"/></g><path fill="url(#iYPTQbb)" class="oyt5f2bkb"/><rect fill="url(#iiUzjJc)" class="jzo6g3ltx"/><rect fill="url(#iT3HJod)" class="jzo6g3ltx"/><g filter="url(#ipZr8Lb)"><path class="tkupr4ncr"/></g><g filter="url(#ihJIVHb)"><rect class="bfx1sskhs"/></g><g filter="url(#igwtBBd)"><rect class="i07pvef3v"/></g><g filter="url(#iJ6uv2b)"><rect class="gfwjh3ohy"/></g><g filter="url(#iquJOic)"><path fill="url(#iQtyKTb)" class="su2ao5zll"/></g><g filter="url(#ihvyFQd)"><circle fill="url(#iUnPUYk)" class="yd020t80k"/></g><g filter="url(#iq8u4Ub)"><circle fill="url(#iFyWCJd)" class="xhlscdyyo"/></g><g filter="url(#iErMHIe)"><circle fill="url(#ibIvL8d)" class="ctvq5pwch"/><circle fill="url(#iF0RJhK)" class="ctvq5pwch"/></g><g filter="url(#i2cbYte)"><circle class="i3t36j6sy"/><circle fill="url(#iAAAqSd)" class="cyprxbchu"/><circle fill="url(#iIdGNqe)" class="cyprxbchu"/></g><g filter="url(#iY5LW1d)"><path fill="url(#it2RhLc)" class="bct12yopm"/><path fill="url(#iq9sLfc)" class="bct12yopm"/><path fill="url(#ia0mn8b)" class="bct12yopm"/><path fill="url(#igtTbmc)" class="bct12yopm"/><path fill="url(#iu1NRNb)" class="bct12yopm"/></g><g filter="url(#ib6Gl3b)"><path class="j5bjferdn"/><path fill="url(#ipjiTLc)" class="w_v3b1bqj"/><path fill="url(#izXVHpc)" class="w_v3b1bqj"/><path fill="url(#iaxP1Ke)" class="w_v3b1bqj"/><path fill="url(#i8W5ARK)" class="w_v3b1bqj"/><path fill="url(#itdmYDe)" class="w_v3b1bqj"/></g><path fill="url(#i8rDP9b)" class="w_v3b1bqj"/><path fill="url(#irvr7Le)" class="w_v3b1bqj"/><g filter="url(#iaAhHRb)"><path class="p9vcw-bpl"/></g><g filter="url(#iUsTcBd)"><path class="txhhz_bef"/><path fill="url(#iOE1dab)" class="c5syombil"/><path fill="url(#ibQufle)" class="c5syombil"/><path fill="url(#iSqqobb)" class="c5syombil"/></g><path stroke="url(#i5APibe)" class="exfo4ub_v"/><g filter="url(#iddtfVc)"><path class="ja97gkbqb"/></g><g filter="url(#iQI0Rhe)"><path class="w8qd_h78a"/></g><path class="ydxnt3bwo"/><path fill="url(#i7TRLKc)" class="ktpmnnbfq"/><path class="yeb78jb2o"/><g filter="url(#iJN0Yzc)"><path class="la3ykh9jb"/><path fill="url(#iLw2rWc)" class="jaf_z9b9a"/></g><g filter="url(#ishTk5c)"><path fill="url(#i2vwGbe)" class="qd9f03-2z"/></g><path class="qwvys8bhr"/><path fill="url(#io8FM8b)" class="ygpctubas"/><path class="g6txiih7o"/><g filter="url(#iBjoJad)"><path fill="url(#i81DWGd)" class="gzhpfbebv"/></g><g filter="url(#ibzL2Nd)"><ellipse transform="rotate(-27.914 14.543 7.602)" class="h28t5oexe"/><ellipse fill="url(#io7DRPc)" transform="rotate(-27.914 14.543 7.602)" class="glxzlmcmh"/></g><defs><radialGradient id="iUnhLfc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88287 -.57813 .14717 -.4793 13.905 29.648)" gradientUnits="userSpaceOnUse"><stop class="vxv2m-bqm"/><stop offset="1" class="y8kcl1bix"/></radialGradient><radialGradient id="i8zPUwe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88287 -.57813 .14717 -.4793 23.772 29.648)" gradientUnits="userSpaceOnUse"><stop class="vxv2m-bqm"/><stop offset="1" class="y8kcl1bix"/></radialGradient><radialGradient id="iQZzNfc" cx="0" cy="0" r="1" gradientTransform="rotate(26.222 -7.656 45.296)scale(1.16697 .3839)" gradientUnits="userSpaceOnUse"><stop class="f0cucabtr"/><stop offset="1" class="rcasxucso"/></radialGradient><radialGradient id="iacCiae" cx="0" cy="0" r="1" gradientTransform="rotate(100.074 5.636 12.842)scale(6.98265 6.28539)" gradientUnits="userSpaceOnUse"><stop offset=".436" class="olwuq14vq"/><stop offset="1" class="g4r-t1bcl"/></radialGradient><radialGradient id="iZUw8Bd" cx="0" cy="0" r="1" gradientTransform="matrix(2.48435 3.38708 -1.82506 1.33864 17.053 19.619)" gradientUnits="userSpaceOnUse"><stop class="hxi88nbzr"/><stop offset="1" class="l3am5pbvj"/></radialGradient><radialGradient id="it7XaSd" cx="0" cy="0" r="1" gradientTransform="rotate(147.653 8.167 14.057)scale(1.92338 4.56348)" gradientUnits="userSpaceOnUse"><stop class="mygo_91-e"/><stop offset="1" class="w30s_lbtj"/></radialGradient><radialGradient id="icED1YI" cx="0" cy="0" r="1" gradientTransform="matrix(3.27144 3.19771 -1.19038 1.21783 18.456 17.996)" gradientUnits="userSpaceOnUse"><stop class="gnb7t6epd"/><stop offset="1" class="oxm2fc9jy"/></radialGradient><radialGradient id="iNtDdEc" cx="0" cy="0" r="1" gradientTransform="matrix(4.9441 -8.0188 3.4438 2.12332 10.387 28.67)" gradientUnits="userSpaceOnUse"><stop class="yh2psxb-p"/><stop offset="1" class="i8l7fq6-h"/></radialGradient><radialGradient id="iZSwmbe" cx="0" cy="0" r="1" gradientTransform="rotate(122.867 4.189 13.371)scale(2.40221 3.19663)" gradientUnits="userSpaceOnUse"><stop class="qg9ghcbvt"/><stop offset="1" class="tcm98nmkx"/></radialGradient><radialGradient id="iCEHRqb" cx="0" cy="0" r="1" gradientTransform="rotate(171.215 6.309 10.008)scale(2.38461 1.04291)" gradientUnits="userSpaceOnUse"><stop class="i0b_c8grj"/><stop offset="1" class="nxhf2dq-t"/></radialGradient><radialGradient id="iQp1XNe" cx="0" cy="0" r="1" gradientTransform="rotate(79.509 1.846 15.83)scale(.8581 .41486)" gradientUnits="userSpaceOnUse"><stop offset=".224" class="fglzf7x9d"/><stop offset="1" class="ch_7khbnn"/></radialGradient><radialGradient id="ihi3Nge" cx="0" cy="0" r="1" gradientTransform="rotate(-105.555 11.257 1.57)scale(1.57324 4.12566)" gradientUnits="userSpaceOnUse"><stop class="pb7i5tbeh"/><stop offset="1" class="zkcw-qija"/></radialGradient><radialGradient id="iXmPazd" cx="0" cy="0" r="1" gradientTransform="rotate(117.353 4.025 9.146)scale(3.64758 .73156)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="tp3-xrbff"/><stop offset="1" class="s3rc45b6k"/></radialGradient><radialGradient id="iw40SNu" cx="0" cy="0" r="1" gradientTransform="matrix(-.75783 1.92969 -.78376 -.3078 14.271 9.766)" gradientUnits="userSpaceOnUse"><stop class="c1gbyobwf"/><stop offset="1" class="kzysqdbiz"/></radialGradient><radialGradient id="inF27se" cx="0" cy="0" r="1" gradientTransform="rotate(-148.57 10.887 2.8)scale(1.64805 1.14906)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="kd54_6u1z"/><stop offset="1" class="u8aws4lgo"/></radialGradient><radialGradient id="ixP2S7d" cx="0" cy="0" r="1" gradientTransform="matrix(-.34375 2 -3.37016 -.57925 14.858 9.742)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="omhpq8bny"/><stop offset=".75" class="x6-zvqbsc"/></radialGradient><radialGradient id="i4G1Wfd" cx="0" cy="0" r="1" gradientTransform="rotate(140.38 6.637 9.589)scale(.63706)" gradientUnits="userSpaceOnUse"><stop class="qkeppfmvx"/><stop offset="1" class="u2-6tpbfe"/></radialGradient><radialGradient id="iXXLOli" cx="0" cy="0" r="1" gradientTransform="rotate(140.38 6.477 10.411)scale(.63706)" gradientUnits="userSpaceOnUse"><stop class="qkeppfmvx"/><stop offset="1" class="u2-6tpbfe"/></radialGradient><radialGradient id="imFUp4b" cx="0" cy="0" r="1" gradientTransform="rotate(140.38 6.224 11.287)scale(.63706)" gradientUnits="userSpaceOnUse"><stop class="qkeppfmvx"/><stop offset="1" class="u2-6tpbfe"/></radialGradient><radialGradient id="i2rOsvc" cx="0" cy="0" r="1" gradientTransform="rotate(79.499 -4.177 14.405)scale(1.94812 .738)" gradientUnits="userSpaceOnUse"><stop class="d_oo0mb1r"/><stop offset="1" class="j-cx_6bmm"/></radialGradient><radialGradient id="iRRrLYL" cx="0" cy="0" r="1" gradientTransform="matrix(-.88648 .98484 -1.05171 -.94667 10.533 14.808)" gradientUnits="userSpaceOnUse"><stop class="vyopt_bxu"/><stop offset="1" class="mo3rc5bif"/></radialGradient><radialGradient id="iYPTQbb" cx="0" cy="0" r="1" gradientTransform="rotate(-141.642 11.803 -1.223)scale(1.56107 2.05437)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="m9f55_8wu"/><stop offset="1" class="wtruoub_r"/></radialGradient><radialGradient id="iiUzjJc" cx="0" cy="0" r="1" gradientTransform="matrix(-.3125 .38281 -.31148 -.25427 20.151 2.113)" gradientUnits="userSpaceOnUse"><stop class="w0k7ie0ks"/><stop offset="1" class="kn7m9-beb"/></radialGradient><radialGradient id="iQtyKTb" cx="0" cy="0" r="1" gradientTransform="rotate(131.576 9.578 7.561)scale(1.29499 1.38067)" gradientUnits="userSpaceOnUse"><stop class="vyopt_bxu"/><stop offset="1" class="mo3rc5bif"/></radialGradient><radialGradient id="iUnPUYk" cx="0" cy="0" r="1" gradientTransform="matrix(.76092 0 0 1.33163 12.825 7.94)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="aik_z9b6i"/><stop offset="1" class="k1mq2zvhc"/></radialGradient><radialGradient id="iF0RJhK" cx="0" cy="0" r="1" gradientTransform="matrix(.35847 -.26102 .29792 .40914 17.835 7.825)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="g7lt91bhf"/><stop offset="1" class="ze1cb0iau"/></radialGradient><radialGradient id="iAAAqSd" cx="0" cy="0" r="1" gradientTransform="matrix(.3561 -.65498 .38336 .20843 17.656 8.296)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="ezktjkbgg"/><stop offset="1" class="j3anadbkm"/></radialGradient><radialGradient id="iIdGNqe" cx="0" cy="0" r="1" gradientTransform="matrix(.11243 .1113 -.14347 .14493 17.675 7.94)" gradientUnits="userSpaceOnUse"><stop class="i4pfhbczn"/><stop offset="1" class="xjk10obil"/></radialGradient><radialGradient id="iq9sLfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.6267 -4.42036 0 15.812 6.49)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="vpd4dcexx"/><stop offset="1" class="upbi0xbpg"/></radialGradient><radialGradient id="igtTbmc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.56676 .69755 0 16.625 7.388)" gradientUnits="userSpaceOnUse"><stop class="op2kwubyv"/><stop offset="1" class="wvivicznw"/></radialGradient><radialGradient id="iu1NRNb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.6031 .75 0 14.648 7.374)" gradientUnits="userSpaceOnUse"><stop class="y7nn5tbfc"/><stop offset="1" class="uylyaxbnq"/></radialGradient><radialGradient id="ipjiTLc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49014 1.9206 -3.26615 -2.53413 17.208 4.595)" gradientUnits="userSpaceOnUse"><stop class="qyobb4hvj"/><stop offset="1" class="szm1jtb2t"/></radialGradient><radialGradient id="iaxP1Ke" cx="0" cy="0" r="1" gradientTransform="rotate(-92.056 10.002 -3.43)scale(.80767 .39667)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="u7v6tactn"/><stop offset="1" class="hpjuubccm"/></radialGradient><radialGradient id="i8W5ARK" cx="0" cy="0" r="1" gradientTransform="matrix(.37253 -.85268 .69543 .30383 17.44 7.187)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ls62f1bvq"/><stop offset="1" class="gx0o3oiqw"/></radialGradient><radialGradient id="itdmYDe" cx="0" cy="0" r="1" gradientTransform="matrix(.43048 .53415 -.47161 .38008 15.271 4.21)" gradientUnits="userSpaceOnUse"><stop class="kxzxrmw_u"/><stop offset="1" class="vs8934bpj"/></radialGradient><radialGradient id="i8rDP9b" cx="0" cy="0" r="1" gradientTransform="matrix(.07865 .3396 -.55831 .1293 15.909 4.21)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="dohbdcxhl"/><stop offset="1" class="bb6ud4ewj"/></radialGradient><radialGradient id="irvr7Le" cx="0" cy="0" r="1" gradientTransform="matrix(.31458 .38909 -.8718 .70487 13.723 4.96)" gradientUnits="userSpaceOnUse"><stop class="w-a4mnbis"/><stop offset="1" class="ab4_rnbjl"/></radialGradient><radialGradient id="i7TRLKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39162 -.46338 0 16.552 7.789)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iLw2rWc" cx="0" cy="0" r="1" gradientTransform="matrix(-.10054 -.12956 .17837 -.13842 16.453 7.68)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="io8FM8b" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39164 -.4634 0 14.66 7.789)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="io7DRPc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00335 -.2142 .25746 -.00403 14.537 7.74)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="i25lg7c" width="5.373" height="2.752" x="8.532" y="27.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.117647 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_619"/></filter><filter id="iDibUie" width="5.373" height="2.752" x="18.399" y="27.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.117647 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_619"/></filter><filter id="i2p2dOO" width="6.055" height="5.783" x="15.962" y="6.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.54902 0 0 0 0 0.772549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_619"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.580392 0 0 0 0 0.760784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_619" result="effect2_innerShadow_4002_619"/></filter><filter id="i8IBcCd" width="5.188" height="8.109" x="16.797" y="9.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.352941 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_619"/></filter><filter id="imsvwAd" width="6.705" height="12.103" x="16.587" y="16.855" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.4 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_619"/></filter><filter id="i9jqYAe" width="11.118" height="12.357" x="8.285" y="16.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.509804 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_619"/></filter><filter id="i67k5cc" width="6.488" height="5.992" x="8.619" y="9.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.501961 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_619"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.541176 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_619" result="effect2_innerShadow_4002_619"/></filter><filter id="iqHbU0c" width="4.196" height="9.342" x="12.799" y="9.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.458824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_619"/></filter><filter id="iNkJRlc" width="3.018" height="6.455" x="13.628" y="11.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_619" stdDeviation=".1"/></filter><filter id="i5GkpFd" width="2.718" height="6.155" x="13.977" y="11.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.670588 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_619"/></filter><filter id="irrsBCc" width="2.18" height="1.491" x="16.731" y="9.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.388235 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_619"/></filter><filter id="iW16h3b" width="1.827" height="1.621" x="15.405" y="10.2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.498039 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_619"/></filter><filter id="iWnJ6id" width="2.654" height="2.575" x="13.768" y="9.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.403922 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_619"/></filter><filter id="i35KUqs" width="1.225" height="1.225" x="16.839" y="12.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.352941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_619"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_619" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.025" dy=".03"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.878431 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_619"/></filter><filter id="iu7d3bc" width="1.225" height="1.225" x="17.081" y="13.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.996078 0 0 0 0 0.321569 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_619"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_619" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.025" dy=".03"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.878431 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_619"/></filter><filter id="iliHqod" width="1.225" height="1.225" x="17.191" y="15.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.27451 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_619"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_619" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.025" dy=".03"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.878431 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_619"/></filter><filter id="iAypa0g" width="1.124" height="1.036" x="10.671" y="16.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.498039 0 0 0 0 0.443137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_619"/></filter><filter id="id3e4Yb" width="2.496" height="2.734" x="9.04" y="15.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.125"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.454902 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_619"/></filter><filter id="iOBwKte" width="3.308" height="2.19" x="8.228" y="14.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.34902 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_619"/></filter><filter id="ipZr8Lb" width="1.381" height="1.353" x="18.793" y="3.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.552941 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_619"/></filter><filter id="ihJIVHb" width=".87" height="1.395" x="21.197" y="2.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.533333 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_619"/></filter><filter id="igwtBBd" width=".87" height="1.395" x="20.578" y="2.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.533333 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_619"/></filter><filter id="iJ6uv2b" width=".87" height="1.395" x="19.958" y="2.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.533333 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_619"/></filter><filter id="iquJOic" width="3.212" height="2.157" x="19.357" y="4.765" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.34902 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_619"/></filter><filter id="ihvyFQd" width="1.648" height="1.448" x="12.825" y="7.216" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.643137 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_619"/></filter><filter id="iq8u4Ub" width="1.863" height="1.863" x="12.617" y="7.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_619" stdDeviation=".25"/></filter><filter id="iErMHIe" width="1.698" height="1.698" x="16.95" y="6.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.529412 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_619"/></filter><filter id="i2cbYte" width="1.863" height="1.863" x="16.742" y="7.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_619" stdDeviation=".25"/></filter><filter id="iY5LW1d" width="4.498" height="5.365" x="13.371" y="5.501" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.752941 0 0 0 0 0.501961 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_619"/></filter><filter id="ib6Gl3b" width="5.464" height="3.588" x="12.875" y="4.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.690196 0 0 0 0 0.533333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_619"/></filter><filter id="iaAhHRb" width="2.263" height="2.663" x="14.372" y="7.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_619" stdDeviation=".375"/></filter><filter id="iUsTcBd" width=".914" height="1.263" x="15.151" y="7.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_619" stdDeviation=".025"/></filter><filter id="iddtfVc" width="1.434" height="1.039" x="16.12" y="6.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_619"/></filter><filter id="iQI0Rhe" width="1.434" height="1.039" x="13.888" y="6.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.168627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_619"/></filter><filter id="iJN0Yzc" width=".454" height=".415" x="16.177" y="7.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_619" stdDeviation=".05"/></filter><filter id="ishTk5c" width=".613" height=".623" x="16.485" y="7.373" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_619" stdDeviation=".1"/></filter><filter id="iBjoJad" width=".654" height=".678" x="14.559" y="7.345" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_619" stdDeviation=".1"/></filter><filter id="ibzL2Nd" width=".509" height=".419" x="14.288" y="7.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_619" stdDeviation=".05"/></filter><linearGradient id="iDxo0eI" x1="13.397" x2="8.532" y1="29.57" y2="29.57" gradientUnits="userSpaceOnUse"><stop class="leyn8uhkc"/><stop offset="1" class="m4prq-bhs"/></linearGradient><linearGradient id="imwSJ8b" x1="23.264" x2="18.399" y1="29.57" y2="29.57" gradientUnits="userSpaceOnUse"><stop class="leyn8uhkc"/><stop offset="1" class="m4prq-bhs"/></linearGradient><linearGradient id="i1ctYud" x1="21.817" x2="21.588" y1="6.747" y2="7.607" gradientUnits="userSpaceOnUse"><stop offset=".193" class="phi9sxixy"/><stop offset="1" class="y3iq9j8og"/></linearGradient><linearGradient id="iMovpyz" x1="19.689" x2="19.689" y1="17.492" y2="28.957" gradientUnits="userSpaceOnUse"><stop class="chtjorcfq"/><stop offset="1" class="a3ta3d8-l"/></linearGradient><linearGradient id="iKJ5SJE" x1="17.299" x2="12.085" y1="17.307" y2="25.695" gradientUnits="userSpaceOnUse"><stop class="wbm6gtb2b"/><stop offset="1" class="wsr-x9y-q"/></linearGradient><linearGradient id="izAx3Ud" x1="16.623" x2="16.623" y1="11.602" y2="17.289" gradientUnits="userSpaceOnUse"><stop class="ft8y4ezam"/><stop offset="1" class="dpzeg8stn"/></linearGradient><linearGradient id="igOfCoc" x1="14.389" x2="15.076" y1="19.664" y2="17.477" gradientUnits="userSpaceOnUse"><stop class="czfaoab9t"/><stop offset="1" class="q9y6v7blv"/></linearGradient><linearGradient id="iRbbF7d" x1="9.123" x2="9.795" y1="16.227" y2="17.305" gradientUnits="userSpaceOnUse"><stop class="awkk3ucgt"/><stop offset="1" class="v-8bsn3gp"/></linearGradient><linearGradient id="iT3HJod" x1="19.912" x2="19.912" y1="3.891" y2="3.195" gradientUnits="userSpaceOnUse"><stop class="spyd3wy8y"/><stop offset="1" class="sp1bv07wo"/></linearGradient><linearGradient id="iFyWCJd" x1="13.549" x2="13.271" y1="8.061" y2="8.061" gradientUnits="userSpaceOnUse"><stop class="s236rjbsc"/><stop offset="1" class="o6sle6pni"/></linearGradient><linearGradient id="ibIvL8d" x1="18.145" x2="17.79" y1="7.466" y2="8.566" gradientUnits="userSpaceOnUse"><stop class="kwz3apblc"/><stop offset="1" class="gx0xrfbie"/></linearGradient><linearGradient id="it2RhLc" x1="17.358" x2="14.046" y1="8.109" y2="8.602" gradientUnits="userSpaceOnUse"><stop class="b941pszbd"/><stop offset="1" class="jtnk9gb3a"/></linearGradient><linearGradient id="ia0mn8b" x1="13.268" x2="14.271" y1="9.278" y2="9.147" gradientUnits="userSpaceOnUse"><stop class="ls27mhbfe"/><stop offset="1" class="ys1ri2qqc"/></linearGradient><linearGradient id="izXVHpc" x1="13.5" x2="14.758" y1="7.824" y2="5.589" gradientUnits="userSpaceOnUse"><stop class="ts8ii3fly"/><stop offset="1" class="zlpmx2b9v"/></linearGradient><linearGradient id="iOE1dab" x1="15.233" x2="15.64" y1="8.394" y2="8.394" gradientUnits="userSpaceOnUse"><stop class="gs643vbjw"/><stop offset="1" class="v4v-qb7kx"/></linearGradient><linearGradient id="ibQufle" x1="16.014" x2="15.57" y1="8.534" y2="8.528" gradientUnits="userSpaceOnUse"><stop class="sbp9bz1ap"/><stop offset="1" class="xrkexibub"/></linearGradient><linearGradient id="iSqqobb" x1="15.692" x2="15.692" y1="8.856" y2="8.608" gradientUnits="userSpaceOnUse"><stop class="rxh459f4v"/><stop offset="1" class="lemuo5beu"/></linearGradient><linearGradient id="i5APibe" x1="15.158" x2="15.347" y1="9.556" y2="9.258" gradientUnits="userSpaceOnUse"><stop class="pn2_jabhi"/><stop offset=".663" class="z9945l-5h"/></linearGradient><linearGradient id="i2vwGbe" x1="16.89" x2="16.754" y1="7.667" y2="7.751" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i81DWGd" x1="14.983" x2="14.847" y1="7.667" y2="7.751" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-dancing-medium-light" /></template>
<style>
.a1bm4qc3u {
  d: path("M19.438 11.086c-.8-.988-1.708-1.432-2.078-1.547l-.562.188l1.234 7.671c1.576 0 2.842-.575 3.51-1.022a.45.45 0 0 0 .18-.48a13.3 13.3 0 0 0-2.284-4.81");
}

.a3ta3d8-l {
  stop-color: var(--svg-color--357ad1, #357AD1);
}

.a9sssdqqd {
  d: path("M18.577 10.89c-.23-.26-.686-.706-1.229-1.003h-.617l.316 1.39c.273-.042.976-.12 1.441-.172c.11-.013.162-.13.089-.214");
}

.ab4_rnbjl {
  stop-color: var(--svg-color--dcc291, #DCC291);
  stop-opacity: 0;
}

.aik_z9b6i {
  stop-color: var(--svg-color--c28775, #C28775);
}

.awkk3ucgt {
  stop-color: var(--svg-color--bc8181, #BC8181);
}

.b941pszbd {
  stop-color: var(--svg-color--fac39e, #FAC39E);
}

.ball_rb6t {
  d: path("m9.322 17.597l-.282-1.363l2.172-.648l.31 1.548a.75.75 0 0 1-.572.878l-.729.164a.75.75 0 0 1-.899-.58");
}

.bb6ud4ewj {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
  stop-opacity: 0;
}

.bct12yopm {
  d: path("M13.396 7.674h.021s-.023-.37-.046-.624c0-.115.046-.254.14-.323l.07-.07a.46.46 0 0 0 .162-.37v-.37c0-.115.07-.208.186-.231c.28-.07.86-.185 1.698-.185c.837 0 1.419.116 1.698.185a.25.25 0 0 1 .186.231v.37c0 .139.07.278.163.37c.218.153.204.237.186.417c-.023.23-.047.624-.047.624h.008l-.115 1.716c-.07.768-.673 1.302-1.392 1.302h-1.392c-.743 0-1.323-.534-1.392-1.302z");
}

.bfx1sskhs {
  width: 0.62px;
  height: 1.395px;
  x: 21.197px;
  y: 2.871px;
  fill: var(--svg-color--d9a689, #D9A689);
  rx: 0.31px;
}

.bhb8ipbdm {
  cx: 17.794px;
  cy: 14.504px;
  r: 0.313px;
}

.bzjjhsbjs {
  fill: var(--svg-color--34a1f0, #34A1F0);
  fill-rule: evenodd;
  d: path("m10.035 11.029l4.216-1.199l.656 2.309l-3.852 1.095l.24 2.342l-2.387.246l-.279-2.718a1.95 1.95 0 0 1 1.406-2.075");
}

.c1gbyobwf {
  stop-color: var(--svg-color--307ba7, #307BA7);
}

.c5syombil {
  d: path("m15.442 7.816l-.23.737a.234.234 0 0 0 .225.303h.34c.16 0 .274-.154.227-.303l-.23-.737c-.05-.163-.28-.163-.332 0");
}

.cc5akeb5x {
  width: 1.191px;
  height: 0.754px;
  x: 10.929px;
  y: 16.017px;
  fill: var(--svg-color--d79681, #D79681);
  rx: 0.377px;
}

.ch_7khbnn {
  stop-color: var(--svg-color--ff5d09, #FF5D09);
  stop-opacity: 0;
}

.chtjorcfq {
  stop-color: var(--svg-color--44b9ff, #44B9FF);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.ctvq5pwch {
  cx: 17.674px;
  cy: 7.94px;
  r: 0.724px;
}

.cyprxbchu {
  cx: 17.674px;
  cy: 7.94px;
  r: 0.431px;
}

.czfaoab9t {
  stop-color: var(--svg-color--225fcf, #225FCF);
}

.d_oo0mb1r {
  stop-color: var(--svg-color--dfab9a, #DFAB9A);
}

.d7z8f74ij {
  fill-rule: evenodd;
  d: path("M21.817 6.383L21.69 8.46a2.2 2.2 0 0 1-1.335 1.89l-3.454 1.47l-.939-2.21l3.34-1.42l.12-1.954z");
}

.dohbdcxhl {
  stop-color: var(--svg-color--e1d19f, #E1D19F);
}

.dpzeg8stn {
  stop-color: var(--svg-color--ff6b3b, #FF6B3B);
}

.ean-3xbkn {
  fill: var(--svg-color--d79681, #D79681);
  d: path("M17.232 11.542c-.02-.47-.113-.86-.197-1.095c-.044-.126-.167-.197-.3-.197h-.952a.377.377 0 0 0-.212.689l1.225.83c.19.129.446.003.436-.227");
}

.eeo67f0sx {
  d: path("m13.77 11.97l.262-2.087h.418l1.833 1.408a.1.1 0 0 1-.024.172l-2.08.823a.3.3 0 0 1-.408-.316");
}

.eiz9jcf6n {
  fill-rule: evenodd;
  d: path("M18.407 10.93c.515 1.086 1.031 3.898.515 6.36H14.83c-.058-1.746-.282-5.607-.719-7.095h3.438zm-1.457-.68c.088.15.254.644.282 1.292c.01.23-.246.356-.436.227l-2.24-1.519z");
}

.eqxpq3aoz {
  d: path("m12.876 12.71l1.157-2.827l1.64 1.422c1.34 2.11.963 5.853.465 7.596a.465.465 0 0 1-.592.306l-2.604-.797a.204.204 0 0 1-.136-.25c.195-.695.49-2.014.546-2.933c.056-.907-.273-2.024-.476-2.516");
}

.exfo4ub_v {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.336 9.273a.11.11 0 0 0-.013-.14a.12.12 0 0 0-.137-.023a1.25 1.25 0 0 1-.578.137c-.213 0-.412-.05-.578-.137a.12.12 0 0 0-.138.024a.11.11 0 0 0-.012.139m1.456 0l-.042-.028zm0 0a.87.87 0 0 1-.728.389a.87.87 0 0 1-.728-.389m0 0l.041-.028m-.041.028l.041-.028m0 0a.82.82 0 0 0 .687.367a.82.82 0 0 0 .686-.367c.037-.056-.026-.12-.086-.09c-.174.09-.378.142-.6.142a1.3 1.3 0 0 1-.601-.143c-.06-.03-.123.037-.086.091Z");
}

.ezktjkbgg {
  stop-color: var(--svg-color--d79a76, #D79A76);
  stop-opacity: 0;
}

.f0cucabtr {
  stop-color: var(--svg-color--1e8acb, #1E8ACB);
}

.fglzf7x9d {
  stop-color: var(--svg-color--ff5d09, #FF5D09);
}

.ft5dv1b6b {
  fill: none;
}

.ft8y4ezam {
  stop-color: var(--svg-color--ff9255, #FF9255);
}

.g4r-t1bcl {
  stop-color: var(--svg-color--4087da, #4087DA);
}

.g6txiih7o {
  fill: var(--svg-color--000, #000);
  d: path("M14.881 7.824a.22.22 0 0 0-.222-.221a.22.22 0 0 0-.197.323h.393a.2.2 0 0 0 .026-.102");
}

.g7lt91bhf {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
}

.gfwjh3ohy {
  width: 0.62px;
  height: 1.395px;
  x: 19.958px;
  y: 2.871px;
  fill: var(--svg-color--d9a689, #D9A689);
  rx: 0.31px;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.glxzlmcmh {
  cx: 14.543px;
  cy: 7.602px;
  rx: 0.169px;
  ry: 0.085px;
}

.gnb7t6epd {
  stop-color: var(--svg-color--40b1ff, #40B1FF);
}

.gs643vbjw {
  stop-color: var(--svg-color--cb9173, #CB9173);
}

.gx0o3oiqw {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
  stop-opacity: 0;
}

.gx0xrfbie {
  stop-color: var(--svg-color--dca189, #DCA189);
}

.gzhpfbebv {
  d: path("M15.013 7.779c0-.125-.102-.209-.13-.234l-.124.121l.077.157z");
}

.h28t5oexe {
  cx: 14.543px;
  cy: 7.602px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.169px;
  ry: 0.085px;
}

.hd_pc76ps {
  fill: var(--svg-color--40c2ff, #40C2FF);
  d: path("m15.509 11.164l.163.134c.99 1.557 1.043 4.003.804 5.878c-.008.056-.087.058-.099.003c-.444-2.034-1.175-3.34-1.597-3.825a.106.106 0 0 1 .035-.166l.576-.251a.04.04 0 0 0-.001-.074l-1.413-.581z");
}

.hebmvfbjm {
  fill: var(--svg-color--239cfd, #239CFD);
  d: path("m15.36 11.343l.163.134c.99 1.557 1.043 4.003.803 5.879c-.007.055-.086.057-.098.002c-.444-2.033-1.175-3.339-1.597-3.824a.106.106 0 0 1 .035-.167l.575-.25a.04.04 0 0 0 0-.074l-1.413-.582z");
}

.hi05lwx5z {
  fill: var(--svg-color--3ea3f7, #3EA3F7);
  d: path("m12.876 12.71l1.153-2.823l1.643 1.418c1.34 2.11.963 5.853.466 7.596a.465.465 0 0 1-.592.306l-2.604-.797a.204.204 0 0 1-.136-.25c.195-.695.49-2.014.546-2.933c.056-.907-.273-2.024-.476-2.516");
}

.hpjuubccm {
  stop-color: var(--svg-color--eec19c, #EEC19C);
  stop-opacity: 0;
}

.hxi88nbzr {
  stop-color: var(--svg-color--2b8afb, #2B8AFB);
}

.i07pvef3v {
  width: 0.62px;
  height: 1.395px;
  x: 20.578px;
  y: 2.871px;
  fill: var(--svg-color--d9a689, #D9A689);
  rx: 0.31px;
}

.i0b_c8grj {
  stop-color: var(--svg-color--2774e5, #2774E5);
}

.i3t36j6sy {
  cx: 17.674px;
  cy: 7.94px;
  r: 0.431px;
  fill: var(--svg-color--d79e81, #D79E81);
}

.i4pfhbczn {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
}

.i8l7fq6-h {
  stop-color: var(--svg-color--4081dd, #4081DD);
  stop-opacity: 0;
}

.irtsewoae {
  fill: var(--svg-color--35abf6, #35ABF6);
  fill-rule: evenodd;
  d: path("M21.817 6.383L21.69 8.46a2.2 2.2 0 0 1-1.335 1.89l-3.454 1.47l-.939-2.21l3.34-1.42l.12-1.954z");
}

.j-cx_6bmm {
  stop-color: var(--svg-color--d59982, #D59982);
}

.j3anadbkm {
  stop-color: var(--svg-color--d79a76, #D79A76);
}

.j5bjferdn {
  fill: var(--svg-color--ebcc94, #EBCC94);
  d: path("m17.697 5.131l.186.092a.85.85 0 0 1 .442.926l-.256 1.318c-.023.136-.113.227-.248.23l-.008.001s.024-.393.047-.624c.019-.188-.014-.246-.186-.417a.54.54 0 0 1-.163-.37v-.37a.25.25 0 0 0-.186-.231c-.28-.07-.86-.185-1.698-.185c-.837 0-1.419.116-1.698.185a.226.226 0 0 0-.186.231v.37a.46.46 0 0 1-.163.37l-.07.07c-.093.069-.14.208-.14.323c.024.255.047.625.047.625h-.02a.275.275 0 0 1-.259-.231l-.256-1.319a.885.885 0 0 1 .466-.902l.186-.092c.116-.07.232-.162.349-.254l.418-.44a.85.85 0 0 1 .954-.139c.232.07.488.07.72 0A1.05 1.05 0 0 1 17 4.53l.35.347a1 1 0 0 0 .348.254");
}

.ja97gkbqb {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("M17.22 6.76h-.001l-.002-.002l-.005-.005l-.067-.046a1.23 1.23 0 0 0-.83-.16a.231.231 0 1 0 .072.457a.77.77 0 0 1 .512.095l.027.019a.231.231 0 0 0 .294-.358");
}

.jaf_z9b9a {
  d: path("M16.525 7.519c.027.037-.03.082-.096.13c-.065.05-.114.084-.141.047c-.028-.036.003-.106.068-.155c.066-.049.141-.059.169-.022");
}

.jtnk9gb3a {
  stop-color: var(--svg-color--c9917c, #C9917C);
}

.jzo6g3ltx {
  width: 0.645px;
  height: 2.293px;
  x: 19.547px;
  y: 1.938px;
  rx: 0.322px;
}

.k1mq2zvhc {
  stop-color: var(--svg-color--ba7867, #BA7867);
}

.kd54_6u1z {
  stop-color: var(--svg-color--ff8337, #FF8337);
  stop-opacity: 0;
}

.kn7m9-beb {
  stop-color: var(--svg-color--d8a181, #D8A181);
}

.ktpmnnbfq {
  d: path("M16.553 7.437a.387.387 0 0 1 .373.49h-.747a.388.388 0 0 1 .375-.489");
}

.kwz3apblc {
  stop-color: var(--svg-color--f5c8a5, #F5C8A5);
}

.kxzxrmw_u {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
}

.kzysqdbiz {
  stop-color: var(--svg-color--307ba7, #307BA7);
  stop-opacity: 0;
}

.l3am5pbvj {
  stop-color: var(--svg-color--2b8afb, #2B8AFB);
  stop-opacity: 0;
}

.la3ykh9jb {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.525 7.519c.027.037-.03.082-.096.13c-.065.05-.114.084-.141.047c-.028-.036.003-.106.068-.155c.066-.049.141-.059.169-.022");
}

.lemuo5beu {
  stop-color: var(--svg-color--c98583, #C98583);
  stop-opacity: 0;
}

.leyn8uhkc {
  stop-color: var(--svg-color--3f3641, #3F3641);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ls27mhbfe {
  stop-color: var(--svg-color--d99e84, #D99E84);
}

.ls62f1bvq {
  stop-color: var(--svg-color--e3ab85, #E3AB85);
}

.lyqmr2bbc {
  cx: 17.551px;
  cy: 12.945px;
  r: 0.313px;
}

.m4prq-bhs {
  stop-color: var(--svg-color--311e34, #311E34);
}

.m9f55_8wu {
  stop-color: var(--svg-color--e1b69a, #E1B69A);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mo3rc5bif {
  stop-color: var(--svg-color--f97b38, #F97B38);
}

.mt-vedbkv {
  d: path("M8.532 29.863V27.46h1.726l1.641.844c.499.404 1.211.712 1.715.904a.445.445 0 0 1 .264.565a.44.44 0 0 1-.411.288h-2.652a.26.26 0 0 1-.224-.123l-.424-.678a.14.14 0 0 0-.26.075v.625a.1.1 0 0 1-.102.102H8.732a.2.2 0 0 1-.2-.2");
}

.mygo_91-e {
  stop-color: var(--svg-color--4ab6fb, #4AB6FB);
}

.n-o01qbda {
  fill: var(--svg-color--ff8146, #FF8146);
  d: path("m13.77 11.97l.262-2.087h.418l1.833 1.408a.1.1 0 0 1-.024.172l-2.08.823a.3.3 0 0 1-.408-.316");
}

.nxhf2dq-t {
  stop-color: var(--svg-color--3fa1f0, #3FA1F0);
  stop-opacity: 0;
}

.o6sle6pni {
  stop-color: var(--svg-color--b87862, #B87862);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ol6g7lb1q {
  cx: 17.903px;
  cy: 16.215px;
  r: 0.313px;
}

.olwuq14vq {
  stop-color: var(--svg-color--499ee2, #499EE2);
}

.omhpq8bny {
  stop-color: var(--svg-color--d93d03, #D93D03);
}

.op2kwubyv {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
}

.oxm2fc9jy {
  stop-color: var(--svg-color--40b1ff, #40B1FF);
  stop-opacity: 0;
}

.oyt5f2bkb {
  d: path("M19.591 3.594h2.226v2.004h-2.226z");
}

.p9vcw-bpl {
  fill: var(--svg-color--c68378, #C68378);
  d: path("m15.488 7.887l-.355.737c-.045.151.061.303.211.303h.32c.15 0 .256-.154.212-.303l-.217-.737c-.046-.164-.122-.164-.17 0");
}

.pb7i5tbeh {
  stop-color: var(--svg-color--346dd8, #346DD8);
}

.phi9sxixy {
  stop-color: var(--svg-color--3779d3, #3779D3);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pn2_jabhi {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
}

.q9y6v7blv {
  stop-color: var(--svg-color--2f82e6, #2F82E6);
  stop-opacity: 0;
}

.qd9f03-2z {
  d: path("M16.898 7.773a.36.36 0 0 0-.1-.2l-.113.123l.05.1z");
}

.qg9ghcbvt {
  stop-color: var(--svg-color--42aff6, #42AFF6);
}

.qkeppfmvx {
  stop-color: var(--svg-color--ded7f4, #DED7F4);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qwvys8bhr {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.57 7.32a.606.606 0 0 0-.588.458a.12.12 0 0 0 .117.148h.967a.1.1 0 0 0 .098-.118a.61.61 0 0 0-.594-.489");
}

.qyobb4hvj {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
}

.rcasxucso {
  stop-color: var(--svg-color--349fe1, #349FE1);
  stop-opacity: 0;
}

.rxh459f4v {
  stop-color: var(--svg-color--c98583, #C98583);
}

.s236rjbsc {
  stop-color: var(--svg-color--af6f5d, #AF6F5D);
}

.s3rc45b6k {
  stop-color: var(--svg-color--3197dd, #3197DD);
  stop-opacity: 0;
}

.s5iez-b2n {
  fill: var(--svg-color--ff9457, #FF9457);
  d: path("M18.577 10.89c-.23-.26-.686-.706-1.229-1.003h-.617l.316 1.39c.273-.042.976-.12 1.441-.172c.11-.013.162-.13.089-.214");
}

.sbp9bz1ap {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
}

.sp1bv07wo {
  stop-color: var(--svg-color--c78b6e, #C78B6E);
  stop-opacity: 0;
}

.spyd3wy8y {
  stop-color: var(--svg-color--c78b6e, #C78B6E);
}

.su2ao5zll {
  d: path("m19.434 5.153l-.077 1.385a.1.1 0 0 0 .09.105l2.64.277a.3.3 0 0 0 .316-.391l-.464-1.42a.15.15 0 0 0-.14-.103l-2.161-.041a.2.2 0 0 0-.204.188");
}

.szm1jtb2t {
  stop-color: var(--svg-color--ffffc2, #FFFFC2);
  stop-opacity: 0;
}

.tcm98nmkx {
  stop-color: var(--svg-color--42aff6, #42AFF6);
  stop-opacity: 0;
}

.tkupr4ncr {
  fill: var(--svg-color--d29c7f, #D29C7F);
  d: path("M18.882 3.54a.39.39 0 0 1 .546-.053l.497.411c.165.136.21.274.051.546c-.054.093-.207.298-.372.162l-.67-.521a.39.39 0 0 1-.052-.546");
}

.tp3-xrbff {
  stop-color: var(--svg-color--3197dd, #3197DD);
}

.ts8ii3fly {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
}

.txhhz_bef {
  fill: var(--svg-color--e4ac8f, #E4AC8F);
  d: path("m15.442 7.816l-.23.737a.234.234 0 0 0 .225.303h.34c.16 0 .274-.154.227-.303l-.23-.737c-.05-.163-.28-.163-.332 0");
}

.u2-6tpbfe {
  stop-color: var(--svg-color--d8cdf0, #D8CDF0);
}

.u7v6tactn {
  stop-color: var(--svg-color--eec19c, #EEC19C);
}

.u8aws4lgo {
  stop-color: var(--svg-color--ff8337, #FF8337);
}

.upbi0xbpg {
  stop-color: var(--svg-color--9f6e75, #9F6E75);
}

.uylyaxbnq {
  stop-color: var(--svg-color--c2837a, #C2837A);
  stop-opacity: 0;
}

.v-8bsn3gp {
  stop-color: var(--svg-color--bc8181, #BC8181);
  stop-opacity: 0;
}

.v4v-qb7kx {
  stop-color: var(--svg-color--cb9173, #CB9173);
  stop-opacity: 0;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vm6ce_jmk {
  d: path("M12.766 21.523c.217-.748.766-3.252 1.031-4.414l.422.18h4.684c-.816 2.398-2.664 3.657-4.004 5.875c-.409.677-.914 1.43-1.352 2.438c-.37.853-1.054 2.326-1.516 3.324a.574.574 0 0 1-.625.33c-1.533-.293-2.385-.943-3.014-1.765a.49.49 0 0 1-.012-.598c.72-.969 2.73-2.974 3.34-3.569c.675-.66.796-.937 1.046-1.8");
}

.vpd4dcexx {
  stop-color: var(--svg-color--c88d87, #C88D87);
  stop-opacity: 0;
}

.vqp8gziqg {
  d: path("M18.399 29.863V27.46h1.727l1.64.844c.5.404 1.212.712 1.715.904a.445.445 0 0 1 .265.565a.44.44 0 0 1-.412.288h-2.652a.26.26 0 0 1-.224-.123l-.424-.678a.141.141 0 0 0-.26.075v.625a.1.1 0 0 1-.102.102h-1.073a.2.2 0 0 1-.2-.2");
}

.vs8934bpj {
  stop-color: var(--svg-color--fbecaf, #FBECAF);
  stop-opacity: 0;
}

.vuihc-bcj {
  d: path("M21.438 20.164c-.824-.753-1.943-2.294-2.594-3.11l-2.258 2.97c1.874 1.219 2.775 1.939 3.346 2.404a.39.39 0 0 1 .111.463a55 55 0 0 1-1.011 2.03c-.439.853-.938 1.86-1.186 2.565a.5.5 0 0 0 .157.559c.28.22.74.51 1.447.744c.745.246 1.602.178 2.092.075a.43.43 0 0 0 .33-.36c.272-1.551.707-4.215.812-4.742c.09-.45.188-1.117 0-1.75c-.187-.633-.52-1.184-1.246-1.848");
}

.vxv2m-bqm {
  stop-color: var(--svg-color--48454b, #48454B);
}

.vyopt_bxu {
  stop-color: var(--svg-color--ff9a58, #FF9A58);
}

.w_v3b1bqj {
  d: path("m17.697 5.131l.186.092a.85.85 0 0 1 .442.926l-.256 1.318c-.023.136-.113.227-.248.23l-.008.001s.024-.393.047-.624c.019-.188-.014-.246-.186-.417a.54.54 0 0 1-.163-.37v-.37a.25.25 0 0 0-.186-.231c-.28-.07-.86-.185-1.698-.185c-.837 0-1.419.116-1.698.185a.226.226 0 0 0-.186.231v.37a.46.46 0 0 1-.163.37l-.07.07c-.093.069-.14.208-.14.323c.024.255.047.625.047.625h-.02a.275.275 0 0 1-.259-.231l-.256-1.319a.885.885 0 0 1 .466-.902l.186-.092c.116-.07.232-.162.349-.254l.418-.44a.85.85 0 0 1 .954-.139c.232.07.488.07.72 0A1.05 1.05 0 0 1 17 4.53l.35.347a1 1 0 0 0 .348.254");
}

.w-a4mnbis {
  stop-color: var(--svg-color--dcc291, #DCC291);
}

.w0k7ie0ks {
  stop-color: var(--svg-color--e6b896, #E6B896);
}

.w30s_lbtj {
  stop-color: var(--svg-color--4ab6fb, #4AB6FB);
  stop-opacity: 0;
}

.w8qd_h78a {
  fill: var(--svg-color--9a6634, #9A6634);
  d: path("m13.971 6.76l.003-.002l.005-.005l.067-.046q.065-.043.182-.091c.156-.062.378-.112.647-.07a.231.231 0 0 1-.072.458a.77.77 0 0 0-.511.095l-.024.016l-.003.003a.231.231 0 0 1-.295-.358");
}

.wbm6gtb2b {
  stop-color: var(--svg-color--3fb1fe, #3FB1FE);
}

.wsr-x9y-q {
  stop-color: var(--svg-color--4195ec, #4195EC);
}

.wtruoub_r {
  stop-color: var(--svg-color--cc987f, #CC987F);
}

.wvivicznw {
  stop-color: var(--svg-color--e2a18c, #E2A18C);
  stop-opacity: 0;
}

.x6-zvqbsc {
  stop-color: var(--svg-color--d93d03, #D93D03);
  stop-opacity: 0;
}

.xhlscdyyo {
  cx: 13.549px;
  cy: 7.94px;
  r: 0.431px;
}

.xjk10obil {
  stop-color: var(--svg-color--cb8e6d, #CB8E6D);
  stop-opacity: 0;
}

.xrkexibub {
  stop-color: var(--svg-color--fec8a4, #FEC8A4);
  stop-opacity: 0;
}

.y3iq9j8og {
  stop-color: var(--svg-color--3779d3, #3779D3);
  stop-opacity: 0;
}

.y7nn5tbfc {
  stop-color: var(--svg-color--c2837a, #C2837A);
}

.y8kcl1bix {
  stop-color: var(--svg-color--48454b, #48454B);
  stop-opacity: 0;
}

.yd020t80k {
  cx: 13.549px;
  cy: 7.94px;
  r: 0.724px;
}

.ydxnt3bwo {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.643 7.32c.283 0 .522.195.587.458a.12.12 0 0 1-.116.148h-.967a.1.1 0 0 1-.099-.118a.606.606 0 0 1 .595-.489");
}

.yeb78jb2o {
  fill: var(--svg-color--000, #000);
  d: path("M16.331 7.824a.22.22 0 0 1 .222-.221a.22.22 0 0 1 .197.323h-.392a.2.2 0 0 1-.027-.102");
}

.ygpctubas {
  d: path("M14.66 7.437a.387.387 0 0 0-.373.49h.747a.39.39 0 0 0-.375-.489");
}

.yh2psxb-p {
  stop-color: var(--svg-color--4081dd, #4081DD);
}

.yqnsa3b2w {
  d: path("m11.099 14.352l-2.586.139a.3.3 0 0 0-.252.434l.668 1.334a.15.15 0 0 0 .156.08l2.173-.318a.15.15 0 0 0 .128-.163l-.13-1.37a.15.15 0 0 0-.157-.136");
}

.ys1ri2qqc {
  stop-color: var(--svg-color--d99e84, #D99E84);
  stop-opacity: 0;
}

.z5ewkjg-x {
  d: path("m14.25 9.83l-4.215 1.199a1.95 1.95 0 0 0-.937.595l1.958 1.623l-.001-.013l3.852-1.095z");
}

.z9945l-5h {
  stop-color: var(--svg-color--d79e8e, #D79E8E);
  stop-opacity: 0;
}

.ze1cb0iau {
  stop-color: var(--svg-color--e3ab88, #E3AB88);
  stop-opacity: 0;
}

.zkcw-qija {
  stop-color: var(--svg-color--2688ed, #2688ED);
  stop-opacity: 0;
}

.zlpmx2b9v {
  stop-color: var(--svg-color--e8ad8e, #E8AD8E);
  stop-opacity: 0;
}

</style>
