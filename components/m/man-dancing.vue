<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ijBolWb)"><path fill="url(#iDxo0eI)" class="mt-vedbkv"/><path fill="url(#iUnhLfc)" class="mt-vedbkv"/></g><g filter="url(#i8h1zie)"><path fill="url(#imwSJ8b)" class="vqp8gziqg"/><path fill="url(#i8zPUwe)" class="vqp8gziqg"/></g><g filter="url(#i3dTCRb)"><path clip-rule="evenodd" class="irtsewoae"/><path fill="url(#iQZzNfc)" clip-rule="evenodd" class="d7z8f74ij"/><path fill="url(#i1ctYud)" clip-rule="evenodd" class="d7z8f74ij"/></g><g filter="url(#iX72ZJd)"><path fill="url(#iacCiae)" class="a1bm4qc3u"/></g><g filter="url(#ikkFbgd)"><path fill="url(#iMovpyz)" class="vuihc-bcj"/><path fill="url(#iZUw8Bd)" class="vuihc-bcj"/><path fill="url(#it7XaSd)" class="vuihc-bcj"/><path fill="url(#icED1YI)" class="vuihc-bcj"/></g><g filter="url(#iKUG1xb)"><path fill="url(#iKJ5SJE)" class="vm6ce_jmk"/><path fill="url(#iNtDdEc)" class="vm6ce_jmk"/><path fill="url(#iZSwmbe)" class="vm6ce_jmk"/><path fill="url(#iCEHRqb)" class="vm6ce_jmk"/></g><path fill="url(#izAx3Ud)" clip-rule="evenodd" class="eiz9jcf6n"/><path fill="url(#iQp1XNe)" clip-rule="evenodd" class="eiz9jcf6n"/><g filter="url(#iEWIQFe)"><path clip-rule="evenodd" class="bzjjhsbjs"/></g><path fill="url(#ihi3Nge)" class="z5ewkjg-x"/><g filter="url(#i3d4OPe)"><path class="hi05lwx5z"/></g><path fill="url(#igOfCoc)" class="eqxpq3aoz"/><path fill="url(#iXmPazd)" class="eqxpq3aoz"/><path fill="url(#iw40SNu)" class="eqxpq3aoz"/><g filter="url(#i7YXUMe)"><path class="hebmvfbjm"/></g><g filter="url(#io6rEPv)"><path class="hd_pc76ps"/></g><g filter="url(#ijrmnze)"><path class="s5iez-b2n"/><path fill="url(#inF27se)" class="a9sssdqqd"/></g><path fill="url(#i7SmkJG)" class="q4v9atysu"/><path fill="url(#ihd1qJb)" class="q4v9atysu"/><path fill="url(#iTchYXd)" class="q4v9atysu"/><g filter="url(#iLlCu8d)"><path class="n-o01qbda"/><path fill="url(#ixP2S7d)" class="eeo67f0sx"/></g><g filter="url(#iIzGl0b)"><circle fill="url(#i4G1Wfd)" class="lyqmr2bbc"/></g><g filter="url(#iE4yrKe)"><circle fill="url(#iXXLOli)" class="bhb8ipbdm"/></g><g filter="url(#i2iFNJQ)"><circle fill="url(#imFUp4b)" class="ol6g7lb1q"/></g><g filter="url(#igqg8Tb)"><rect transform="rotate(32.175 10.93 16.017)" class="v28phubku"/></g><g filter="url(#iFOC1De)"><path fill="url(#i3z72ee)" class="ball_rb6t"/><path fill="url(#iOQ3jAd)" class="ball_rb6t"/></g><g filter="url(#ilizRtQ)"><path fill="url(#iRRrLYL)" class="yqnsa3b2w"/></g><path fill="url(#iEKjIec)" class="oyt5f2bkb"/><rect fill="url(#ioHd4yd)" class="jzo6g3ltx"/><rect fill="url(#iLiwsVb)" class="jzo6g3ltx"/><g filter="url(#iAiflMb)"><path class="hug3njg1x"/></g><g filter="url(#iDPomcd)"><rect class="mz_kk80ao"/></g><g filter="url(#iPfs2Bc)"><rect class="njuv9l7qk"/></g><g filter="url(#i5CM5wL)"><rect class="bks_xxbxu"/></g><g filter="url(#iI3uYAu)"><path fill="url(#iQtyKTb)" class="su2ao5zll"/></g><circle fill="url(#iS2DeSb)" class="ij6bbhbvi"/><g filter="url(#ihZvpxb)"><circle fill="url(#ivQKzbb)" class="mfb5g-b4p"/></g><g filter="url(#iv2KlTT)"><circle fill="url(#ilxPwTc)" class="ygka1ymfl"/><circle fill="url(#iJhsTTd)" class="ygka1ymfl"/></g><g filter="url(#iXcXRVd)"><circle class="z-ff6obec"/><circle fill="url(#iegAxzc)" class="g2kdez53a"/><circle fill="url(#iIXnBBb)" class="g2kdez53a"/></g><path fill="url(#iPDRDQb)" class="dojqjsdjn"/><path fill="url(#iprZHuc)" class="dojqjsdjn"/><path fill="url(#i9gpWQz)" class="dojqjsdjn"/><path fill="url(#ikHcC6b)" class="dojqjsdjn"/><path fill="url(#iCiuBbe)" class="dojqjsdjn"/><g filter="url(#igPY56R)"><path class="gbkbl9jhh"/><path fill="url(#iUihGib)" class="i18i8kakb"/><path fill="url(#i4uFQPe)" class="i18i8kakb"/><path fill="url(#iRtQjpb)" class="i18i8kakb"/><path fill="url(#iuXmXWc)" class="i18i8kakb"/><path fill="url(#ieC5fle)" class="i18i8kakb"/><path fill="url(#ivm8Lke)" class="i18i8kakb"/></g><path fill="url(#ij7LhFb)" class="i18i8kakb"/><path fill="url(#iiq4EIe)" class="i18i8kakb"/><path fill="url(#iViWUye)" class="i18i8kakb"/><g filter="url(#irtjHJe)"><path class="plk_ymbkc"/></g><g filter="url(#iGJdasd)"><path class="acp78hc5j"/><path fill="url(#ixNGRed)" class="odo4vyb_y"/><path fill="url(#i4MgLdb)" class="odo4vyb_y"/><path fill="url(#isQHh5c)" class="odo4vyb_y"/></g><g filter="url(#ijXMuPe)"><path stroke="url(#iKJW3Qd)" class="rq3chdqxl"/></g><path class="d61cx2y5p"/><path class="dikba5bkj"/><path fill="url(#iciQ3Sc)" class="dd5dkypyl"/><path class="x0trsrbov"/><g filter="url(#iXVoqOc)"><path class="uveu07bmt"/><path fill="url(#i9bfxyc)" class="dxik7lb_v"/></g><g filter="url(#iFHYvDe)"><path fill="url(#iFcvDKb)" class="hrbrf-bez"/></g><path class="rrxfaob6m"/><path fill="url(#i1oZRqV)" class="w7-m8xbzn"/><path class="tma48-dpr"/><g filter="url(#iBMLqQx)"><path fill="url(#iE4Vcid)" class="zg0zpn-4t"/></g><g filter="url(#iYQIRhb)"><ellipse transform="rotate(-27.914 14.516 7.602)" class="brd8gzb7j"/><ellipse fill="url(#icotrVc)" transform="rotate(-27.914 14.516 7.602)" class="beqqygb-y"/></g><g filter="url(#ikWce8b)"><path fill="url(#iJmBBPe)" clip-rule="evenodd" class="fzik8hbdz"/></g><g filter="url(#itpQ9qp)"><path class="u_uwqvb7h"/></g><g filter="url(#iFR5Xad)"><path fill="url(#ifNcj6d)" clip-rule="evenodd" class="bbhh573_y"/></g><g filter="url(#iJZvGee)"><path class="ek6t2wb0i"/></g><defs><radialGradient id="iUnhLfc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88287 -.57813 .14717 -.4793 13.905 29.648)" gradientUnits="userSpaceOnUse"><stop class="vxv2m-bqm"/><stop offset="1" class="y8kcl1bix"/></radialGradient><radialGradient id="i8zPUwe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88287 -.57813 .14717 -.4793 23.772 29.648)" gradientUnits="userSpaceOnUse"><stop class="vxv2m-bqm"/><stop offset="1" class="y8kcl1bix"/></radialGradient><radialGradient id="iQZzNfc" cx="0" cy="0" r="1" gradientTransform="rotate(26.222 -7.656 45.296)scale(1.16697 .3839)" gradientUnits="userSpaceOnUse"><stop class="f0cucabtr"/><stop offset="1" class="rcasxucso"/></radialGradient><radialGradient id="iacCiae" cx="0" cy="0" r="1" gradientTransform="rotate(100.074 5.636 12.842)scale(6.98265 6.28539)" gradientUnits="userSpaceOnUse"><stop offset=".436" class="olwuq14vq"/><stop offset="1" class="g4r-t1bcl"/></radialGradient><radialGradient id="iZUw8Bd" cx="0" cy="0" r="1" gradientTransform="matrix(2.48435 3.38708 -1.82506 1.33864 17.053 19.619)" gradientUnits="userSpaceOnUse"><stop class="hxi88nbzr"/><stop offset="1" class="l3am5pbvj"/></radialGradient><radialGradient id="it7XaSd" cx="0" cy="0" r="1" gradientTransform="rotate(147.653 8.167 14.057)scale(1.92338 4.56348)" gradientUnits="userSpaceOnUse"><stop class="mygo_91-e"/><stop offset="1" class="w30s_lbtj"/></radialGradient><radialGradient id="icED1YI" cx="0" cy="0" r="1" gradientTransform="matrix(3.27144 3.19771 -1.19038 1.21783 18.456 17.996)" gradientUnits="userSpaceOnUse"><stop class="gnb7t6epd"/><stop offset="1" class="oxm2fc9jy"/></radialGradient><radialGradient id="iNtDdEc" cx="0" cy="0" r="1" gradientTransform="matrix(4.9441 -8.0188 3.4438 2.12332 10.387 28.67)" gradientUnits="userSpaceOnUse"><stop class="yh2psxb-p"/><stop offset="1" class="i8l7fq6-h"/></radialGradient><radialGradient id="iZSwmbe" cx="0" cy="0" r="1" gradientTransform="rotate(122.867 4.189 13.371)scale(2.40221 3.19663)" gradientUnits="userSpaceOnUse"><stop class="qg9ghcbvt"/><stop offset="1" class="tcm98nmkx"/></radialGradient><radialGradient id="iCEHRqb" cx="0" cy="0" r="1" gradientTransform="rotate(171.215 6.309 10.008)scale(2.38461 1.04291)" gradientUnits="userSpaceOnUse"><stop class="i0b_c8grj"/><stop offset="1" class="nxhf2dq-t"/></radialGradient><radialGradient id="iQp1XNe" cx="0" cy="0" r="1" gradientTransform="rotate(79.509 1.846 15.83)scale(.8581 .41486)" gradientUnits="userSpaceOnUse"><stop offset=".224" class="fglzf7x9d"/><stop offset="1" class="ch_7khbnn"/></radialGradient><radialGradient id="ihi3Nge" cx="0" cy="0" r="1" gradientTransform="rotate(-105.555 11.257 1.57)scale(1.57324 4.12566)" gradientUnits="userSpaceOnUse"><stop class="pb7i5tbeh"/><stop offset="1" class="zkcw-qija"/></radialGradient><radialGradient id="iXmPazd" cx="0" cy="0" r="1" gradientTransform="rotate(117.353 4.025 9.146)scale(3.64758 .73156)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="tp3-xrbff"/><stop offset="1" class="s3rc45b6k"/></radialGradient><radialGradient id="iw40SNu" cx="0" cy="0" r="1" gradientTransform="matrix(-.75783 1.92969 -.78376 -.3078 14.271 9.766)" gradientUnits="userSpaceOnUse"><stop class="c1gbyobwf"/><stop offset="1" class="kzysqdbiz"/></radialGradient><radialGradient id="inF27se" cx="0" cy="0" r="1" gradientTransform="rotate(-148.57 10.887 2.8)scale(1.64805 1.14906)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="kd54_6u1z"/><stop offset="1" class="u8aws4lgo"/></radialGradient><radialGradient id="i7SmkJG" cx="0" cy="0" r="1" gradientTransform="rotate(-112.917 12.347 .255)scale(2.08657 3.55629)" gradientUnits="userSpaceOnUse"><stop class="ycxsud7ro"/><stop offset="1" class="plllp03-w"/></radialGradient><radialGradient id="ihd1qJb" cx="0" cy="0" r="1" gradientTransform="matrix(.42187 1.42187 -.59557 .1767 16.967 10.102)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="s58p9d6xr"/><stop offset="1" class="mck6syxgi"/></radialGradient><radialGradient id="iTchYXd" cx="0" cy="0" r="1" gradientTransform="rotate(20.772 -20.84 46.506)scale(1.45388 2.47796)" gradientUnits="userSpaceOnUse"><stop class="haxfetbde"/><stop offset=".207" class="z1xpafvnu"/><stop offset="1" class="fc8-mpbsb"/></radialGradient><radialGradient id="ixP2S7d" cx="0" cy="0" r="1" gradientTransform="matrix(-.34375 2 -3.37016 -.57925 14.858 9.742)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="omhpq8bny"/><stop offset=".75" class="x6-zvqbsc"/></radialGradient><radialGradient id="i4G1Wfd" cx="0" cy="0" r="1" gradientTransform="rotate(140.38 6.637 9.589)scale(.63706)" gradientUnits="userSpaceOnUse"><stop class="qkeppfmvx"/><stop offset="1" class="u2-6tpbfe"/></radialGradient><radialGradient id="iXXLOli" cx="0" cy="0" r="1" gradientTransform="rotate(140.38 6.477 10.411)scale(.63706)" gradientUnits="userSpaceOnUse"><stop class="qkeppfmvx"/><stop offset="1" class="u2-6tpbfe"/></radialGradient><radialGradient id="imFUp4b" cx="0" cy="0" r="1" gradientTransform="rotate(140.38 6.224 11.287)scale(.63706)" gradientUnits="userSpaceOnUse"><stop class="qkeppfmvx"/><stop offset="1" class="u2-6tpbfe"/></radialGradient><radialGradient id="i3z72ee" cx="0" cy="0" r="1" gradientTransform="rotate(166.504 4.626 9.17)scale(2.00859 2.92396)" gradientUnits="userSpaceOnUse"><stop class="wxvap4b7x"/><stop offset="1" class="aqg8uzb7g"/></radialGradient><radialGradient id="iRRrLYL" cx="0" cy="0" r="1" gradientTransform="matrix(-.88648 .98484 -1.05171 -.94667 10.533 14.808)" gradientUnits="userSpaceOnUse"><stop class="vyopt_bxu"/><stop offset="1" class="mo3rc5bif"/></radialGradient><radialGradient id="iEKjIec" cx="0" cy="0" r="1" gradientTransform="matrix(-1.80323 -1.12499 1.48049 -2.37305 21.817 4.945)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="ajd7qpbwd"/><stop offset="1" class="yhtyv1bqs"/></radialGradient><radialGradient id="iQtyKTb" cx="0" cy="0" r="1" gradientTransform="rotate(131.576 9.578 7.561)scale(1.29499 1.38067)" gradientUnits="userSpaceOnUse"><stop class="vyopt_bxu"/><stop offset="1" class="mo3rc5bif"/></radialGradient><radialGradient id="iS2DeSb" cx="0" cy="0" r="1" gradientTransform="matrix(.76093 0 0 1.33163 12.799 7.94)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="iJhsTTd" cx="0" cy="0" r="1" gradientTransform="matrix(.35847 -.26102 .29792 .40914 17.809 7.825)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="iegAxzc" cx="0" cy="0" r="1" gradientTransform="matrix(.3561 -.65498 .38336 .20843 17.63 8.296)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="iIXnBBb" cx="0" cy="0" r="1" gradientTransform="matrix(.11243 .1113 -.14347 .14493 17.649 7.94)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="i9gpWQz" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.72281 -4.25077 0 15.794 7.25)" gradientUnits="userSpaceOnUse"><stop offset=".56" class="l58-idrcp"/><stop offset="1" class="kcal37bgz"/></radialGradient><radialGradient id="ikHcC6b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.56676 .69755 0 16.599 7.388)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="iCiuBbe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.6031 .75 0 14.622 7.374)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="iUihGib" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49014 1.9206 -3.26615 -2.53413 17.182 4.595)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="iRtQjpb" cx="0" cy="0" r="1" gradientTransform="rotate(-95.29 9.794 -3.104)scale(.86767 .42613)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="iuXmXWc" cx="0" cy="0" r="1" gradientTransform="matrix(.37253 -.85268 .69544 .30383 17.414 7.186)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="ieC5fle" cx="0" cy="0" r="1" gradientTransform="matrix(.43048 .53415 -.47162 .38008 15.245 4.21)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="ivm8Lke" cx="0" cy="0" r="1" gradientTransform="matrix(.62917 -1.31628 .4548 .21739 17.398 6.11)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="ij7LhFb" cx="0" cy="0" r="1" gradientTransform="matrix(.11325 .44007 -.7235 .18618 15.883 4.21)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="s_ha1fylz"/><stop offset="1" class="e0ciekbtt"/></radialGradient><radialGradient id="iiq4EIe" cx="0" cy="0" r="1" gradientTransform="matrix(.47998 .69331 -1.44277 .99884 13.681 4.757)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="pb3_oi83v"/><stop offset="1" class="gt3e5dbiv"/></radialGradient><radialGradient id="iViWUye" cx="0" cy="0" r="1" gradientTransform="rotate(155.748 7.39 4.751)scale(3.42774 4.28908)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="gmm-ghbsu"/><stop offset=".959" class="g3s2gbbst"/></radialGradient><radialGradient id="iKJW3Qd" cx="0" cy="0" r="1" gradientTransform="matrix(.01067 -.272 .81597 .032 15.544 9.68)" gradientUnits="userSpaceOnUse"><stop class="zjmwko4fr"/><stop offset="1" class="md9bsbc9k"/></radialGradient><radialGradient id="iciQ3Sc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39162 -.46338 0 16.526 7.789)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i9bfxyc" cx="0" cy="0" r="1" gradientTransform="rotate(-127.811 10.094 -.182)scale(.1636 .22523)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i1oZRqV" cx="0" cy="0" r="1" gradientTransform="matrix(0 .39164 -.4634 0 14.634 7.789)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="icotrVc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00335 -.21367 .25685 -.00402 14.51 7.738)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iJmBBPe" cx="0" cy="0" r="1" gradientTransform="matrix(.08533 -.35199 .7722 .1872 16.644 6.986)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><radialGradient id="ifNcj6d" cx="0" cy="0" r="1" gradientTransform="matrix(-.08533 -.35199 .7722 -.1872 14.518 6.986)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="mrt-5h0hn"/><stop offset="1" class="xaad_wcir"/></radialGradient><filter id="ijBolWb" width="5.373" height="2.752" x="8.532" y="27.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.117647 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_607"/></filter><filter id="i8h1zie" width="5.373" height="2.752" x="18.399" y="27.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.117647 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_607"/></filter><filter id="i3dTCRb" width="6.055" height="5.783" x="15.962" y="6.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.54902 0 0 0 0 0.772549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_607"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.580392 0 0 0 0 0.760784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_607" result="effect2_innerShadow_4002_607"/></filter><filter id="iX72ZJd" width="5.188" height="8.109" x="16.797" y="9.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.352941 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_607"/></filter><filter id="ikkFbgd" width="6.705" height="12.103" x="16.587" y="16.855" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.4 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_607"/></filter><filter id="iKUG1xb" width="11.118" height="12.357" x="8.285" y="16.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.509804 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_607"/></filter><filter id="iEWIQFe" width="6.488" height="5.992" x="8.619" y="9.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.501961 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_607"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.541176 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_607" result="effect2_innerShadow_4002_607"/></filter><filter id="i3d4OPe" width="4.196" height="9.342" x="12.799" y="9.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.458824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_607"/></filter><filter id="i7YXUMe" width="3.018" height="6.455" x="13.628" y="11.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_607" stdDeviation=".1"/></filter><filter id="io6rEPv" width="2.718" height="6.155" x="13.977" y="11.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.670588 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_607"/></filter><filter id="ijrmnze" width="2.18" height="1.491" x="16.731" y="9.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.388235 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_607"/></filter><filter id="iLlCu8d" width="2.654" height="2.575" x="13.768" y="9.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.403922 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_607"/></filter><filter id="iIzGl0b" width="1.225" height="1.225" x="16.839" y="12.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.352941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_607"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_607" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.025" dy=".03"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.878431 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_607"/></filter><filter id="iE4yrKe" width="1.225" height="1.225" x="17.081" y="13.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.996078 0 0 0 0 0.321569 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_607"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_607" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.025" dy=".03"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.878431 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_607"/></filter><filter id="i2iFNJQ" width="1.225" height="1.225" x="17.191" y="15.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.27451 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_607"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_607" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.025" dy=".03"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.878431 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_607"/></filter><filter id="igqg8Tb" width="1.124" height="1.036" x="10.671" y="16.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.835294 0 0 0 0 0.513726 0 0 0 0 0.231373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_607"/></filter><filter id="iFOC1De" width="2.496" height="2.734" x="9.04" y="15.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.125"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.521569 0 0 0 0 0.247059 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_607"/></filter><filter id="ilizRtQ" width="3.308" height="2.19" x="8.228" y="14.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.34902 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_607"/></filter><filter id="iAiflMb" width="1.381" height="1.353" x="18.793" y="3.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.596078 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_607"/></filter><filter id="iDPomcd" width=".87" height="1.395" x="21.197" y="2.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.658824 0 0 0 0 0.0392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_607"/></filter><filter id="iPfs2Bc" width=".87" height="1.395" x="20.578" y="2.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.658824 0 0 0 0 0.0392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_607"/></filter><filter id="i5CM5wL" width=".87" height="1.395" x="19.958" y="2.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.658824 0 0 0 0 0.0392157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_607"/></filter><filter id="iI3uYAu" width="3.212" height="2.157" x="19.357" y="4.765" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.34902 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_607"/></filter><filter id="ihZvpxb" width="1.863" height="1.863" x="12.591" y="7.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_607" stdDeviation=".25"/></filter><filter id="iv2KlTT" width="1.698" height="1.698" x="16.924" y="6.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_607"/></filter><filter id="iXcXRVd" width="1.863" height="1.863" x="16.716" y="7.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_607" stdDeviation=".25"/></filter><filter id="igPY56R" width="5.464" height="3.738" x="12.849" y="3.96" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_607"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_607" result="effect2_innerShadow_4002_607"/></filter><filter id="irtjHJe" width="2.263" height="2.663" x="14.346" y="7.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_607" stdDeviation=".375"/></filter><filter id="iGJdasd" width=".914" height="1.263" x="15.124" y="7.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_607" stdDeviation=".025"/></filter><filter id="ijXMuPe" width="1.795" height=".865" x="14.684" y="8.947" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_607" stdDeviation=".05"/></filter><filter id="iXVoqOc" width=".454" height=".415" x="16.151" y="7.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_607" stdDeviation=".05"/></filter><filter id="iFHYvDe" width=".612" height=".622" x="16.459" y="7.373" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_607" stdDeviation=".1"/></filter><filter id="iBMLqQx" width=".654" height=".677" x="14.533" y="7.345" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_607" stdDeviation=".1"/></filter><filter id="iYQIRhb" width=".508" height=".418" x="14.262" y="7.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_607" stdDeviation=".05"/></filter><filter id="ikWce8b" width="1.128" height=".856" x="16.129" y="6.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_607"/></filter><filter id="itpQ9qp" width="1.119" height=".596" x="16.134" y="6.526" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_607" stdDeviation=".075"/></filter><filter id="iFR5Xad" width="1.128" height=".856" x="13.905" y="6.319" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.698039 0 0 0 0 0.25098 0 0 0 0 0.313726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_607"/></filter><filter id="iJZvGee" width="1.119" height=".596" x="13.91" y="6.526" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_607" stdDeviation=".075"/></filter><linearGradient id="iDxo0eI" x1="13.397" x2="8.532" y1="29.57" y2="29.57" gradientUnits="userSpaceOnUse"><stop class="leyn8uhkc"/><stop offset="1" class="m4prq-bhs"/></linearGradient><linearGradient id="imwSJ8b" x1="23.264" x2="18.399" y1="29.57" y2="29.57" gradientUnits="userSpaceOnUse"><stop class="leyn8uhkc"/><stop offset="1" class="m4prq-bhs"/></linearGradient><linearGradient id="i1ctYud" x1="21.817" x2="21.588" y1="6.747" y2="7.607" gradientUnits="userSpaceOnUse"><stop offset=".193" class="phi9sxixy"/><stop offset="1" class="y3iq9j8og"/></linearGradient><linearGradient id="iMovpyz" x1="19.689" x2="19.689" y1="17.492" y2="28.957" gradientUnits="userSpaceOnUse"><stop class="chtjorcfq"/><stop offset="1" class="a3ta3d8-l"/></linearGradient><linearGradient id="iKJ5SJE" x1="17.299" x2="12.085" y1="17.307" y2="25.695" gradientUnits="userSpaceOnUse"><stop class="wbm6gtb2b"/><stop offset="1" class="wsr-x9y-q"/></linearGradient><linearGradient id="izAx3Ud" x1="16.623" x2="16.623" y1="11.602" y2="17.289" gradientUnits="userSpaceOnUse"><stop class="ft8y4ezam"/><stop offset="1" class="dpzeg8stn"/></linearGradient><linearGradient id="igOfCoc" x1="14.389" x2="15.076" y1="19.664" y2="17.477" gradientUnits="userSpaceOnUse"><stop class="czfaoab9t"/><stop offset="1" class="q9y6v7blv"/></linearGradient><linearGradient id="iOQ3jAd" x1="9.123" x2="9.795" y1="16.227" y2="17.305" gradientUnits="userSpaceOnUse"><stop class="m5tq5vbii"/><stop offset="1" class="vmv_1bcut"/></linearGradient><linearGradient id="ioHd4yd" x1="20.192" x2="19.67" y1="2.789" y2="2.789" gradientUnits="userSpaceOnUse"><stop class="gbs57djzy"/><stop offset="1" class="tfggdpbuw"/></linearGradient><linearGradient id="iLiwsVb" x1="19.912" x2="19.912" y1="3.891" y2="3.195" gradientUnits="userSpaceOnUse"><stop class="fc0ywd_0s"/><stop offset="1" class="bp0ohsbas"/></linearGradient><linearGradient id="ivQKzbb" x1="13.523" x2="13.245" y1="8.061" y2="8.061" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="ilxPwTc" x1="18.119" x2="17.764" y1="7.466" y2="8.566" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="iPDRDQb" x1="17.331" x2="14.02" y1="8.109" y2="8.602" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".916" class="as9qb1byz"/></linearGradient><linearGradient id="iprZHuc" x1="13.242" x2="14.244" y1="9.278" y2="9.147" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="i4uFQPe" x1="13.474" x2="14.732" y1="7.824" y2="5.589" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="ixNGRed" x1="15.207" x2="15.613" y1="8.394" y2="8.394" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="i4MgLdb" x1="15.988" x2="15.543" y1="8.534" y2="8.528" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="isQHh5c" x1="15.666" x2="15.666" y1="8.856" y2="8.608" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="iFcvDKb" x1="16.863" x2="16.727" y1="7.667" y2="7.751" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iE4Vcid" x1="14.956" x2="14.821" y1="7.667" y2="7.751" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-dancing" /></template>
<style>
.a1bm4qc3u {
  d: path("M19.438 11.086c-.8-.988-1.708-1.432-2.078-1.547l-.562.188l1.234 7.671c1.576 0 2.842-.575 3.51-1.022a.45.45 0 0 0 .18-.48a13.3 13.3 0 0 0-2.284-4.81");
}

.a3ta3d8-l {
  stop-color: var(--svg-color--357ad1, #357AD1);
}

.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.a9sssdqqd {
  d: path("M18.577 10.89c-.23-.26-.686-.706-1.229-1.003h-.617l.316 1.39c.273-.042.976-.12 1.441-.172c.11-.013.162-.13.089-.214");
}

.acp78hc5j {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m15.416 7.816l-.23.737a.234.234 0 0 0 .225.303h.34c.16 0 .274-.154.226-.303l-.23-.737c-.05-.163-.28-.163-.331 0");
}

.ajd7qpbwd {
  stop-color: var(--svg-color--f7c436, #F7C436);
}

.aqg8uzb7g {
  stop-color: var(--svg-color--eaa82b, #EAA82B);
}

.as9qb1byz {
  stop-color: var(--svg-color--f9a528, #F9A528);
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.ball_rb6t {
  d: path("m9.322 17.597l-.282-1.363l2.172-.648l.31 1.548a.75.75 0 0 1-.572.878l-.729.164a.75.75 0 0 1-.899-.58");
}

.bbhh573_y {
  fill-rule: evenodd;
  d: path("M14.81 6.983c-.313-.029-.513.093-.561.138a.205.205 0 1 1-.278-.301c.133-.123.447-.285.877-.244a.205.205 0 0 1-.039.407");
}

.beqqygb-y {
  cx: 14.516px;
  cy: 7.602px;
  rx: 0.168px;
  ry: 0.085px;
}

.bhb8ipbdm {
  cx: 17.794px;
  cy: 14.504px;
  r: 0.313px;
}

.bks_xxbxu {
  width: 0.62px;
  height: 1.395px;
  x: 19.958px;
  y: 2.871px;
  fill: var(--svg-color--f9c435, #F9C435);
  rx: 0.31px;
}

.bp0ohsbas {
  stop-color: var(--svg-color--e7ab31, #E7AB31);
  stop-opacity: 0;
}

.brd8gzb7j {
  cx: 14.516px;
  cy: 7.602px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.168px;
  ry: 0.085px;
}

.bzjjhsbjs {
  fill: var(--svg-color--34a1f0, #34A1F0);
  fill-rule: evenodd;
  d: path("m10.035 11.029l4.216-1.199l.656 2.309l-3.852 1.095l.24 2.342l-2.387.246l-.279-2.718a1.95 1.95 0 0 1 1.406-2.075");
}

.c1gbyobwf {
  stop-color: var(--svg-color--307ba7, #307BA7);
}

.ch_7khbnn {
  stop-color: var(--svg-color--ff5d09, #FF5D09);
  stop-opacity: 0;
}

.chtjorcfq {
  stop-color: var(--svg-color--44b9ff, #44B9FF);
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.czfaoab9t {
  stop-color: var(--svg-color--225fcf, #225FCF);
}

.d61cx2y5p {
  fill: var(--svg-color--8a004f, #8A004F);
  d: path("M15.581 9.297c-.22 0-.427-.052-.6-.143c-.06-.03-.124.037-.086.091a.82.82 0 0 0 .686.367a.82.82 0 0 0 .687-.367c.037-.056-.027-.12-.086-.09c-.174.09-.379.142-.6.142");
}

.d7z8f74ij {
  fill-rule: evenodd;
  d: path("M21.817 6.383L21.69 8.46a2.2 2.2 0 0 1-1.335 1.89l-3.454 1.47l-.939-2.21l3.34-1.42l.12-1.954z");
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.dd5dkypyl {
  d: path("M16.527 7.437a.387.387 0 0 1 .373.49h-.747a.388.388 0 0 1 .375-.489");
}

.dikba5bkj {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.617 7.32c.283 0 .522.195.587.458a.12.12 0 0 1-.116.148h-.967a.1.1 0 0 1-.099-.118a.606.606 0 0 1 .595-.489");
}

.dojqjsdjn {
  d: path("M13.37 7.674a13 13 0 0 1-.025-.624c0-.115.046-.254.14-.323l.07-.07a.46.46 0 0 0 .162-.37v-.37c0-.115.07-.208.186-.231c.28-.07.86-.185 1.698-.185c.837 0 1.419.116 1.698.185a.25.25 0 0 1 .186.231v.37c0 .139.07.278.163.37c.217.153.204.237.186.417c-.006.055-.023.518-.039.624l-.115 1.716c-.07.768-.673 1.302-1.392 1.302h-1.392c-.743 0-1.323-.534-1.392-1.302z");
}

.dpzeg8stn {
  stop-color: var(--svg-color--ff6b3b, #FF6B3B);
}

.dxik7lb_v {
  d: path("M16.498 7.52c.027.036-.03.08-.096.13c-.065.049-.113.083-.14.046s.002-.106.068-.155c.065-.049.14-.058.168-.022");
}

.e0ciekbtt {
  stop-color: var(--svg-color--ffc926, #FFC926);
  stop-opacity: 0;
}

.eeo67f0sx {
  d: path("m13.77 11.97l.262-2.087h.418l1.833 1.408a.1.1 0 0 1-.024.172l-2.08.823a.3.3 0 0 1-.408-.316");
}

.eiz9jcf6n {
  fill-rule: evenodd;
  d: path("M18.407 10.93c.515 1.086 1.031 3.898.515 6.36H14.83c-.058-1.746-.282-5.607-.719-7.095h3.438zm-1.457-.68c.088.15.254.644.282 1.292c.01.23-.246.356-.436.227l-2.24-1.519z");
}

.ek6t2wb0i {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M14.11 6.922c.09-.083.348-.225.719-.19");
}

.eqxpq3aoz {
  d: path("m12.876 12.71l1.157-2.827l1.64 1.422c1.34 2.11.963 5.853.465 7.596a.465.465 0 0 1-.592.306l-2.604-.797a.204.204 0 0 1-.136-.25c.195-.695.49-2.014.546-2.933c.056-.907-.273-2.024-.476-2.516");
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f0cucabtr {
  stop-color: var(--svg-color--1e8acb, #1E8ACB);
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.fc0ywd_0s {
  stop-color: var(--svg-color--e7ab31, #E7AB31);
}

.fc8-mpbsb {
  stop-color: var(--svg-color--cd9625, #CD9625);
  stop-opacity: 0;
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

.fzik8hbdz {
  fill-rule: evenodd;
  d: path("M16.353 6.983c.312-.029.512.093.56.138a.205.205 0 1 0 .278-.301c-.132-.123-.447-.285-.876-.244a.205.205 0 0 0 .038.407");
}

.g2kdez53a {
  cx: 17.648px;
  cy: 7.94px;
  r: 0.431px;
}

.g3s2gbbst {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
}

.g4r-t1bcl {
  stop-color: var(--svg-color--4087da, #4087DA);
}

.gbkbl9jhh {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m17.67 5.131l.187.092a.85.85 0 0 1 .442.926l-.256 1.318c-.023.136-.113.227-.248.23c.015-.217.03-.57.035-.625c.02-.188-.01-.244-.182-.415a.54.54 0 0 1-.163-.37v-.37a.25.25 0 0 0-.186-.231c-.28-.07-.86-.185-1.698-.185s-1.419.116-1.698.185a.226.226 0 0 0-.186.231v.37a.46.46 0 0 1-.163.37l-.07.07c-.093.069-.14.214-.14.33c.007.067.016.455.026.617a.274.274 0 0 1-.258-.23l-.256-1.319a.885.885 0 0 1 .466-.902c.44-.192.6-.485.953-.786a.85.85 0 0 1 .954-.139c.232.07.488.07.72 0a1.05 1.05 0 0 1 1.024.232l.349.347a1 1 0 0 0 .349.254");
}

.gbs57djzy {
  stop-color: var(--svg-color--fac93f, #FAC93F);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
}

.gmm-ghbsu {
  stop-color: var(--svg-color--cf7d35, #CF7D35);
  stop-opacity: 0;
}

.gnb7t6epd {
  stop-color: var(--svg-color--40b1ff, #40B1FF);
}

.gt3e5dbiv {
  stop-color: var(--svg-color--f29322, #F29322);
  stop-opacity: 0;
}

.haxfetbde {
  stop-color: var(--svg-color--b27318, #B27318);
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
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

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hrbrf-bez {
  d: path("M16.871 7.773a.36.36 0 0 0-.1-.2l-.112.123l.05.099z");
}

.hug3njg1x {
  fill: var(--svg-color--e9ac25, #E9AC25);
  d: path("M18.882 3.54a.39.39 0 0 1 .546-.053l.497.411c.165.136.21.274.051.546c-.054.093-.207.298-.372.162l-.67-.521a.39.39 0 0 1-.052-.546");
}

.hxi88nbzr {
  stop-color: var(--svg-color--2b8afb, #2B8AFB);
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i0b_c8grj {
  stop-color: var(--svg-color--2774e5, #2774E5);
}

.i18i8kakb {
  d: path("m17.67 5.131l.187.092a.85.85 0 0 1 .442.926l-.256 1.318c-.023.136-.113.227-.248.23c.015-.217.03-.57.035-.625c.02-.188-.01-.244-.182-.415a.54.54 0 0 1-.163-.37v-.37a.25.25 0 0 0-.186-.231c-.28-.07-.86-.185-1.698-.185s-1.419.116-1.698.185a.226.226 0 0 0-.186.231v.37a.46.46 0 0 1-.163.37l-.07.07c-.093.069-.14.214-.14.33c.007.067.016.455.026.617a.274.274 0 0 1-.258-.23l-.256-1.319a.885.885 0 0 1 .466-.902c.44-.192.6-.485.953-.786a.85.85 0 0 1 .954-.139c.232.07.488.07.72 0a1.05 1.05 0 0 1 1.024.232l.349.347a1 1 0 0 0 .349.254");
}

.i8l7fq6-h {
  stop-color: var(--svg-color--4081dd, #4081DD);
  stop-opacity: 0;
}

.ij6bbhbvi {
  cx: 13.523px;
  cy: 7.94px;
  r: 0.724px;
}

.irtsewoae {
  fill: var(--svg-color--35abf6, #35ABF6);
  fill-rule: evenodd;
  d: path("M21.817 6.383L21.69 8.46a2.2 2.2 0 0 1-1.335 1.89l-3.454 1.47l-.939-2.21l3.34-1.42l.12-1.954z");
}

.jzo6g3ltx {
  width: 0.645px;
  height: 2.293px;
  x: 19.547px;
  y: 1.938px;
  rx: 0.322px;
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.kcal37bgz {
  stop-color: var(--svg-color--d07f50, #D07F50);
}

.kd54_6u1z {
  stop-color: var(--svg-color--ff8337, #FF8337);
  stop-opacity: 0;
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.kzysqdbiz {
  stop-color: var(--svg-color--307ba7, #307BA7);
  stop-opacity: 0;
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l3am5pbvj {
  stop-color: var(--svg-color--2b8afb, #2B8AFB);
  stop-opacity: 0;
}

.l58-idrcp {
  stop-color: var(--svg-color--f49a3e, #F49A3E);
  stop-opacity: 0;
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.leyn8uhkc {
  stop-color: var(--svg-color--3f3641, #3F3641);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lyqmr2bbc {
  cx: 17.551px;
  cy: 12.945px;
  r: 0.313px;
}

.m4prq-bhs {
  stop-color: var(--svg-color--311e34, #311E34);
}

.m5tq5vbii {
  stop-color: var(--svg-color--dd9730, #DD9730);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.mck6syxgi {
  stop-color: var(--svg-color--ecb936, #ECB936);
  stop-opacity: 0;
}

.md9bsbc9k {
  stop-color: var(--svg-color--ffbe30, #FFBE30);
  stop-opacity: 0;
}

.mfb5g-b4p {
  cx: 13.523px;
  cy: 7.94px;
  r: 0.431px;
}

.mo3rc5bif {
  stop-color: var(--svg-color--f97b38, #F97B38);
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.mrt-5h0hn {
  stop-color: var(--svg-color--c64f38, #C64F38);
}

.mt-vedbkv {
  d: path("M8.532 29.863V27.46h1.726l1.641.844c.499.404 1.211.712 1.715.904a.445.445 0 0 1 .264.565a.44.44 0 0 1-.411.288h-2.652a.26.26 0 0 1-.224-.123l-.424-.678a.14.14 0 0 0-.26.075v.625a.1.1 0 0 1-.102.102H8.732a.2.2 0 0 1-.2-.2");
}

.mygo_91-e {
  stop-color: var(--svg-color--4ab6fb, #4AB6FB);
}

.mz_kk80ao {
  width: 0.62px;
  height: 1.395px;
  x: 21.197px;
  y: 2.871px;
  fill: var(--svg-color--f9c435, #F9C435);
  rx: 0.31px;
}

.n-o01qbda {
  fill: var(--svg-color--ff8146, #FF8146);
  d: path("m13.77 11.97l.262-2.087h.418l1.833 1.408a.1.1 0 0 1-.024.172l-2.08.823a.3.3 0 0 1-.408-.316");
}

.njuv9l7qk {
  width: 0.62px;
  height: 1.395px;
  x: 20.578px;
  y: 2.871px;
  fill: var(--svg-color--f9c435, #F9C435);
  rx: 0.31px;
}

.nxhf2dq-t {
  stop-color: var(--svg-color--3fa1f0, #3FA1F0);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odo4vyb_y {
  d: path("m15.416 7.816l-.23.737a.234.234 0 0 0 .225.303h.34c.16 0 .274-.154.226-.303l-.23-.737c-.05-.163-.28-.163-.331 0");
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

.oxm2fc9jy {
  stop-color: var(--svg-color--40b1ff, #40B1FF);
  stop-opacity: 0;
}

.oyt5f2bkb {
  d: path("M19.591 3.594h2.226v2.004h-2.226z");
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pb3_oi83v {
  stop-color: var(--svg-color--c9993e, #C9993E);
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

.plk_ymbkc {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m15.462 7.887l-.356.737c-.044.151.062.303.212.303h.32c.15 0 .255-.154.211-.303l-.216-.737c-.046-.163-.123-.163-.171 0");
}

.plllp03-w {
  stop-color: var(--svg-color--e4b233, #E4B233);
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.q4v9atysu {
  d: path("M17.232 11.542c-.028-.648-.194-1.142-.282-1.292h-2.395l2.24 1.519c.191.129.447.003.437-.227");
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.q9y6v7blv {
  stop-color: var(--svg-color--2f82e6, #2F82E6);
  stop-opacity: 0;
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qg9ghcbvt {
  stop-color: var(--svg-color--42aff6, #42AFF6);
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qkeppfmvx {
  stop-color: var(--svg-color--ded7f4, #DED7F4);
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.rcasxucso {
  stop-color: var(--svg-color--349fe1, #349FE1);
  stop-opacity: 0;
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rq3chdqxl {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M15.581 9.297c-.22 0-.427-.052-.6-.143c-.06-.03-.124.037-.086.091a.82.82 0 0 0 .686.367a.82.82 0 0 0 .687-.367c.037-.056-.027-.12-.086-.09c-.174.09-.379.142-.6.142Z");
}

.rrxfaob6m {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.544 7.32a.605.605 0 0 0-.588.458a.12.12 0 0 0 .116.148h.968a.1.1 0 0 0 .098-.118a.61.61 0 0 0-.594-.489");
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.s_ha1fylz {
  stop-color: var(--svg-color--ddb13b, #DDB13B);
}

.s3rc45b6k {
  stop-color: var(--svg-color--3197dd, #3197DD);
  stop-opacity: 0;
}

.s58p9d6xr {
  stop-color: var(--svg-color--d19a1a, #D19A1A);
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.s5iez-b2n {
  fill: var(--svg-color--ff9457, #FF9457);
  d: path("M18.577 10.89c-.23-.26-.686-.706-1.229-1.003h-.617l.316 1.39c.273-.042.976-.12 1.441-.172c.11-.013.162-.13.089-.214");
}

.su2ao5zll {
  d: path("m19.434 5.153l-.077 1.385a.1.1 0 0 0 .09.105l2.64.277a.3.3 0 0 0 .316-.391l-.464-1.42a.15.15 0 0 0-.14-.103l-2.161-.041a.2.2 0 0 0-.204.188");
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.tcm98nmkx {
  stop-color: var(--svg-color--42aff6, #42AFF6);
  stop-opacity: 0;
}

.tfggdpbuw {
  stop-color: var(--svg-color--eab133, #EAB133);
}

.tma48-dpr {
  fill: var(--svg-color--000, #000);
  d: path("M14.855 7.824a.22.22 0 0 0-.222-.221a.22.22 0 0 0-.197.323h.393a.2.2 0 0 0 .026-.102");
}

.tp3-xrbff {
  stop-color: var(--svg-color--3197dd, #3197DD);
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.u_uwqvb7h {
  stroke: var(--svg-color--d76d5b, #D76D5B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M17.053 6.922c-.091-.083-.348-.225-.719-.19");
}

.u2-6tpbfe {
  stop-color: var(--svg-color--d8cdf0, #D8CDF0);
}

.u8aws4lgo {
  stop-color: var(--svg-color--ff8337, #FF8337);
}

.uveu07bmt {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.498 7.52c.027.036-.03.08-.096.13c-.065.049-.113.083-.14.046s.002-.106.068-.155c.065-.049.14-.058.168-.022");
}

.v28phubku {
  width: 1.191px;
  height: 0.754px;
  x: 10.929px;
  y: 16.017px;
  fill: var(--svg-color--eea934, #EEA934);
  rx: 0.377px;
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vm6ce_jmk {
  d: path("M12.766 21.523c.217-.748.766-3.252 1.031-4.414l.422.18h4.684c-.816 2.398-2.664 3.657-4.004 5.875c-.409.677-.914 1.43-1.352 2.438c-.37.853-1.054 2.326-1.516 3.324a.574.574 0 0 1-.625.33c-1.533-.293-2.385-.943-3.014-1.765a.49.49 0 0 1-.012-.598c.72-.969 2.73-2.974 3.34-3.569c.675-.66.796-.937 1.046-1.8");
}

.vmv_1bcut {
  stop-color: var(--svg-color--dd9730, #DD9730);
  stop-opacity: 0;
}

.vqp8gziqg {
  d: path("M18.399 29.863V27.46h1.727l1.64.844c.5.404 1.212.712 1.715.904a.445.445 0 0 1 .265.565a.44.44 0 0 1-.412.288h-2.652a.26.26 0 0 1-.224-.123l-.424-.678a.141.141 0 0 0-.26.075v.625a.1.1 0 0 1-.102.102h-1.073a.2.2 0 0 1-.2-.2");
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
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

.w30s_lbtj {
  stop-color: var(--svg-color--4ab6fb, #4AB6FB);
  stop-opacity: 0;
}

.w7-m8xbzn {
  d: path("M14.633 7.437a.387.387 0 0 0-.372.49h.747a.39.39 0 0 0-.375-.489");
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wbm6gtb2b {
  stop-color: var(--svg-color--3fb1fe, #3FB1FE);
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.wsr-x9y-q {
  stop-color: var(--svg-color--4195ec, #4195EC);
}

.wxvap4b7x {
  stop-color: var(--svg-color--ffc43b, #FFC43B);
}

.x0trsrbov {
  fill: var(--svg-color--000, #000);
  d: path("M16.305 7.824a.22.22 0 0 1 .222-.221a.22.22 0 0 1 .197.323h-.392a.2.2 0 0 1-.027-.102");
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.x6-zvqbsc {
  stop-color: var(--svg-color--d93d03, #D93D03);
  stop-opacity: 0;
}

.xaad_wcir {
  stop-color: var(--svg-color--bb4f29, #BB4F29);
}

.y3iq9j8og {
  stop-color: var(--svg-color--3779d3, #3779D3);
  stop-opacity: 0;
}

.y8kcl1bix {
  stop-color: var(--svg-color--48454b, #48454B);
  stop-opacity: 0;
}

.ycxsud7ro {
  stop-color: var(--svg-color--f8c63d, #F8C63D);
}

.ygka1ymfl {
  cx: 17.648px;
  cy: 7.94px;
  r: 0.724px;
}

.yh2psxb-p {
  stop-color: var(--svg-color--4081dd, #4081DD);
}

.yhtyv1bqs {
  stop-color: var(--svg-color--e3a530, #E3A530);
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.yqnsa3b2w {
  d: path("m11.099 14.352l-2.586.139a.3.3 0 0 0-.252.434l.668 1.334a.15.15 0 0 0 .156.08l2.173-.318a.15.15 0 0 0 .128-.163l-.13-1.37a.15.15 0 0 0-.157-.136");
}

.z-ff6obec {
  cx: 17.648px;
  cy: 7.94px;
  r: 0.431px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.z1xpafvnu {
  stop-color: var(--svg-color--b5771a, #B5771A);
  stop-opacity: 0.884;
}

.z5ewkjg-x {
  d: path("m14.25 9.83l-4.215 1.199a1.95 1.95 0 0 0-.937.595l1.958 1.623l-.001-.013l3.852-1.095z");
}

.zg0zpn-4t {
  d: path("M14.986 7.778c0-.125-.101-.208-.129-.233l-.124.12l.076.157z");
}

.zjmwko4fr {
  stop-color: var(--svg-color--ffd069, #FFD069);
}

.zkcw-qija {
  stop-color: var(--svg-color--2688ed, #2688ED);
  stop-opacity: 0;
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

</style>
