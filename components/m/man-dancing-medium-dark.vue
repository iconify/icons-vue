<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iHy6GKR)"><path fill="url(#iDxo0eI)" class="mt-vedbkv"/><path fill="url(#iUnhLfc)" class="mt-vedbkv"/></g><g filter="url(#iIHK55d)"><path fill="url(#imwSJ8b)" class="vqp8gziqg"/><path fill="url(#i8zPUwe)" class="vqp8gziqg"/></g><g filter="url(#i2ITrVc)"><path clip-rule="evenodd" class="irtsewoae"/><path fill="url(#iQZzNfc)" clip-rule="evenodd" class="d7z8f74ij"/><path fill="url(#i1ctYud)" clip-rule="evenodd" class="d7z8f74ij"/></g><g filter="url(#ij1trId)"><path fill="url(#iacCiae)" class="a1bm4qc3u"/></g><g filter="url(#izwVrxi)"><path fill="url(#iMovpyz)" class="vuihc-bcj"/><path fill="url(#iZUw8Bd)" class="vuihc-bcj"/><path fill="url(#it7XaSd)" class="vuihc-bcj"/><path fill="url(#icED1YI)" class="vuihc-bcj"/></g><g filter="url(#iPz0o3b)"><path fill="url(#iKJ5SJE)" class="vm6ce_jmk"/><path fill="url(#iNtDdEc)" class="vm6ce_jmk"/><path fill="url(#iZSwmbe)" class="vm6ce_jmk"/><path fill="url(#iCEHRqb)" class="vm6ce_jmk"/></g><path fill="url(#izAx3Ud)" clip-rule="evenodd" class="eiz9jcf6n"/><path fill="url(#iQp1XNe)" clip-rule="evenodd" class="eiz9jcf6n"/><g filter="url(#iPNo0MP)"><path clip-rule="evenodd" class="bzjjhsbjs"/></g><path fill="url(#ihi3Nge)" class="z5ewkjg-x"/><g filter="url(#ihiX2pe)"><path class="hi05lwx5z"/></g><path fill="url(#igOfCoc)" class="eqxpq3aoz"/><path fill="url(#iXmPazd)" class="eqxpq3aoz"/><path fill="url(#iw40SNu)" class="eqxpq3aoz"/><g filter="url(#iSdsKZd)"><path class="hebmvfbjm"/></g><g filter="url(#itqVQPb)"><path class="hd_pc76ps"/></g><g filter="url(#i75QFge)"><path class="s5iez-b2n"/><path fill="url(#inF27se)" class="a9sssdqqd"/></g><path fill="url(#iRBsfCL)" class="q4v9atysu"/><path fill="url(#iNpXd3b)" class="q4v9atysu"/><path fill="url(#iDxRl0V)" class="q4v9atysu"/><g filter="url(#ic7MAsb)"><path class="n-o01qbda"/><path fill="url(#ixP2S7d)" class="eeo67f0sx"/></g><g filter="url(#idXn0Sc)"><circle fill="url(#i4G1Wfd)" class="lyqmr2bbc"/></g><g filter="url(#i2fY26Y)"><circle fill="url(#iXXLOli)" class="bhb8ipbdm"/></g><g filter="url(#iHPJCYb)"><circle fill="url(#imFUp4b)" class="ol6g7lb1q"/></g><g filter="url(#iJNWPhe)"><rect transform="rotate(32.175 10.93 16.017)" class="ibps_eqic"/></g><g filter="url(#izvQNRc)"><path fill="url(#iRsfQAb)" class="ball_rb6t"/><path fill="url(#iK9ACyb)" class="ball_rb6t"/></g><g filter="url(#igzPMrc)"><path fill="url(#iRRrLYL)" class="yqnsa3b2w"/></g><path fill="url(#it76Tdb)" class="oyt5f2bkb"/><rect fill="url(#inyj5qe)" class="jzo6g3ltx"/><rect fill="url(#iTYwXee)" class="jzo6g3ltx"/><g filter="url(#ippWjtb)"><path class="ntr0bqbzj"/></g><g filter="url(#iIfRjid)"><rect class="fdw40sw0m"/></g><g filter="url(#if7OKLd)"><rect class="o7ak8nbtx"/></g><g filter="url(#ikkhpdc)"><rect class="j5r2wxpvw"/></g><g filter="url(#i9PbWGb)"><path fill="url(#iQtyKTb)" class="su2ao5zll"/></g><g filter="url(#iiVgfRc)"><circle fill="url(#i2fc5pe)" class="w5w_0vdfo"/></g><g filter="url(#i3VM1Fb)"><circle fill="url(#ivFV2Ge)" class="rqwi4sb7b"/></g><g filter="url(#iI61SUI)"><circle fill="url(#i9nsGIc)" class="zezloqboo"/><circle fill="url(#iOKPbhc)" class="zezloqboo"/></g><g filter="url(#ijH2J3c)"><circle class="aujtu_bkk"/><circle fill="url(#ixt0Koe)" class="o_dq2zb-o"/><circle fill="url(#iGxZFRc)" class="o_dq2zb-o"/></g><g filter="url(#ijssDXd)"><path fill="url(#iEPsRzd)" class="xr70e_b6m"/><path fill="url(#iGEehce)" class="xr70e_b6m"/><path fill="url(#iIYieQd)" class="xr70e_b6m"/></g><path fill="url(#irSC7Ub)" class="vrtp9bcak"/><path fill="url(#i99YOKB)" class="vrtp9bcak"/><path fill="url(#ijofsWs)" class="vrtp9bcak"/><path fill="url(#ix79aWb)" class="vrtp9bcak"/><path fill="url(#ijENDWb)" class="vrtp9bcak"/><g filter="url(#iw04bMm)"><path fill="url(#iTtxQJw)" class="d8s-on5pp"/></g><g filter="url(#iRW8fGH)"><path class="v9ldxkc6l"/><path fill="url(#iN1SHAb)" class="rblhu8b8j"/><path fill="url(#iAzPZOb)" class="rblhu8b8j"/><path fill="url(#iugVOWB)" class="rblhu8b8j"/><path fill="url(#iMqGUYd)" class="rblhu8b8j"/></g><g filter="url(#ido56Rb)"><path class="v139tp24n"/></g><g filter="url(#iBCbIBd)"><path class="sxvf2qb2c"/><path fill="url(#it5P2La)" class="vjbaz8r2t"/><path fill="url(#in35kve)" class="vjbaz8r2t"/><path fill="url(#icYVenQ)" class="vjbaz8r2t"/><path fill="url(#iAYN3rs)" class="vjbaz8r2t"/></g><path class="fqpf1cbjx"/><g filter="url(#iQWwvub)"><path class="opfpvxndz"/><path fill="url(#i4VQWhb)" class="yy5jkisqu"/></g><g filter="url(#ip1AHzd)"><path class="jluwh2bfy"/><path fill="url(#i3ZLgCe)" class="ts57h0bot"/></g><path class="nlkqldb7d"/><path fill="url(#iVlDZQc)" class="of4t_rsab"/><path class="bc9b4ab2e"/><g filter="url(#i39WLMc)"><path class="qw2rl3bjm"/><path fill="url(#iSz7ibv)" class="flk9v203r"/></g><g filter="url(#iUSnV9c)"><path fill="url(#ixJCxRd)" class="cvtthw6wc"/></g><path class="kygm6qb6m"/><path fill="url(#i40Olxb)" class="v4zb_95po"/><path class="a-g770t2u"/><g filter="url(#iapXfFd)"><path fill="url(#ihmw9rc)" class="evsu6_b2z"/></g><g filter="url(#iF4tNSb)"><ellipse transform="rotate(-27.914 14.534 7.602)" class="i38ihmb_i"/><ellipse fill="url(#iUar3tc)" transform="rotate(-27.914 14.534 7.602)" class="gtoocib1j"/></g><g filter="url(#ibJkice)"><path stroke="url(#iakUcke)" class="bmux5s23h"/></g><defs><radialGradient id="iUnhLfc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88287 -.57813 .14717 -.4793 13.905 29.648)" gradientUnits="userSpaceOnUse"><stop class="vxv2m-bqm"/><stop offset="1" class="y8kcl1bix"/></radialGradient><radialGradient id="i8zPUwe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88287 -.57813 .14717 -.4793 23.772 29.648)" gradientUnits="userSpaceOnUse"><stop class="vxv2m-bqm"/><stop offset="1" class="y8kcl1bix"/></radialGradient><radialGradient id="iQZzNfc" cx="0" cy="0" r="1" gradientTransform="rotate(26.222 -7.656 45.296)scale(1.16697 .3839)" gradientUnits="userSpaceOnUse"><stop class="f0cucabtr"/><stop offset="1" class="rcasxucso"/></radialGradient><radialGradient id="iacCiae" cx="0" cy="0" r="1" gradientTransform="rotate(100.074 5.636 12.842)scale(6.98265 6.28539)" gradientUnits="userSpaceOnUse"><stop offset=".436" class="olwuq14vq"/><stop offset="1" class="g4r-t1bcl"/></radialGradient><radialGradient id="iZUw8Bd" cx="0" cy="0" r="1" gradientTransform="matrix(2.48435 3.38708 -1.82506 1.33864 17.053 19.619)" gradientUnits="userSpaceOnUse"><stop class="hxi88nbzr"/><stop offset="1" class="l3am5pbvj"/></radialGradient><radialGradient id="it7XaSd" cx="0" cy="0" r="1" gradientTransform="rotate(147.653 8.167 14.057)scale(1.92338 4.56348)" gradientUnits="userSpaceOnUse"><stop class="mygo_91-e"/><stop offset="1" class="w30s_lbtj"/></radialGradient><radialGradient id="icED1YI" cx="0" cy="0" r="1" gradientTransform="matrix(3.27144 3.19771 -1.19038 1.21783 18.456 17.996)" gradientUnits="userSpaceOnUse"><stop class="gnb7t6epd"/><stop offset="1" class="oxm2fc9jy"/></radialGradient><radialGradient id="iNtDdEc" cx="0" cy="0" r="1" gradientTransform="matrix(4.9441 -8.0188 3.4438 2.12332 10.387 28.67)" gradientUnits="userSpaceOnUse"><stop class="yh2psxb-p"/><stop offset="1" class="i8l7fq6-h"/></radialGradient><radialGradient id="iZSwmbe" cx="0" cy="0" r="1" gradientTransform="rotate(122.867 4.189 13.371)scale(2.40221 3.19663)" gradientUnits="userSpaceOnUse"><stop class="qg9ghcbvt"/><stop offset="1" class="tcm98nmkx"/></radialGradient><radialGradient id="iCEHRqb" cx="0" cy="0" r="1" gradientTransform="rotate(171.215 6.309 10.008)scale(2.38461 1.04291)" gradientUnits="userSpaceOnUse"><stop class="i0b_c8grj"/><stop offset="1" class="nxhf2dq-t"/></radialGradient><radialGradient id="iQp1XNe" cx="0" cy="0" r="1" gradientTransform="rotate(79.509 1.846 15.83)scale(.8581 .41486)" gradientUnits="userSpaceOnUse"><stop offset=".224" class="fglzf7x9d"/><stop offset="1" class="ch_7khbnn"/></radialGradient><radialGradient id="ihi3Nge" cx="0" cy="0" r="1" gradientTransform="rotate(-105.555 11.257 1.57)scale(1.57324 4.12566)" gradientUnits="userSpaceOnUse"><stop class="pb7i5tbeh"/><stop offset="1" class="zkcw-qija"/></radialGradient><radialGradient id="iXmPazd" cx="0" cy="0" r="1" gradientTransform="rotate(117.353 4.025 9.146)scale(3.64758 .73156)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="tp3-xrbff"/><stop offset="1" class="s3rc45b6k"/></radialGradient><radialGradient id="iw40SNu" cx="0" cy="0" r="1" gradientTransform="matrix(-.75783 1.92969 -.78376 -.3078 14.271 9.766)" gradientUnits="userSpaceOnUse"><stop class="c1gbyobwf"/><stop offset="1" class="kzysqdbiz"/></radialGradient><radialGradient id="inF27se" cx="0" cy="0" r="1" gradientTransform="rotate(-148.57 10.887 2.8)scale(1.64805 1.14906)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="kd54_6u1z"/><stop offset="1" class="u8aws4lgo"/></radialGradient><radialGradient id="iRBsfCL" cx="0" cy="0" r="1" gradientTransform="rotate(-112.917 12.347 .255)scale(2.08657 3.55629)" gradientUnits="userSpaceOnUse"><stop class="wqbs93h8n"/><stop offset="1" class="k63icwbow"/><stop offset="1" class="yeg_8ccml"/></radialGradient><radialGradient id="iNpXd3b" cx="0" cy="0" r="1" gradientTransform="matrix(.42187 1.42187 -.59557 .1767 16.967 10.102)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="hg6oqob2v"/><stop offset="1" class="hyi6vg4pw"/></radialGradient><radialGradient id="iDxRl0V" cx="0" cy="0" r="1" gradientTransform="matrix(.75781 .60547 -1.03195 1.29159 15.538 10.371)" gradientUnits="userSpaceOnUse"><stop class="vc9ew0biq"/><stop offset="1" class="rbqcrhr2a"/></radialGradient><radialGradient id="ixP2S7d" cx="0" cy="0" r="1" gradientTransform="matrix(-.34375 2 -3.37016 -.57925 14.858 9.742)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="omhpq8bny"/><stop offset=".75" class="x6-zvqbsc"/></radialGradient><radialGradient id="i4G1Wfd" cx="0" cy="0" r="1" gradientTransform="rotate(140.38 6.637 9.589)scale(.63706)" gradientUnits="userSpaceOnUse"><stop class="qkeppfmvx"/><stop offset="1" class="u2-6tpbfe"/></radialGradient><radialGradient id="iXXLOli" cx="0" cy="0" r="1" gradientTransform="rotate(140.38 6.477 10.411)scale(.63706)" gradientUnits="userSpaceOnUse"><stop class="qkeppfmvx"/><stop offset="1" class="u2-6tpbfe"/></radialGradient><radialGradient id="imFUp4b" cx="0" cy="0" r="1" gradientTransform="rotate(140.38 6.224 11.287)scale(.63706)" gradientUnits="userSpaceOnUse"><stop class="qkeppfmvx"/><stop offset="1" class="u2-6tpbfe"/></radialGradient><radialGradient id="iRsfQAb" cx="0" cy="0" r="1" gradientTransform="rotate(79.499 -4.177 14.405)scale(1.94812 .738)" gradientUnits="userSpaceOnUse"><stop class="pvj13sbsi"/><stop offset="1" class="j6id9usmg"/></radialGradient><radialGradient id="iRRrLYL" cx="0" cy="0" r="1" gradientTransform="matrix(-.88648 .98484 -1.05171 -.94667 10.533 14.808)" gradientUnits="userSpaceOnUse"><stop class="vyopt_bxu"/><stop offset="1" class="mo3rc5bif"/></radialGradient><radialGradient id="it76Tdb" cx="0" cy="0" r="1" gradientTransform="rotate(-141.642 11.803 -1.223)scale(1.56107 2.05437)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="e1witkb9q"/><stop offset="1" class="eu3vkcbvq"/></radialGradient><radialGradient id="inyj5qe" cx="0" cy="0" r="1" gradientTransform="matrix(-.3125 .38281 -.31148 -.25427 20.151 2.113)" gradientUnits="userSpaceOnUse"><stop class="tj6dwnbcs"/><stop offset="1" class="aeh1388xn"/></radialGradient><radialGradient id="iQtyKTb" cx="0" cy="0" r="1" gradientTransform="rotate(131.576 9.578 7.561)scale(1.29499 1.38067)" gradientUnits="userSpaceOnUse"><stop class="vyopt_bxu"/><stop offset="1" class="mo3rc5bif"/></radialGradient><radialGradient id="i2fc5pe" cx="0" cy="0" r="1" gradientTransform="matrix(.76093 0 0 1.33163 12.816 7.94)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="iOKPbhc" cx="0" cy="0" r="1" gradientTransform="matrix(.35847 -.26102 .29792 .40914 17.826 7.825)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="ixt0Koe" cx="0" cy="0" r="1" gradientTransform="matrix(.3561 -.65499 .38336 .20843 17.647 8.296)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="iGxZFRc" cx="0" cy="0" r="1" gradientTransform="matrix(.11243 .1113 -.14347 .14493 17.667 7.94)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="iGEehce" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.56676 .69755 0 16.616 7.388)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="iIYieQd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.59583 .74096 0 14.64 7.447)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="ijofsWs" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.83595 -5.20709 0 15.468 7.17)" gradientUnits="userSpaceOnUse"><stop offset=".619" class="rko8b-bmk"/><stop offset="1" class="whxihzpaf"/></radialGradient><radialGradient id="ix79aWb" cx="0" cy="0" r="1" gradientTransform="matrix(-.74456 -.50089 .2851 -.4238 17.447 10.506)" gradientUnits="userSpaceOnUse"><stop class="m13zyzbuk"/><stop offset="1" class="kzk-_ccou"/></radialGradient><radialGradient id="ijENDWb" cx="0" cy="0" r="1" gradientTransform="matrix(1.12361 -.2359 .14942 .7117 14.022 10.952)" gradientUnits="userSpaceOnUse"><stop class="m13zyzbuk"/><stop offset="1" class="kzk-_ccou"/></radialGradient><radialGradient id="iN1SHAb" cx="0" cy="0" r="1" gradientTransform="matrix(.34594 -1.28202 .6173 .16657 17.483 6.16)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="iAzPZOb" cx="0" cy="0" r="1" gradientTransform="matrix(1.65848 .15262 -.08206 .89176 16.77 5.396)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="iugVOWB" cx="0" cy="0" r="1" gradientTransform="matrix(0 .7281 -1.12763 0 15.599 4.21)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="iMqGUYd" cx="0" cy="0" r="1" gradientTransform="matrix(1.3329 -.97678 1.5303 2.0882 12.802 7.167)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="iAYN3rs" cx="0" cy="0" r="1" gradientTransform="matrix(0 .08538 -.2743 0 15.74 8.636)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="i4VQWhb" cx="0" cy="0" r="1" gradientTransform="matrix(.04518 -.26158 .77387 .13366 16.658 7.036)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="i3ZLgCe" cx="0" cy="0" r="1" gradientTransform="matrix(.04518 -.26159 .7739 .13368 14.426 7.035)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="iVlDZQc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35171 -.55944 0 16.543 7.644)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iSz7ibv" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 10.103 -.187)scale(.16399 .22578)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i40Olxb" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35173 -.55947 0 14.652 7.644)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iUar3tc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00335 -.21419 .25747 -.00403 14.528 7.739)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iHy6GKR" width="5.373" height="2.752" x="8.532" y="27.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.117647 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_613"/></filter><filter id="iIHK55d" width="5.373" height="2.752" x="18.399" y="27.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.117647 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_613"/></filter><filter id="i2ITrVc" width="6.055" height="5.783" x="15.962" y="6.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.54902 0 0 0 0 0.772549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_613"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.580392 0 0 0 0 0.760784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_613" result="effect2_innerShadow_4002_613"/></filter><filter id="ij1trId" width="5.188" height="8.109" x="16.797" y="9.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.352941 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_613"/></filter><filter id="izwVrxi" width="6.705" height="12.103" x="16.587" y="16.855" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.4 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_613"/></filter><filter id="iPz0o3b" width="11.118" height="12.357" x="8.285" y="16.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.509804 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_613"/></filter><filter id="iPNo0MP" width="6.488" height="5.992" x="8.619" y="9.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.501961 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_613"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.541176 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_613" result="effect2_innerShadow_4002_613"/></filter><filter id="ihiX2pe" width="4.196" height="9.342" x="12.799" y="9.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.458824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_613"/></filter><filter id="iSdsKZd" width="3.018" height="6.455" x="13.628" y="11.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_613" stdDeviation=".1"/></filter><filter id="itqVQPb" width="2.718" height="6.155" x="13.977" y="11.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.670588 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_613"/></filter><filter id="i75QFge" width="2.18" height="1.491" x="16.731" y="9.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.388235 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_613"/></filter><filter id="ic7MAsb" width="2.654" height="2.575" x="13.768" y="9.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.403922 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_613"/></filter><filter id="idXn0Sc" width="1.225" height="1.225" x="16.839" y="12.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.352941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_613"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_613" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.025" dy=".03"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.878431 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_613"/></filter><filter id="i2fY26Y" width="1.225" height="1.225" x="17.081" y="13.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.996078 0 0 0 0 0.321569 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_613"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_613" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.025" dy=".03"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.878431 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_613"/></filter><filter id="iHPJCYb" width="1.225" height="1.225" x="17.191" y="15.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.27451 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_613"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_613" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.025" dy=".03"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.878431 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_613"/></filter><filter id="iJNWPhe" width="1.124" height="1.036" x="10.671" y="16.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.27451 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_613"/></filter><filter id="izvQNRc" width="2.496" height="2.734" x="9.04" y="15.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.125"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.266667 0 0 0 0 0.352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_613"/></filter><filter id="igzPMrc" width="3.308" height="2.19" x="8.228" y="14.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.34902 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_613"/></filter><filter id="ippWjtb" width="1.381" height="1.353" x="18.793" y="3.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.290196 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_613"/></filter><filter id="iIfRjid" width=".87" height="1.395" x="21.197" y="2.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.278431 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_613"/></filter><filter id="if7OKLd" width=".87" height="1.395" x="20.578" y="2.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.278431 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_613"/></filter><filter id="ikkhpdc" width=".87" height="1.395" x="19.958" y="2.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.278431 0 0 0 0 0.227451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_613"/></filter><filter id="i9PbWGb" width="3.212" height="2.157" x="19.357" y="4.765" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.34902 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_613"/></filter><filter id="iiVgfRc" width="1.648" height="1.448" x="12.816" y="7.216" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_613"/></filter><filter id="i3VM1Fb" width="1.863" height="1.863" x="12.609" y="7.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_613" stdDeviation=".25"/></filter><filter id="iI61SUI" width="1.698" height="1.698" x="16.941" y="6.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_613"/></filter><filter id="ijH2J3c" width="1.863" height="1.863" x="16.734" y="7.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_613" stdDeviation=".25"/></filter><filter id="ijssDXd" width="4.498" height="5.315" x="13.362" y="5.501" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_613"/></filter><filter id="iw04bMm" width="2.841" height="2.33" x="15.172" y="5.001" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_613" stdDeviation=".25"/></filter><filter id="iRW8fGH" width="5.464" height="3.988" x="12.867" y="3.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_613"/></filter><filter id="ido56Rb" width="2.263" height="2.663" x="14.364" y="7.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_613" stdDeviation=".375"/></filter><filter id="iBCbIBd" width=".914" height="1.263" x="15.142" y="7.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_613" stdDeviation=".025"/></filter><filter id="iQWwvub" width="1.434" height="1.039" x="16.111" y="6.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_613"/></filter><filter id="ip1AHzd" width="1.434" height="1.039" x="13.879" y="6.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_613"/></filter><filter id="i39WLMc" width=".454" height=".415" x="16.169" y="7.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_613" stdDeviation=".05"/></filter><filter id="iUSnV9c" width=".613" height=".623" x="16.476" y="7.373" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_613" stdDeviation=".1"/></filter><filter id="iapXfFd" width=".654" height=".678" x="14.55" y="7.345" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_613" stdDeviation=".1"/></filter><filter id="iF4tNSb" width=".509" height=".419" x="14.28" y="7.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_613" stdDeviation=".05"/></filter><filter id="ibJkice" width=".862" height="1.409" x="13.146" y="5.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_613" stdDeviation=".125"/></filter><linearGradient id="iDxo0eI" x1="13.397" x2="8.532" y1="29.57" y2="29.57" gradientUnits="userSpaceOnUse"><stop class="leyn8uhkc"/><stop offset="1" class="m4prq-bhs"/></linearGradient><linearGradient id="imwSJ8b" x1="23.264" x2="18.399" y1="29.57" y2="29.57" gradientUnits="userSpaceOnUse"><stop class="leyn8uhkc"/><stop offset="1" class="m4prq-bhs"/></linearGradient><linearGradient id="i1ctYud" x1="21.817" x2="21.588" y1="6.747" y2="7.607" gradientUnits="userSpaceOnUse"><stop offset=".193" class="phi9sxixy"/><stop offset="1" class="y3iq9j8og"/></linearGradient><linearGradient id="iMovpyz" x1="19.689" x2="19.689" y1="17.492" y2="28.957" gradientUnits="userSpaceOnUse"><stop class="chtjorcfq"/><stop offset="1" class="a3ta3d8-l"/></linearGradient><linearGradient id="iKJ5SJE" x1="17.299" x2="12.085" y1="17.307" y2="25.695" gradientUnits="userSpaceOnUse"><stop class="wbm6gtb2b"/><stop offset="1" class="wsr-x9y-q"/></linearGradient><linearGradient id="izAx3Ud" x1="16.623" x2="16.623" y1="11.602" y2="17.289" gradientUnits="userSpaceOnUse"><stop class="ft8y4ezam"/><stop offset="1" class="dpzeg8stn"/></linearGradient><linearGradient id="igOfCoc" x1="14.389" x2="15.076" y1="19.664" y2="17.477" gradientUnits="userSpaceOnUse"><stop class="czfaoab9t"/><stop offset="1" class="q9y6v7blv"/></linearGradient><linearGradient id="iK9ACyb" x1="9.123" x2="9.795" y1="16.227" y2="17.305" gradientUnits="userSpaceOnUse"><stop class="xsew42bqa"/><stop offset="1" class="o08ppqslm"/></linearGradient><linearGradient id="iTYwXee" x1="19.912" x2="19.912" y1="3.891" y2="3.195" gradientUnits="userSpaceOnUse"><stop class="u3d2dfbjp"/><stop offset="1" class="l9m62bgua"/></linearGradient><linearGradient id="ivFV2Ge" x1="13.54" x2="13.262" y1="8.061" y2="8.061" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="i9nsGIc" x1="18.136" x2="17.781" y1="7.466" y2="8.566" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="iEPsRzd" x1="17.349" x2="14.037" y1="8.109" y2="8.602" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="irSC7Ub" x1="13.259" x2="14.075" y1="9.278" y2="9.249" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="i99YOKB" x1="17.708" x2="17.25" y1="8.914" y2="8.871" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="iTtxQJw" x1="15.368" x2="18.9" y1="6.814" y2="5.55" gradientUnits="userSpaceOnUse"><stop offset=".109" class="fxywcj73h"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="it5P2La" x1="15.224" x2="15.631" y1="8.394" y2="8.394" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="in35kve" x1="16.006" x2="15.561" y1="8.534" y2="8.528" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="icYVenQ" x1="15.683" x2="15.683" y1="8.856" y2="8.608" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="ixJCxRd" x1="16.881" x2="16.745" y1="7.667" y2="7.751" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="ihmw9rc" x1="14.974" x2="14.838" y1="7.667" y2="7.751" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iakUcke" x1="13.577" x2="13.577" y1="5.811" y2="6.746" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-dancing-medium-dark" /></template>
<style>
.a-g770t2u {
  fill: var(--svg-color--000, #000);
  d: path("M14.873 7.824a.22.22 0 0 0-.222-.221a.22.22 0 0 0-.197.323h.392a.2.2 0 0 0 .027-.102");
}

.a1bm4qc3u {
  d: path("M19.438 11.086c-.8-.988-1.708-1.432-2.078-1.547l-.562.188l1.234 7.671c1.576 0 2.842-.575 3.51-1.022a.45.45 0 0 0 .18-.48a13.3 13.3 0 0 0-2.284-4.81");
}

.a3ta3d8-l {
  stop-color: var(--svg-color--357ad1, #357AD1);
}

.a9sssdqqd {
  d: path("M18.577 10.89c-.23-.26-.686-.706-1.229-1.003h-.617l.316 1.39c.273-.042.976-.12 1.441-.172c.11-.013.162-.13.089-.214");
}

.aeh1388xn {
  stop-color: var(--svg-color--77544a, #77544A);
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.aujtu_bkk {
  cx: 17.665px;
  cy: 7.94px;
  r: 0.431px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.ball_rb6t {
  d: path("m9.322 17.597l-.282-1.363l2.172-.648l.31 1.548a.75.75 0 0 1-.572.878l-.729.164a.75.75 0 0 1-.899-.58");
}

.bc9b4ab2e {
  fill: var(--svg-color--000, #000);
  d: path("M16.323 7.824a.22.22 0 0 1 .221-.221a.22.22 0 0 1 .197.323h-.392a.2.2 0 0 1-.026-.102");
}

.bhb8ipbdm {
  cx: 17.794px;
  cy: 14.504px;
  r: 0.313px;
}

.bmux5s23h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.633 5.854v.389c-.003.064-.03.208-.112.27");
}

.bzjjhsbjs {
  fill: var(--svg-color--34a1f0, #34A1F0);
  fill-rule: evenodd;
  d: path("m10.035 11.029l4.216-1.199l.656 2.309l-3.852 1.095l.24 2.342l-2.387.246l-.279-2.718a1.95 1.95 0 0 1 1.406-2.075");
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
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

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.cvtthw6wc {
  d: path("M16.89 7.773a.36.36 0 0 0-.101-.2l-.113.123l.051.1z");
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.czfaoab9t {
  stop-color: var(--svg-color--225fcf, #225FCF);
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.d7z8f74ij {
  fill-rule: evenodd;
  d: path("M21.817 6.383L21.69 8.46a2.2 2.2 0 0 1-1.335 1.89l-3.454 1.47l-.939-2.21l3.34-1.42l.12-1.954z");
}

.d8s-on5pp {
  d: path("m17.317 5.501l-1.334.445a.454.454 0 0 0 .204.88l1.327-.177z");
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.dpzeg8stn {
  stop-color: var(--svg-color--ff6b3b, #FF6B3B);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e1witkb9q {
  stop-color: var(--svg-color--84665f, #84665F);
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

.eu3vkcbvq {
  stop-color: var(--svg-color--714d49, #714D49);
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.evsu6_b2z {
  d: path("M15.004 7.779c0-.125-.101-.209-.129-.234l-.125.121l.077.157z");
}

.f0cucabtr {
  stop-color: var(--svg-color--1e8acb, #1E8ACB);
}

.fdw40sw0m {
  width: 0.62px;
  height: 1.395px;
  x: 21.197px;
  y: 2.871px;
  fill: var(--svg-color--7b574f, #7B574F);
  rx: 0.31px;
}

.fglzf7x9d {
  stop-color: var(--svg-color--ff5d09, #FF5D09);
}

.flk9v203r {
  d: path("M16.516 7.519c.028.037-.03.082-.095.13c-.066.05-.115.084-.142.047c-.028-.036.003-.106.069-.155c.065-.049.14-.059.168-.022");
}

.fqpf1cbjx {
  fill: var(--svg-color--88014f, #88014F);
  d: path("M15.599 9.297c-.22 0-.427-.052-.6-.143c-.06-.03-.124.037-.087.091a.82.82 0 0 0 .687.367a.82.82 0 0 0 .686-.367c.038-.056-.026-.12-.086-.09c-.173.09-.378.142-.6.142");
}

.ft5dv1b6b {
  fill: none;
}

.ft8y4ezam {
  stop-color: var(--svg-color--ff9255, #FF9255);
}

.fxywcj73h {
  stop-color: var(--svg-color--a47f73, #A47F73);
}

.g4r-t1bcl {
  stop-color: var(--svg-color--4087da, #4087DA);
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.gnb7t6epd {
  stop-color: var(--svg-color--40b1ff, #40B1FF);
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.gtoocib1j {
  cx: 14.534px;
  cy: 7.602px;
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

.hg6oqob2v {
  stop-color: var(--svg-color--5c322f, #5C322F);
}

.hi05lwx5z {
  fill: var(--svg-color--3ea3f7, #3EA3F7);
  d: path("m12.876 12.71l1.153-2.823l1.643 1.418c1.34 2.11.963 5.853.466 7.596a.465.465 0 0 1-.592.306l-2.604-.797a.204.204 0 0 1-.136-.25c.195-.695.49-2.014.546-2.933c.056-.907-.273-2.024-.476-2.516");
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.hxi88nbzr {
  stop-color: var(--svg-color--2b8afb, #2B8AFB);
}

.hyi6vg4pw {
  stop-color: var(--svg-color--684640, #684640);
  stop-opacity: 0;
}

.i0b_c8grj {
  stop-color: var(--svg-color--2774e5, #2774E5);
}

.i38ihmb_i {
  cx: 14.534px;
  cy: 7.602px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.169px;
  ry: 0.085px;
}

.i8l7fq6-h {
  stop-color: var(--svg-color--4081dd, #4081DD);
  stop-opacity: 0;
}

.ibps_eqic {
  width: 1.191px;
  height: 0.754px;
  x: 10.929px;
  y: 16.017px;
  fill: var(--svg-color--7e5048, #7E5048);
  rx: 0.377px;
}

.irtsewoae {
  fill: var(--svg-color--35abf6, #35ABF6);
  fill-rule: evenodd;
  d: path("M21.817 6.383L21.69 8.46a2.2 2.2 0 0 1-1.335 1.89l-3.454 1.47l-.939-2.21l3.34-1.42l.12-1.954z");
}

.j5r2wxpvw {
  width: 0.62px;
  height: 1.395px;
  x: 19.958px;
  y: 2.871px;
  fill: var(--svg-color--7b574f, #7B574F);
  rx: 0.31px;
}

.j6id9usmg {
  stop-color: var(--svg-color--784c4a, #784C4A);
}

.jluwh2bfy {
  fill: var(--svg-color--352827, #352827);
  d: path("m13.963 6.76l.002-.002l.005-.005l.067-.046q.066-.043.182-.091a1.23 1.23 0 0 1 .648-.07a.231.231 0 0 1-.073.458a.77.77 0 0 0-.511.095l-.024.016l-.003.003a.231.231 0 0 1-.294-.358");
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.jzo6g3ltx {
  width: 0.645px;
  height: 2.293px;
  x: 19.547px;
  y: 1.938px;
  rx: 0.322px;
}

.k63icwbow {
  stop-color: var(--svg-color--311c1b, #311C1B);
}

.kd54_6u1z {
  stop-color: var(--svg-color--ff8337, #FF8337);
  stop-opacity: 0;
}

.kygm6qb6m {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.561 7.32a.606.606 0 0 0-.587.458a.12.12 0 0 0 .116.148h.967a.1.1 0 0 0 .099-.118a.61.61 0 0 0-.595-.489");
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.kzk-_ccou {
  stop-color: var(--svg-color--8b6a6b, #8B6A6B);
  stop-opacity: 0;
}

.kzysqdbiz {
  stop-color: var(--svg-color--307ba7, #307BA7);
  stop-opacity: 0;
}

.l3am5pbvj {
  stop-color: var(--svg-color--2b8afb, #2B8AFB);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.l9m62bgua {
  stop-color: var(--svg-color--6f4941, #6F4941);
  stop-opacity: 0;
}

.leyn8uhkc {
  stop-color: var(--svg-color--3f3641, #3F3641);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.lyqmr2bbc {
  cx: 17.551px;
  cy: 12.945px;
  r: 0.313px;
}

.m13zyzbuk {
  stop-color: var(--svg-color--8b6a6b, #8B6A6B);
}

.m4prq-bhs {
  stop-color: var(--svg-color--311e34, #311E34);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
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

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.nlkqldb7d {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.634 7.32c.283 0 .523.195.588.458a.12.12 0 0 1-.116.148h-.968a.1.1 0 0 1-.098-.118a.606.606 0 0 1 .594-.489");
}

.ntr0bqbzj {
  fill: var(--svg-color--714d45, #714D45);
  d: path("M18.882 3.54a.39.39 0 0 1 .546-.053l.497.411c.165.136.21.274.051.546c-.054.093-.207.298-.372.162l-.67-.521a.39.39 0 0 1-.052-.546");
}

.nxhf2dq-t {
  stop-color: var(--svg-color--3fa1f0, #3FA1F0);
  stop-opacity: 0;
}

.o_dq2zb-o {
  cx: 17.665px;
  cy: 7.94px;
  r: 0.431px;
}

.o08ppqslm {
  stop-color: var(--svg-color--73464e, #73464E);
  stop-opacity: 0;
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o7ak8nbtx {
  width: 0.62px;
  height: 1.395px;
  x: 20.578px;
  y: 2.871px;
  fill: var(--svg-color--7b574f, #7B574F);
  rx: 0.31px;
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.of4t_rsab {
  d: path("M16.544 7.437a.387.387 0 0 1 .373.49h-.747a.388.388 0 0 1 .375-.489");
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

.opfpvxndz {
  fill: var(--svg-color--352827, #352827);
  d: path("M17.212 6.76h-.002l-.002-.002l-.005-.005l-.067-.046a1.23 1.23 0 0 0-.83-.16a.231.231 0 0 0 .073.457a.77.77 0 0 1 .511.095l.024.016l.003.003a.231.231 0 0 0 .295-.358");
}

.oxm2fc9jy {
  stop-color: var(--svg-color--40b1ff, #40B1FF);
  stop-opacity: 0;
}

.oyt5f2bkb {
  d: path("M19.591 3.594h2.226v2.004h-2.226z");
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

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.pvj13sbsi {
  stop-color: var(--svg-color--896565, #896565);
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.q4v9atysu {
  d: path("M17.232 11.542c-.028-.648-.194-1.142-.282-1.292h-2.395l2.24 1.519c.191.129.447.003.437-.227");
}

.q9y6v7blv {
  stop-color: var(--svg-color--2f82e6, #2F82E6);
  stop-opacity: 0;
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

.qw2rl3bjm {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.516 7.519c.028.037-.03.082-.095.13c-.066.05-.115.084-.142.047c-.028-.036.003-.106.069-.155c.065-.049.14-.059.168-.022");
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rblhu8b8j {
  d: path("m17.688 5.131l.186.092a.85.85 0 0 1 .442.926l-.256 1.318c-.022.136-.112.227-.248.23l-.008.001s.024-.393.047-.624c.019-.188-.014-.246-.186-.417a.54.54 0 0 1-.163-.37v-.37a.25.25 0 0 0-.186-.231c-.28-.07-.86-.185-1.698-.185c-.837 0-1.419.116-1.698.185a.226.226 0 0 0-.186.231v.37a.46.46 0 0 1-.163.37l-.07.07c-.092.069-.139.208-.139.323c.023.255.047.625.047.625h-.022a.275.275 0 0 1-.258-.231l-.255-1.319a.885.885 0 0 1 .465-.902l.186-.092c.116-.07.232-.162.349-.254l.418-.44a.85.85 0 0 1 .954-.139c.233.07.489.07.721 0a1.05 1.05 0 0 1 1.023.232l.35.347a1 1 0 0 0 .348.254");
}

.rbqcrhr2a {
  stop-color: var(--svg-color--6f504a, #6F504A);
  stop-opacity: 0;
}

.rcasxucso {
  stop-color: var(--svg-color--349fe1, #349FE1);
  stop-opacity: 0;
}

.rko8b-bmk {
  stop-color: var(--svg-color--714250, #714250);
  stop-opacity: 0;
}

.rqwi4sb7b {
  cx: 13.54px;
  cy: 7.94px;
  r: 0.431px;
}

.s3rc45b6k {
  stop-color: var(--svg-color--3197dd, #3197DD);
  stop-opacity: 0;
}

.s5iez-b2n {
  fill: var(--svg-color--ff9457, #FF9457);
  d: path("M18.577 10.89c-.23-.26-.686-.706-1.229-1.003h-.617l.316 1.39c.273-.042.976-.12 1.441-.172c.11-.013.162-.13.089-.214");
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.su2ao5zll {
  d: path("m19.434 5.153l-.077 1.385a.1.1 0 0 0 .09.105l2.64.277a.3.3 0 0 0 .316-.391l-.464-1.42a.15.15 0 0 0-.14-.103l-2.161-.041a.2.2 0 0 0-.204.188");
}

.sxvf2qb2c {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m15.433 7.816l-.23.737a.234.234 0 0 0 .225.303h.341c.16 0 .273-.154.226-.303l-.23-.737c-.05-.163-.28-.163-.332 0");
}

.tcm98nmkx {
  stop-color: var(--svg-color--42aff6, #42AFF6);
  stop-opacity: 0;
}

.tj6dwnbcs {
  stop-color: var(--svg-color--8b7067, #8B7067);
}

.tkijdf1cs {
  stop-color: var(--svg-color--32272d, #32272D);
}

.tp3-xrbff {
  stop-color: var(--svg-color--3197dd, #3197DD);
}

.ts57h0bot {
  d: path("m13.963 6.76l.002-.002l.005-.005l.067-.046q.066-.043.182-.091a1.23 1.23 0 0 1 .648-.07a.231.231 0 0 1-.073.458a.77.77 0 0 0-.511.095l-.024.016l-.003.003a.231.231 0 0 1-.294-.358");
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.u2-6tpbfe {
  stop-color: var(--svg-color--d8cdf0, #D8CDF0);
}

.u3d2dfbjp {
  stop-color: var(--svg-color--6f4941, #6F4941);
}

.u8aws4lgo {
  stop-color: var(--svg-color--ff8337, #FF8337);
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.v139tp24n {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m15.48 7.887l-.356.737c-.044.151.061.303.211.303h.32c.15 0 .256-.154.212-.303l-.216-.737c-.047-.163-.123-.163-.171 0");
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.v4zb_95po {
  d: path("M14.65 7.437a.387.387 0 0 0-.372.49h.747a.39.39 0 0 0-.375-.489");
}

.v9ldxkc6l {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m17.688 5.131l.186.092a.85.85 0 0 1 .442.926l-.256 1.318c-.022.136-.112.227-.248.23l-.008.001s.024-.393.047-.624c.019-.188-.014-.246-.186-.417a.54.54 0 0 1-.163-.37v-.37a.25.25 0 0 0-.186-.231c-.28-.07-.86-.185-1.698-.185c-.837 0-1.419.116-1.698.185a.226.226 0 0 0-.186.231v.37a.46.46 0 0 1-.163.37l-.07.07c-.092.069-.139.208-.139.323c.023.255.047.625.047.625h-.022a.275.275 0 0 1-.258-.231l-.255-1.319a.885.885 0 0 1 .465-.902l.186-.092c.116-.07.232-.162.349-.254l.418-.44a.85.85 0 0 1 .954-.139c.233.07.489.07.721 0a1.05 1.05 0 0 1 1.023.232l.35.347a1 1 0 0 0 .348.254");
}

.vc9ew0biq {
  stop-color: var(--svg-color--5b302d, #5B302D);
}

.vgfjqtbdb {
  stop-color: var(--svg-color--301a2d, #301A2D);
  stop-opacity: 0;
}

.vjbaz8r2t {
  d: path("m15.433 7.816l-.23.737a.234.234 0 0 0 .225.303h.341c.16 0 .273-.154.226-.303l-.23-.737c-.05-.163-.28-.163-.332 0");
}

.vm6ce_jmk {
  d: path("M12.766 21.523c.217-.748.766-3.252 1.031-4.414l.422.18h4.684c-.816 2.398-2.664 3.657-4.004 5.875c-.409.677-.914 1.43-1.352 2.438c-.37.853-1.054 2.326-1.516 3.324a.574.574 0 0 1-.625.33c-1.533-.293-2.385-.943-3.014-1.765a.49.49 0 0 1-.012-.598c.72-.969 2.73-2.974 3.34-3.569c.675-.66.796-.937 1.046-1.8");
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.vqp8gziqg {
  d: path("M18.399 29.863V27.46h1.727l1.64.844c.5.404 1.212.712 1.715.904a.445.445 0 0 1 .265.565a.44.44 0 0 1-.412.288h-2.652a.26.26 0 0 1-.224-.123l-.424-.678a.141.141 0 0 0-.26.075v.625a.1.1 0 0 1-.102.102h-1.073a.2.2 0 0 1-.2-.2");
}

.vrtp9bcak {
  d: path("M13.362 7.05c0-.115.047-.254.14-.323l.07-.07a.46.46 0 0 0 .162-.37v-.37c0-.115.07-.208.186-.231c.28-.07.861-.185 1.698-.185c.838 0 1.419.116 1.698.185a.25.25 0 0 1 .186.231v.37c0 .139.07.278.163.37c.218.153.204.237.186.417c-.023.23-.046.624-.046.624h.007l-.115 1.716c-.07.768-.673 1.302-1.392 1.302h-1.392c-.742 0-1.322-.534-1.392-1.302c-.06-.787-.087-1.577-.159-2.364");
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

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w30s_lbtj {
  stop-color: var(--svg-color--4ab6fb, #4AB6FB);
  stop-opacity: 0;
}

.w5w_0vdfo {
  cx: 13.54px;
  cy: 7.94px;
  r: 0.724px;
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.wbm6gtb2b {
  stop-color: var(--svg-color--3fb1fe, #3FB1FE);
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.whxihzpaf {
  stop-color: var(--svg-color--5f3e52, #5F3E52);
}

.wqbs93h8n {
  stop-color: var(--svg-color--8d706a, #8D706A);
}

.wsr-x9y-q {
  stop-color: var(--svg-color--4195ec, #4195EC);
}

.x6-zvqbsc {
  stop-color: var(--svg-color--d93d03, #D93D03);
  stop-opacity: 0;
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xr70e_b6m {
  d: path("M13.387 7.674h.022s-.024-.37-.047-.624c0-.115.047-.254.14-.323l.07-.07a.46.46 0 0 0 .162-.37v-.37c0-.115.07-.208.186-.231c.28-.07.861-.185 1.698-.185c.838 0 1.419.116 1.698.185a.25.25 0 0 1 .186.231v.37c0 .139.07.278.163.37c.218.153.204.237.186.417c-.023.23-.046.624-.046.624h.007l-.115 1.716c-.07.768-.673 1.302-1.392 1.302h-1.392c-.742 0-1.322-.534-1.392-1.302z");
}

.xsew42bqa {
  stop-color: var(--svg-color--73464e, #73464E);
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y3iq9j8og {
  stop-color: var(--svg-color--3779d3, #3779D3);
  stop-opacity: 0;
}

.y8kcl1bix {
  stop-color: var(--svg-color--48454b, #48454B);
  stop-opacity: 0;
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.yeg_8ccml {
  stop-color: var(--svg-color--6b4c46, #6B4C46);
}

.yh2psxb-p {
  stop-color: var(--svg-color--4081dd, #4081DD);
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.yqnsa3b2w {
  d: path("m11.099 14.352l-2.586.139a.3.3 0 0 0-.252.434l.668 1.334a.15.15 0 0 0 .156.08l2.173-.318a.15.15 0 0 0 .128-.163l-.13-1.37a.15.15 0 0 0-.157-.136");
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.yy5jkisqu {
  d: path("M17.212 6.76h-.002l-.002-.002l-.005-.005l-.067-.046a1.23 1.23 0 0 0-.83-.16a.231.231 0 0 0 .073.457a.77.77 0 0 1 .511.095l.024.016l.003.003a.231.231 0 0 0 .295-.358");
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.z5ewkjg-x {
  d: path("m14.25 9.83l-4.215 1.199a1.95 1.95 0 0 0-.937.595l1.958 1.623l-.001-.013l3.852-1.095z");
}

.zezloqboo {
  cx: 17.665px;
  cy: 7.94px;
  r: 0.724px;
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
}

.zkcw-qija {
  stop-color: var(--svg-color--2688ed, #2688ED);
  stop-opacity: 0;
}

</style>
