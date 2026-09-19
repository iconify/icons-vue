<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#isj4UjY)"><path fill="url(#iDxo0eI)" class="mt-vedbkv"/><path fill="url(#iUnhLfc)" class="mt-vedbkv"/></g><g filter="url(#itYQeAd)"><path fill="url(#imwSJ8b)" class="vqp8gziqg"/><path fill="url(#i8zPUwe)" class="vqp8gziqg"/></g><g filter="url(#ieQawsb)"><path clip-rule="evenodd" class="irtsewoae"/><path fill="url(#iQZzNfc)" clip-rule="evenodd" class="d7z8f74ij"/><path fill="url(#i1ctYud)" clip-rule="evenodd" class="d7z8f74ij"/></g><g filter="url(#irzaQkc)"><path fill="url(#iacCiae)" class="a1bm4qc3u"/></g><g filter="url(#iGk1rHc)"><path fill="url(#iMovpyz)" class="vuihc-bcj"/><path fill="url(#iZUw8Bd)" class="vuihc-bcj"/><path fill="url(#it7XaSd)" class="vuihc-bcj"/><path fill="url(#icED1YI)" class="vuihc-bcj"/></g><g filter="url(#iLsv7Rd)"><path fill="url(#iKJ5SJE)" class="vm6ce_jmk"/><path fill="url(#iNtDdEc)" class="vm6ce_jmk"/><path fill="url(#iZSwmbe)" class="vm6ce_jmk"/><path fill="url(#iCEHRqb)" class="vm6ce_jmk"/></g><path fill="url(#izAx3Ud)" clip-rule="evenodd" class="eiz9jcf6n"/><path fill="url(#iQp1XNe)" clip-rule="evenodd" class="eiz9jcf6n"/><g filter="url(#ij1ef1b)"><path clip-rule="evenodd" class="bzjjhsbjs"/></g><path fill="url(#ihi3Nge)" class="z5ewkjg-x"/><g filter="url(#il2S4od)"><path class="hi05lwx5z"/></g><path fill="url(#igOfCoc)" class="eqxpq3aoz"/><path fill="url(#iXmPazd)" class="eqxpq3aoz"/><path fill="url(#iw40SNu)" class="eqxpq3aoz"/><g filter="url(#in8jdgc)"><path class="hebmvfbjm"/></g><g filter="url(#iytaPld)"><path class="hd_pc76ps"/></g><g filter="url(#ii0AJ2b)"><path class="s5iez-b2n"/><path fill="url(#inF27se)" class="a9sssdqqd"/></g><path fill="url(#igGrEBd)" class="q4v9atysu"/><path fill="url(#iHv7gRd)" class="q4v9atysu"/><path fill="url(#iUjB7Gb)" class="q4v9atysu"/><g filter="url(#iZsELiK)"><path class="n-o01qbda"/><path fill="url(#ixP2S7d)" class="eeo67f0sx"/></g><g filter="url(#iWZsG0f)"><circle fill="url(#i4G1Wfd)" class="lyqmr2bbc"/></g><g filter="url(#ic6Rw2h)"><circle fill="url(#iXXLOli)" class="bhb8ipbdm"/></g><g filter="url(#i9b8Qdd)"><circle fill="url(#imFUp4b)" class="ol6g7lb1q"/></g><g filter="url(#i3V4Aid)"><rect transform="rotate(32.175 10.93 16.017)" class="fnhrnudgu"/></g><g filter="url(#iwGXzBb)"><path fill="url(#iJkAMTS)" class="ball_rb6t"/><path fill="url(#i4DxRyT)" class="ball_rb6t"/></g><g filter="url(#imBr2mc)"><path fill="url(#iRRrLYL)" class="yqnsa3b2w"/></g><path fill="url(#i3M74zc)" class="oyt5f2bkb"/><rect fill="url(#i46QL8d)" class="jzo6g3ltx"/><g filter="url(#ip6NaLb)"><path class="nw7vbrbpr"/></g><g filter="url(#i5PMPld)"><rect class="zxbkl_amt"/></g><g filter="url(#iZJcdbd)"><rect class="y6eyh2aow"/></g><g filter="url(#icJhM7c)"><rect class="ry-ekhh-j"/></g><g filter="url(#iyCKd7b)"><path fill="url(#iQtyKTb)" class="su2ao5zll"/></g><g filter="url(#irrzXDc)"><circle fill="url(#iz9gVue)" class="d94oh9btf"/></g><g filter="url(#ikASb8b)"><circle fill="url(#i04B2zG)" class="wuv_a16vx"/></g><g filter="url(#iuTCwFe)"><circle fill="url(#iDcibuO)" class="odw4vhbkm"/><circle fill="url(#iYekz2i)" class="odw4vhbkm"/></g><g filter="url(#iuqe1Ie)"><circle class="nrb6rutxd"/><circle fill="url(#izhAXle)" class="zmb-7ybbe"/><circle fill="url(#icU43Gb)" class="zmb-7ybbe"/></g><g filter="url(#iataodd)"><path fill="url(#iBGS6zb)" class="qr__ilbau"/><path fill="url(#iHFxVee)" class="qr__ilbau"/><path fill="url(#ijN3xBd)" class="qr__ilbau"/><path fill="url(#iSx0H0d)" class="qr__ilbau"/><path fill="url(#iw3871b)" class="qr__ilbau"/><path fill="url(#icJXEyd)" class="qr__ilbau"/></g><g filter="url(#iUBD4od)"><path fill="url(#itNvo7c)" class="tt8d0zipw"/></g><g filter="url(#ibVtPPe)"><path class="r5_hzabpg"/><path fill="url(#ifuGoJb)" class="ql-dvux6w"/><path fill="url(#iC3ekwd)" class="ql-dvux6w"/><path fill="url(#iWuUmzc)" class="ql-dvux6w"/><path fill="url(#isJsJoe)" class="ql-dvux6w"/></g><g filter="url(#i6n0oMj)"><path class="zg7d64buy"/></g><g filter="url(#i5C3AAm)"><path class="q5lg0cblh"/><path fill="url(#iKMcEUb)" class="eqc1gmb9f"/><path fill="url(#iT49b3d)" class="eqc1gmb9f"/><path fill="url(#i6iDvYd)" class="eqc1gmb9f"/><path fill="url(#iXkhx2c)" class="eqc1gmb9f"/></g><path class="ckhrr8bwd"/><g filter="url(#imZDNhd)"><path class="aqzhrib_b"/></g><g filter="url(#iYpA4Kd)"><path class="xhauz4b4f"/></g><path class="qq7wqybbp"/><path fill="url(#iAekNub)" class="jdfc1ybpd"/><path class="wcnk0lwkc"/><g filter="url(#iwyAMue)"><path class="s070ztb0t"/><path fill="url(#iMWQ1bq)" class="lmrgvxujp"/></g><g filter="url(#iEhHShe)"><path fill="url(#iw4IU2c)" class="upgy9ybtr"/></g><path class="r47xu_bba"/><path fill="url(#iPOIi6H)" class="pep0evayi"/><path class="aeb7vncfg"/><g filter="url(#isjoHSd)"><path fill="url(#iHJNlxc)" class="ml3329emb"/></g><g filter="url(#idSgdcd)"><ellipse transform="rotate(-27.914 14.526 7.602)" class="yautbgb0o"/><ellipse fill="url(#iUAMqZc)" transform="rotate(-27.914 14.526 7.602)" class="sq2difwmt"/></g><g filter="url(#i0HUajb)"><path stroke="url(#i522dkc)" class="r086h34jy"/></g><defs><radialGradient id="iUnhLfc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88287 -.57813 .14717 -.4793 13.905 29.648)" gradientUnits="userSpaceOnUse"><stop class="vxv2m-bqm"/><stop offset="1" class="y8kcl1bix"/></radialGradient><radialGradient id="i8zPUwe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88287 -.57813 .14717 -.4793 23.772 29.648)" gradientUnits="userSpaceOnUse"><stop class="vxv2m-bqm"/><stop offset="1" class="y8kcl1bix"/></radialGradient><radialGradient id="iQZzNfc" cx="0" cy="0" r="1" gradientTransform="rotate(26.222 -7.656 45.296)scale(1.16697 .3839)" gradientUnits="userSpaceOnUse"><stop class="f0cucabtr"/><stop offset="1" class="rcasxucso"/></radialGradient><radialGradient id="iacCiae" cx="0" cy="0" r="1" gradientTransform="rotate(100.074 5.636 12.842)scale(6.98265 6.28539)" gradientUnits="userSpaceOnUse"><stop offset=".436" class="olwuq14vq"/><stop offset="1" class="g4r-t1bcl"/></radialGradient><radialGradient id="iZUw8Bd" cx="0" cy="0" r="1" gradientTransform="matrix(2.48435 3.38708 -1.82506 1.33864 17.053 19.619)" gradientUnits="userSpaceOnUse"><stop class="hxi88nbzr"/><stop offset="1" class="l3am5pbvj"/></radialGradient><radialGradient id="it7XaSd" cx="0" cy="0" r="1" gradientTransform="rotate(147.653 8.167 14.057)scale(1.92338 4.56348)" gradientUnits="userSpaceOnUse"><stop class="mygo_91-e"/><stop offset="1" class="w30s_lbtj"/></radialGradient><radialGradient id="icED1YI" cx="0" cy="0" r="1" gradientTransform="matrix(3.27144 3.19771 -1.19038 1.21783 18.456 17.996)" gradientUnits="userSpaceOnUse"><stop class="gnb7t6epd"/><stop offset="1" class="oxm2fc9jy"/></radialGradient><radialGradient id="iNtDdEc" cx="0" cy="0" r="1" gradientTransform="matrix(4.9441 -8.0188 3.4438 2.12332 10.387 28.67)" gradientUnits="userSpaceOnUse"><stop class="yh2psxb-p"/><stop offset="1" class="i8l7fq6-h"/></radialGradient><radialGradient id="iZSwmbe" cx="0" cy="0" r="1" gradientTransform="rotate(122.867 4.189 13.371)scale(2.40221 3.19663)" gradientUnits="userSpaceOnUse"><stop class="qg9ghcbvt"/><stop offset="1" class="tcm98nmkx"/></radialGradient><radialGradient id="iCEHRqb" cx="0" cy="0" r="1" gradientTransform="rotate(171.215 6.309 10.008)scale(2.38461 1.04291)" gradientUnits="userSpaceOnUse"><stop class="i0b_c8grj"/><stop offset="1" class="nxhf2dq-t"/></radialGradient><radialGradient id="iQp1XNe" cx="0" cy="0" r="1" gradientTransform="rotate(79.509 1.846 15.83)scale(.8581 .41486)" gradientUnits="userSpaceOnUse"><stop offset=".224" class="fglzf7x9d"/><stop offset="1" class="ch_7khbnn"/></radialGradient><radialGradient id="ihi3Nge" cx="0" cy="0" r="1" gradientTransform="rotate(-105.555 11.257 1.57)scale(1.57324 4.12566)" gradientUnits="userSpaceOnUse"><stop class="pb7i5tbeh"/><stop offset="1" class="zkcw-qija"/></radialGradient><radialGradient id="iXmPazd" cx="0" cy="0" r="1" gradientTransform="rotate(117.353 4.025 9.146)scale(3.64758 .73156)" gradientUnits="userSpaceOnUse"><stop offset=".216" class="tp3-xrbff"/><stop offset="1" class="s3rc45b6k"/></radialGradient><radialGradient id="iw40SNu" cx="0" cy="0" r="1" gradientTransform="matrix(-.75783 1.92969 -.78376 -.3078 14.271 9.766)" gradientUnits="userSpaceOnUse"><stop class="c1gbyobwf"/><stop offset="1" class="kzysqdbiz"/></radialGradient><radialGradient id="inF27se" cx="0" cy="0" r="1" gradientTransform="rotate(-148.57 10.887 2.8)scale(1.64805 1.14906)" gradientUnits="userSpaceOnUse"><stop offset=".64" class="kd54_6u1z"/><stop offset="1" class="u8aws4lgo"/></radialGradient><radialGradient id="igGrEBd" cx="0" cy="0" r="1" gradientTransform="rotate(-112.917 12.347 .255)scale(2.08657 3.55629)" gradientUnits="userSpaceOnUse"><stop class="ri7j818ay"/><stop offset="1" class="k63icwbow"/></radialGradient><radialGradient id="iHv7gRd" cx="0" cy="0" r="1" gradientTransform="matrix(.42187 1.42187 -.59557 .1767 16.967 10.102)" gradientUnits="userSpaceOnUse"><stop offset=".256" class="upl8m_stv"/><stop offset="1" class="gm9kqlonf"/></radialGradient><radialGradient id="iUjB7Gb" cx="0" cy="0" r="1" gradientTransform="matrix(.75781 .60547 -1.03195 1.29159 15.538 10.371)" gradientUnits="userSpaceOnUse"><stop class="i5re4xwgj"/><stop offset="1" class="pgj2tijvk"/></radialGradient><radialGradient id="ixP2S7d" cx="0" cy="0" r="1" gradientTransform="matrix(-.34375 2 -3.37016 -.57925 14.858 9.742)" gradientUnits="userSpaceOnUse"><stop offset=".222" class="omhpq8bny"/><stop offset=".75" class="x6-zvqbsc"/></radialGradient><radialGradient id="i4G1Wfd" cx="0" cy="0" r="1" gradientTransform="rotate(140.38 6.637 9.589)scale(.63706)" gradientUnits="userSpaceOnUse"><stop class="qkeppfmvx"/><stop offset="1" class="u2-6tpbfe"/></radialGradient><radialGradient id="iXXLOli" cx="0" cy="0" r="1" gradientTransform="rotate(140.38 6.477 10.411)scale(.63706)" gradientUnits="userSpaceOnUse"><stop class="qkeppfmvx"/><stop offset="1" class="u2-6tpbfe"/></radialGradient><radialGradient id="imFUp4b" cx="0" cy="0" r="1" gradientTransform="rotate(140.38 6.224 11.287)scale(.63706)" gradientUnits="userSpaceOnUse"><stop class="qkeppfmvx"/><stop offset="1" class="u2-6tpbfe"/></radialGradient><radialGradient id="iJkAMTS" cx="0" cy="0" r="1" gradientTransform="rotate(79.499 -4.177 14.405)scale(1.94812 .738)" gradientUnits="userSpaceOnUse"><stop class="i6bp981rz"/><stop offset="1" class="yk21hmsbp"/></radialGradient><radialGradient id="iRRrLYL" cx="0" cy="0" r="1" gradientTransform="matrix(-.88648 .98484 -1.05171 -.94667 10.533 14.808)" gradientUnits="userSpaceOnUse"><stop class="vyopt_bxu"/><stop offset="1" class="mo3rc5bif"/></radialGradient><radialGradient id="i3M74zc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.80323 -1.12499 1.48049 -2.37305 21.817 4.945)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="y91qr6bma"/><stop offset="1" class="jzzytcccd"/></radialGradient><radialGradient id="i46QL8d" cx="0" cy="0" r="1" gradientTransform="matrix(-.3125 .38281 -.31148 -.25427 20.151 2.113)" gradientUnits="userSpaceOnUse"><stop class="niqcevjah"/><stop offset="1" class="itnpxobwo"/></radialGradient><radialGradient id="iQtyKTb" cx="0" cy="0" r="1" gradientTransform="rotate(131.576 9.578 7.561)scale(1.29499 1.38067)" gradientUnits="userSpaceOnUse"><stop class="vyopt_bxu"/><stop offset="1" class="mo3rc5bif"/></radialGradient><radialGradient id="iz9gVue" cx="0" cy="0" r="1" gradientTransform="matrix(.76093 0 0 1.33163 12.807 7.94)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="x3sd7rf5r"/><stop offset="1" class="dsm4f-bda"/></radialGradient><radialGradient id="iYekz2i" cx="0" cy="0" r="1" gradientTransform="matrix(.35847 -.26102 .29792 .40914 17.818 7.825)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ytssyfa7a"/><stop offset="1" class="fnfe_1psv"/></radialGradient><radialGradient id="izhAXle" cx="0" cy="0" r="1" gradientTransform="matrix(.3561 -.65498 .38336 .20843 17.639 8.296)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="lvos55blo"/><stop offset=".916" class="bvmj8ubsx"/></radialGradient><radialGradient id="icU43Gb" cx="0" cy="0" r="1" gradientTransform="matrix(.11243 .1113 -.14347 .14493 17.657 7.94)" gradientUnits="userSpaceOnUse"><stop class="iqm2531qk"/><stop offset="1" class="n3g96cceg"/></radialGradient><radialGradient id="ijN3xBd" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.08087 -4.18211 0 15.46 7.854)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="iSx0H0d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.56676 .69755 0 16.607 7.388)" gradientUnits="userSpaceOnUse"><stop class="kb28pwbin"/><stop offset="1" class="uck_nmbag"/></radialGradient><radialGradient id="iw3871b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.6031 .75 0 14.63 7.374)" gradientUnits="userSpaceOnUse"><stop class="j7sc31byj"/><stop offset="1" class="e9zt2gbxt"/></radialGradient><radialGradient id="icJXEyd" cx="0" cy="0" r="1" gradientTransform="rotate(-166.409 9.353 4.266)scale(1.2674 .74468)" gradientUnits="userSpaceOnUse"><stop offset=".136" class="ph-yb3bws"/><stop offset="1" class="az2la2bjr"/></radialGradient><radialGradient id="ifuGoJb" cx="0" cy="0" r="1" gradientTransform="matrix(.34594 -1.28202 .47541 .12829 17.474 6.16)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="iC3ekwd" cx="0" cy="0" r="1" gradientTransform="matrix(1.65848 .15263 -.08207 .89176 16.763 5.396)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="iWuUmzc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .7281 -1.12763 0 15.59 4.21)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="isJsJoe" cx="0" cy="0" r="1" gradientTransform="matrix(1.3329 -.97678 1.5303 2.0882 12.794 7.167)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="iXkhx2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 .08538 -.2743 0 15.732 8.636)" gradientUnits="userSpaceOnUse"><stop class="ldpzz4bsg"/><stop offset="1" class="xtaxaigve"/></radialGradient><radialGradient id="iAekNub" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35171 -.55944 0 16.535 7.644)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iMWQ1bq" cx="0" cy="0" r="1" gradientTransform="matrix(-.10022 -.12916 .17781 -.13798 16.434 7.681)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iPOIi6H" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35173 -.55947 0 14.643 7.644)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iUAMqZc" cx="0" cy="0" r="1" gradientTransform="matrix(-.00335 -.21419 .25747 -.00403 14.519 7.739)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="isj4UjY" width="5.373" height="2.752" x="8.532" y="27.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.117647 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_610"/></filter><filter id="itYQeAd" width="5.373" height="2.752" x="18.399" y="27.311" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.117647 0 0 0 0 0.290196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_610"/></filter><filter id="ieQawsb" width="6.055" height="5.783" x="15.962" y="6.237" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.54902 0 0 0 0 0.772549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_610"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.196078 0 0 0 0 0.580392 0 0 0 0 0.760784 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_610" result="effect2_innerShadow_4002_610"/></filter><filter id="irzaQkc" width="5.188" height="8.109" x="16.797" y="9.289" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.141176 0 0 0 0 0.352941 0 0 0 0 0.752941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_610"/></filter><filter id="iGk1rHc" width="6.705" height="12.103" x="16.587" y="16.855" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.4 0 0 0 0 0.858824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_610"/></filter><filter id="iLsv7Rd" width="11.118" height="12.357" x="8.285" y="16.909" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.215686 0 0 0 0 0.509804 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_610"/></filter><filter id="ij1ef1b" width="6.488" height="5.992" x="8.619" y="9.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.501961 0 0 0 0 0.717647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_610"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.184314 0 0 0 0 0.541176 0 0 0 0 0.701961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_610" result="effect2_innerShadow_4002_610"/></filter><filter id="il2S4od" width="4.196" height="9.342" x="12.799" y="9.887" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.458824 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_610"/></filter><filter id="in8jdgc" width="3.018" height="6.455" x="13.628" y="11.143" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_610" stdDeviation=".1"/></filter><filter id="iytaPld" width="2.718" height="6.155" x="13.977" y="11.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.172549 0 0 0 0 0.670588 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_610"/></filter><filter id="ii0AJ2b" width="2.18" height="1.491" x="16.731" y="9.787" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".3" dy="-.1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.388235 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_610"/></filter><filter id="iZsELiK" width="2.654" height="2.575" x="13.768" y="9.733" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.886275 0 0 0 0 0.403922 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_610"/></filter><filter id="iWZsG0f" width="1.225" height="1.225" x="16.839" y="12.433" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 1 0 0 0 0 0.352941 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_610"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_610" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.025" dy=".03"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.878431 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_610"/></filter><filter id="ic6Rw2h" width="1.225" height="1.225" x="17.081" y="13.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.996078 0 0 0 0 0.321569 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_610"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_610" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.025" dy=".03"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.878431 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_610"/></filter><filter id="i9b8Qdd" width="1.225" height="1.225" x="17.191" y="15.702" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" operator="out"/><feColorMatrix values="0 0 0 0 0.956863 0 0 0 0 0.27451 0 0 0 0 0.176471 0 0 0 1 0"/><feBlend in2="BackgroundImageFix" result="effect1_dropShadow_4002_610"/><feBlend in="SourceGraphic" in2="effect1_dropShadow_4002_610" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.025" dy=".03"/><feGaussianBlur stdDeviation=".025"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.878431 0 0 0 0 0.976471 0 0 0 1 0"/><feBlend in2="shape" result="effect2_innerShadow_4002_610"/></filter><filter id="i3V4Aid" width="1.124" height="1.036" x="10.671" y="16.11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.05"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.12549 0 0 0 0 0.137255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_610"/></filter><filter id="iwGXzBb" width="2.496" height="2.734" x="9.04" y="15.461" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.125"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.137255 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_610"/></filter><filter id="imBr2mc" width="3.308" height="2.19" x="8.228" y="14.151" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.34902 0 0 0 0 0.278431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_610"/></filter><filter id="ip6NaLb" width="1.381" height="1.353" x="18.793" y="3.298" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.227451 0 0 0 0 0.121569 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_610"/></filter><filter id="i5PMPld" width=".87" height="1.395" x="21.197" y="2.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.141176 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_610"/></filter><filter id="iZJcdbd" width=".87" height="1.395" x="20.578" y="2.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.141176 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_610"/></filter><filter id="icJhM7c" width=".87" height="1.395" x="19.958" y="2.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.141176 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_610"/></filter><filter id="iyCKd7b" width="3.212" height="2.157" x="19.357" y="4.765" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.2"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.34902 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_610"/></filter><filter id="irrzXDc" width="1.648" height="1.448" x="12.807" y="7.216" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.270588 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_610"/></filter><filter id="ikASb8b" width="1.863" height="1.863" x="12.6" y="7.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_610" stdDeviation=".25"/></filter><filter id="iuTCwFe" width="1.698" height="1.698" x="16.933" y="6.966" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.141176 0 0 0 0 0.223529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_610"/></filter><filter id="iuqe1Ie" width="1.863" height="1.863" x="16.725" y="7.008" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_610" stdDeviation=".25"/></filter><filter id="iataodd" width="4.498" height="5.315" x="13.353" y="5.501" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.109804 0 0 0 0 0.0509804 0 0 0 0 0.0509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_610"/></filter><filter id="iUBD4od" width="3.841" height="3.33" x="14.664" y="4.501" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_610" stdDeviation=".5"/></filter><filter id="ibVtPPe" width="5.464" height="3.988" x="12.858" y="3.71" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_610"/></filter><filter id="i6n0oMj" width="2.263" height="2.663" x="14.355" y="7.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_610" stdDeviation=".375"/></filter><filter id="i5C3AAm" width=".914" height="1.263" x="15.133" y="7.644" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_610" stdDeviation=".025"/></filter><filter id="imZDNhd" width="1.434" height="1.039" x="16.103" y="6.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_610"/></filter><filter id="iYpA4Kd" width="1.434" height="1.039" x="13.871" y="6.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_610"/></filter><filter id="iwyAMue" width=".454" height=".415" x="16.16" y="7.397" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_610" stdDeviation=".05"/></filter><filter id="iEhHShe" width=".612" height=".622" x="16.467" y="7.373" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_610" stdDeviation=".1"/></filter><filter id="isjoHSd" width=".653" height=".677" x="14.542" y="7.345" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_610" stdDeviation=".1"/></filter><filter id="idSgdcd" width=".509" height=".419" x="14.271" y="7.393" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_610" stdDeviation=".05"/></filter><filter id="i0HUajb" width=".862" height="1.409" x="13.138" y="5.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_610" stdDeviation=".125"/></filter><linearGradient id="iDxo0eI" x1="13.397" x2="8.532" y1="29.57" y2="29.57" gradientUnits="userSpaceOnUse"><stop class="leyn8uhkc"/><stop offset="1" class="m4prq-bhs"/></linearGradient><linearGradient id="imwSJ8b" x1="23.264" x2="18.399" y1="29.57" y2="29.57" gradientUnits="userSpaceOnUse"><stop class="leyn8uhkc"/><stop offset="1" class="m4prq-bhs"/></linearGradient><linearGradient id="i1ctYud" x1="21.817" x2="21.588" y1="6.747" y2="7.607" gradientUnits="userSpaceOnUse"><stop offset=".193" class="phi9sxixy"/><stop offset="1" class="y3iq9j8og"/></linearGradient><linearGradient id="iMovpyz" x1="19.689" x2="19.689" y1="17.492" y2="28.957" gradientUnits="userSpaceOnUse"><stop class="chtjorcfq"/><stop offset="1" class="a3ta3d8-l"/></linearGradient><linearGradient id="iKJ5SJE" x1="17.299" x2="12.085" y1="17.307" y2="25.695" gradientUnits="userSpaceOnUse"><stop class="wbm6gtb2b"/><stop offset="1" class="wsr-x9y-q"/></linearGradient><linearGradient id="izAx3Ud" x1="16.623" x2="16.623" y1="11.602" y2="17.289" gradientUnits="userSpaceOnUse"><stop class="ft8y4ezam"/><stop offset="1" class="dpzeg8stn"/></linearGradient><linearGradient id="igOfCoc" x1="14.389" x2="15.076" y1="19.664" y2="17.477" gradientUnits="userSpaceOnUse"><stop class="czfaoab9t"/><stop offset="1" class="q9y6v7blv"/></linearGradient><linearGradient id="i4DxRyT" x1="9.123" x2="9.795" y1="16.227" y2="17.305" gradientUnits="userSpaceOnUse"><stop class="pxbf6eb5r"/><stop offset="1" class="l9trnvq1c"/></linearGradient><linearGradient id="i04B2zG" x1="13.531" x2="13.254" y1="8.061" y2="8.061" gradientUnits="userSpaceOnUse"><stop class="fbs6uccsw"/><stop offset="1" class="np-b1wbds"/></linearGradient><linearGradient id="iDcibuO" x1="18.128" x2="17.773" y1="7.466" y2="8.566" gradientUnits="userSpaceOnUse"><stop class="o1rzobcjq"/><stop offset="1" class="acjykw8xe"/></linearGradient><linearGradient id="iBGS6zb" x1="17.34" x2="14.029" y1="8.109" y2="8.602" gradientUnits="userSpaceOnUse"><stop class="cdm_o50ho"/><stop offset="1" class="ahguepbtf"/></linearGradient><linearGradient id="iHFxVee" x1="13.25" x2="14.232" y1="9.278" y2="9.216" gradientUnits="userSpaceOnUse"><stop offset=".283" class="j-n0q842a"/><stop offset="1" class="o-j_7gbpq"/></linearGradient><linearGradient id="itNvo7c" x1="16.006" x2="19.742" y1="6.644" y2="5.358" gradientUnits="userSpaceOnUse"><stop class="cgqcq-bjq"/><stop offset="1" class="o1syipbau"/></linearGradient><linearGradient id="iKMcEUb" x1="15.215" x2="15.622" y1="8.394" y2="8.394" gradientUnits="userSpaceOnUse"><stop class="o6hm6qxaj"/><stop offset="1" class="mg63gccek"/></linearGradient><linearGradient id="iT49b3d" x1="15.997" x2="15.552" y1="8.534" y2="8.528" gradientUnits="userSpaceOnUse"><stop class="yww6tz8di"/><stop offset="1" class="n-4z7qb5o"/></linearGradient><linearGradient id="i6iDvYd" x1="15.675" x2="15.675" y1="8.856" y2="8.608" gradientUnits="userSpaceOnUse"><stop class="xtiplndwl"/><stop offset="1" class="h8-lntwqp"/></linearGradient><linearGradient id="iw4IU2c" x1="16.871" x2="16.736" y1="7.667" y2="7.751" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iHJNlxc" x1="14.965" x2="14.829" y1="7.667" y2="7.751" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="i522dkc" x1="13.569" x2="13.569" y1="5.811" y2="6.746" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-dancing-dark" /></template>
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

.acjykw8xe {
  stop-color: var(--svg-color--452a31, #452A31);
}

.aeb7vncfg {
  fill: var(--svg-color--000, #000);
  d: path("M14.864 7.824a.22.22 0 0 0-.222-.221a.22.22 0 0 0-.197.323h.393a.2.2 0 0 0 .026-.102");
}

.ahguepbtf {
  stop-color: var(--svg-color--3c2828, #3C2828);
}

.aqzhrib_b {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M17.203 6.76h-.001l-.002-.002l-.005-.005l-.067-.046a1.23 1.23 0 0 0-.83-.16a.231.231 0 1 0 .072.457a.77.77 0 0 1 .512.095l.023.016l.004.003a.231.231 0 0 0 .294-.358");
}

.az2la2bjr {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
  stop-opacity: 0;
}

.ball_rb6t {
  d: path("m9.322 17.597l-.282-1.363l2.172-.648l.31 1.548a.75.75 0 0 1-.572.878l-.729.164a.75.75 0 0 1-.899-.58");
}

.bhb8ipbdm {
  cx: 17.794px;
  cy: 14.504px;
  r: 0.313px;
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bvmj8ubsx {
  stop-color: var(--svg-color--31191a, #31191A);
}

.bzjjhsbjs {
  fill: var(--svg-color--34a1f0, #34A1F0);
  fill-rule: evenodd;
  d: path("m10.035 11.029l4.216-1.199l.656 2.309l-3.852 1.095l.24 2.342l-2.387.246l-.279-2.718a1.95 1.95 0 0 1 1.406-2.075");
}

.c1gbyobwf {
  stop-color: var(--svg-color--307ba7, #307BA7);
}

.cdm_o50ho {
  stop-color: var(--svg-color--533531, #533531);
}

.cgqcq-bjq {
  stop-color: var(--svg-color--675454, #675454);
}

.ch_7khbnn {
  stop-color: var(--svg-color--ff5d09, #FF5D09);
  stop-opacity: 0;
}

.chtjorcfq {
  stop-color: var(--svg-color--44b9ff, #44B9FF);
}

.ckhrr8bwd {
  fill: var(--svg-color--2a0219, #2A0219);
  d: path("M15.59 9.297c-.22 0-.427-.052-.6-.143c-.06-.03-.124.037-.086.091a.82.82 0 0 0 .686.367a.82.82 0 0 0 .686-.367c.038-.056-.026-.12-.085-.09c-.174.09-.379.142-.601.142");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.czfaoab9t {
  stop-color: var(--svg-color--225fcf, #225FCF);
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d7z8f74ij {
  fill-rule: evenodd;
  d: path("M21.817 6.383L21.69 8.46a2.2 2.2 0 0 1-1.335 1.89l-3.454 1.47l-.939-2.21l3.34-1.42l.12-1.954z");
}

.d94oh9btf {
  cx: 13.531px;
  cy: 7.94px;
  r: 0.724px;
}

.dpzeg8stn {
  stop-color: var(--svg-color--ff6b3b, #FF6B3B);
}

.dsm4f-bda {
  stop-color: var(--svg-color--332423, #332423);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e9zt2gbxt {
  stop-color: var(--svg-color--351d26, #351D26);
  stop-opacity: 0;
}

.eeo67f0sx {
  d: path("m13.77 11.97l.262-2.087h.418l1.833 1.408a.1.1 0 0 1-.024.172l-2.08.823a.3.3 0 0 1-.408-.316");
}

.eiz9jcf6n {
  fill-rule: evenodd;
  d: path("M18.407 10.93c.515 1.086 1.031 3.898.515 6.36H14.83c-.058-1.746-.282-5.607-.719-7.095h3.438zm-1.457-.68c.088.15.254.644.282 1.292c.01.23-.246.356-.436.227l-2.24-1.519z");
}

.eqc1gmb9f {
  d: path("m15.424 7.816l-.23.737a.234.234 0 0 0 .226.303h.34c.16 0 .273-.154.226-.303l-.23-.737c-.05-.163-.28-.163-.332 0");
}

.eqxpq3aoz {
  d: path("m12.876 12.71l1.157-2.827l1.64 1.422c1.34 2.11.963 5.853.465 7.596a.465.465 0 0 1-.592.306l-2.604-.797a.204.204 0 0 1-.136-.25c.195-.695.49-2.014.546-2.933c.056-.907-.273-2.024-.476-2.516");
}

.f0cucabtr {
  stop-color: var(--svg-color--1e8acb, #1E8ACB);
}

.fbs6uccsw {
  stop-color: var(--svg-color--281920, #281920);
}

.fglzf7x9d {
  stop-color: var(--svg-color--ff5d09, #FF5D09);
}

.fnfe_1psv {
  stop-color: var(--svg-color--40272a, #40272A);
  stop-opacity: 0;
}

.fnhrnudgu {
  width: 1.191px;
  height: 0.754px;
  x: 10.929px;
  y: 16.017px;
  fill: var(--svg-color--482824, #482824);
  rx: 0.377px;
}

.ft5dv1b6b {
  fill: none;
}

.ft8y4ezam {
  stop-color: var(--svg-color--ff9255, #FF9255);
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.g4r-t1bcl {
  stop-color: var(--svg-color--4087da, #4087DA);
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.gm9kqlonf {
  stop-color: var(--svg-color--5b4d4c, #5B4D4C);
  stop-opacity: 0;
}

.gnb7t6epd {
  stop-color: var(--svg-color--40b1ff, #40B1FF);
}

.h8-lntwqp {
  stop-color: var(--svg-color--3f222f, #3F222F);
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

.hxi88nbzr {
  stop-color: var(--svg-color--2b8afb, #2B8AFB);
}

.i0b_c8grj {
  stop-color: var(--svg-color--2774e5, #2774E5);
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
}

.i5re4xwgj {
  stop-color: var(--svg-color--231213, #231213);
}

.i6bp981rz {
  stop-color: var(--svg-color--5b4847, #5B4847);
}

.i8l7fq6-h {
  stop-color: var(--svg-color--4081dd, #4081DD);
  stop-opacity: 0;
}

.iqm2531qk {
  stop-color: var(--svg-color--352123, #352123);
}

.irtsewoae {
  fill: var(--svg-color--35abf6, #35ABF6);
  fill-rule: evenodd;
  d: path("M21.817 6.383L21.69 8.46a2.2 2.2 0 0 1-1.335 1.89l-3.454 1.47l-.939-2.21l3.34-1.42l.12-1.954z");
}

.itnpxobwo {
  stop-color: var(--svg-color--402a27, #402A27);
}

.j-n0q842a {
  stop-color: var(--svg-color--564440, #564440);
}

.j7sc31byj {
  stop-color: var(--svg-color--351d26, #351D26);
}

.jdfc1ybpd {
  d: path("M16.536 7.437a.387.387 0 0 1 .373.49h-.748a.388.388 0 0 1 .375-.489");
}

.jzo6g3ltx {
  width: 0.645px;
  height: 2.293px;
  x: 19.547px;
  y: 1.938px;
  rx: 0.322px;
}

.jzzytcccd {
  stop-color: var(--svg-color--341e20, #341E20);
}

.k63icwbow {
  stop-color: var(--svg-color--311c1b, #311C1B);
}

.kb28pwbin {
  stop-color: var(--svg-color--412628, #412628);
}

.kd54_6u1z {
  stop-color: var(--svg-color--ff8337, #FF8337);
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

.l9trnvq1c {
  stop-color: var(--svg-color--39272d, #39272D);
  stop-opacity: 0;
}

.ldpzz4bsg {
  stop-color: var(--svg-color--624e4d, #624E4D);
}

.leyn8uhkc {
  stop-color: var(--svg-color--3f3641, #3F3641);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lmrgvxujp {
  d: path("M16.506 7.52c.028.036-.03.08-.095.13c-.065.049-.114.083-.141.046c-.028-.037.003-.106.068-.155c.066-.049.14-.058.168-.022");
}

.lvos55blo {
  stop-color: var(--svg-color--31191a, #31191A);
  stop-opacity: 0;
}

.lyqmr2bbc {
  cx: 17.551px;
  cy: 12.945px;
  r: 0.313px;
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m4prq-bhs {
  stop-color: var(--svg-color--311e34, #311E34);
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mg63gccek {
  stop-color: var(--svg-color--3d2928, #3D2928);
  stop-opacity: 0;
}

.ml3329emb {
  d: path("M14.995 7.778c0-.125-.101-.208-.129-.233l-.124.12l.076.157z");
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

.n-4z7qb5o {
  stop-color: var(--svg-color--624d4b, #624D4B);
  stop-opacity: 0;
}

.n-o01qbda {
  fill: var(--svg-color--ff8146, #FF8146);
  d: path("m13.77 11.97l.262-2.087h.418l1.833 1.408a.1.1 0 0 1-.024.172l-2.08.823a.3.3 0 0 1-.408-.316");
}

.n3g96cceg {
  stop-color: var(--svg-color--352123, #352123);
  stop-opacity: 0;
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.niqcevjah {
  stop-color: var(--svg-color--5d4d4a, #5D4D4A);
}

.np-b1wbds {
  stop-color: var(--svg-color--27161d, #27161D);
}

.nrb6rutxd {
  cx: 17.656px;
  cy: 7.94px;
  r: 0.431px;
  fill: var(--svg-color--463133, #463133);
}

.nw7vbrbpr {
  fill: var(--svg-color--382422, #382422);
  d: path("M18.882 3.54a.39.39 0 0 1 .546-.053l.497.411c.165.136.21.274.051.546c-.054.093-.207.298-.372.162l-.67-.521a.39.39 0 0 1-.052-.546");
}

.nxhf2dq-t {
  stop-color: var(--svg-color--3fa1f0, #3FA1F0);
  stop-opacity: 0;
}

.o-j_7gbpq {
  stop-color: var(--svg-color--564440, #564440);
  stop-opacity: 0;
}

.o1rzobcjq {
  stop-color: var(--svg-color--635251, #635251);
}

.o1syipbau {
  stop-color: var(--svg-color--685654, #685654);
  stop-opacity: 0;
}

.o6hm6qxaj {
  stop-color: var(--svg-color--3d2928, #3D2928);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.odw4vhbkm {
  cx: 17.656px;
  cy: 7.94px;
  r: 0.724px;
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

.pb7i5tbeh {
  stop-color: var(--svg-color--346dd8, #346DD8);
}

.pep0evayi {
  d: path("M14.642 7.437a.387.387 0 0 0-.373.49h.748a.39.39 0 0 0-.375-.489");
}

.pgj2tijvk {
  stop-color: var(--svg-color--231213, #231213);
  stop-opacity: 0;
}

.ph-yb3bws {
  stop-color: var(--svg-color--5b4b4d, #5B4B4D);
}

.phi9sxixy {
  stop-color: var(--svg-color--3779d3, #3779D3);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pxbf6eb5r {
  stop-color: var(--svg-color--39272d, #39272D);
}

.q4v9atysu {
  d: path("M17.232 11.542c-.028-.648-.194-1.142-.282-1.292h-2.395l2.24 1.519c.191.129.447.003.437-.227");
}

.q5lg0cblh {
  fill: var(--svg-color--4b3034, #4B3034);
  d: path("m15.424 7.816l-.23.737a.234.234 0 0 0 .226.303h.34c.16 0 .273-.154.226-.303l-.23-.737c-.05-.163-.28-.163-.332 0");
}

.q9y6v7blv {
  stop-color: var(--svg-color--2f82e6, #2F82E6);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qg9ghcbvt {
  stop-color: var(--svg-color--42aff6, #42AFF6);
}

.qkeppfmvx {
  stop-color: var(--svg-color--ded7f4, #DED7F4);
}

.ql-dvux6w {
  d: path("m17.68 5.131l.186.092a.85.85 0 0 1 .442.926l-.256 1.318c-.023.136-.113.227-.248.23l-.008.001s.023-.393.047-.624c.018-.188-.014-.246-.187-.417a.54.54 0 0 1-.162-.37v-.37a.25.25 0 0 0-.186-.231c-.28-.07-.861-.185-1.698-.185c-.838 0-1.42.116-1.698.185a.226.226 0 0 0-.186.231v.37a.46.46 0 0 1-.163.37l-.07.07c-.093.069-.14.208-.14.323c.024.255.047.625.047.625h-.021a.274.274 0 0 1-.258-.231l-.256-1.319a.885.885 0 0 1 .465-.902l.186-.092c.117-.07.233-.162.35-.254l.418-.44a.85.85 0 0 1 .954-.139c.232.07.488.07.72 0a1.05 1.05 0 0 1 1.024.232l.349.347a1 1 0 0 0 .349.254");
}

.qq7wqybbp {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.626 7.32c.283 0 .522.195.587.458a.12.12 0 0 1-.116.148h-.967a.1.1 0 0 1-.099-.118a.606.606 0 0 1 .595-.489");
}

.qr__ilbau {
  d: path("M13.379 7.674h.02s-.022-.37-.046-.624c0-.115.047-.254.14-.323l.07-.07a.46.46 0 0 0 .162-.37v-.37c0-.115.07-.208.187-.231c.279-.07.86-.185 1.697-.185s1.42.116 1.698.185a.25.25 0 0 1 .186.231v.37c0 .139.07.278.163.37c.218.153.204.237.186.417c-.023.23-.046.624-.046.624h.008l-.116 1.716c-.07.768-.672 1.302-1.392 1.302h-1.392c-.742 0-1.322-.534-1.392-1.302z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r086h34jy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M13.625 5.854v.389c-.004.064-.031.208-.112.27");
}

.r47xu_bba {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.552 7.32a.605.605 0 0 0-.587.458a.12.12 0 0 0 .116.148h.967a.1.1 0 0 0 .099-.118a.61.61 0 0 0-.595-.489");
}

.r5_hzabpg {
  fill: var(--svg-color--21181b, #21181B);
  d: path("m17.68 5.131l.186.092a.85.85 0 0 1 .442.926l-.256 1.318c-.023.136-.113.227-.248.23l-.008.001s.023-.393.047-.624c.018-.188-.014-.246-.187-.417a.54.54 0 0 1-.162-.37v-.37a.25.25 0 0 0-.186-.231c-.28-.07-.861-.185-1.698-.185c-.838 0-1.42.116-1.698.185a.226.226 0 0 0-.186.231v.37a.46.46 0 0 1-.163.37l-.07.07c-.093.069-.14.208-.14.323c.024.255.047.625.047.625h-.021a.274.274 0 0 1-.258-.231l-.256-1.319a.885.885 0 0 1 .465-.902l.186-.092c.117-.07.233-.162.35-.254l.418-.44a.85.85 0 0 1 .954-.139c.232.07.488.07.72 0a1.05 1.05 0 0 1 1.024.232l.349.347a1 1 0 0 0 .349.254");
}

.rcasxucso {
  stop-color: var(--svg-color--349fe1, #349FE1);
  stop-opacity: 0;
}

.ri7j818ay {
  stop-color: var(--svg-color--615150, #615150);
}

.ry-ekhh-j {
  width: 0.62px;
  height: 1.395px;
  x: 19.958px;
  y: 2.871px;
  fill: var(--svg-color--482f2c, #482F2C);
  rx: 0.31px;
}

.s070ztb0t {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M16.506 7.52c.028.036-.03.08-.095.13c-.065.049-.114.083-.141.046c-.028-.037.003-.106.068-.155c.066-.049.14-.058.168-.022");
}

.s3rc45b6k {
  stop-color: var(--svg-color--3197dd, #3197DD);
  stop-opacity: 0;
}

.s5iez-b2n {
  fill: var(--svg-color--ff9457, #FF9457);
  d: path("M18.577 10.89c-.23-.26-.686-.706-1.229-1.003h-.617l.316 1.39c.273-.042.976-.12 1.441-.172c.11-.013.162-.13.089-.214");
}

.sq2difwmt {
  cx: 14.526px;
  cy: 7.602px;
  rx: 0.169px;
  ry: 0.085px;
}

.su2ao5zll {
  d: path("m19.434 5.153l-.077 1.385a.1.1 0 0 0 .09.105l2.64.277a.3.3 0 0 0 .316-.391l-.464-1.42a.15.15 0 0 0-.14-.103l-2.161-.041a.2.2 0 0 0-.204.188");
}

.tcm98nmkx {
  stop-color: var(--svg-color--42aff6, #42AFF6);
  stop-opacity: 0;
}

.tp3-xrbff {
  stop-color: var(--svg-color--3197dd, #3197DD);
}

.tt8d0zipw {
  d: path("m17.309 5.501l-1.335.445a.454.454 0 0 0 .204.88l1.327-.177z");
}

.u2-6tpbfe {
  stop-color: var(--svg-color--d8cdf0, #D8CDF0);
}

.u8aws4lgo {
  stop-color: var(--svg-color--ff8337, #FF8337);
}

.uck_nmbag {
  stop-color: var(--svg-color--412628, #412628);
  stop-opacity: 0;
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.upgy9ybtr {
  d: path("M16.88 7.772a.36.36 0 0 0-.1-.2l-.113.124l.051.098z");
}

.upl8m_stv {
  stop-color: var(--svg-color--2c171f, #2C171F);
}

.vm6ce_jmk {
  d: path("M12.766 21.523c.217-.748.766-3.252 1.031-4.414l.422.18h4.684c-.816 2.398-2.664 3.657-4.004 5.875c-.409.677-.914 1.43-1.352 2.438c-.37.853-1.054 2.326-1.516 3.324a.574.574 0 0 1-.625.33c-1.533-.293-2.385-.943-3.014-1.765a.49.49 0 0 1-.012-.598c.72-.969 2.73-2.974 3.34-3.569c.675-.66.796-.937 1.046-1.8");
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vqp8gziqg {
  d: path("M18.399 29.863V27.46h1.727l1.64.844c.5.404 1.212.712 1.715.904a.445.445 0 0 1 .265.565a.44.44 0 0 1-.412.288h-2.652a.26.26 0 0 1-.224-.123l-.424-.678a.141.141 0 0 0-.26.075v.625a.1.1 0 0 1-.102.102h-1.073a.2.2 0 0 1-.2-.2");
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

.wbm6gtb2b {
  stop-color: var(--svg-color--3fb1fe, #3FB1FE);
}

.wcnk0lwkc {
  fill: var(--svg-color--000, #000);
  d: path("M16.314 7.824a.22.22 0 0 1 .222-.221a.22.22 0 0 1 .197.323h-.392a.2.2 0 0 1-.027-.102");
}

.wsr-x9y-q {
  stop-color: var(--svg-color--4195ec, #4195EC);
}

.wuv_a16vx {
  cx: 13.531px;
  cy: 7.94px;
  r: 0.431px;
}

.x3sd7rf5r {
  stop-color: var(--svg-color--362324, #362324);
}

.x6-zvqbsc {
  stop-color: var(--svg-color--d93d03, #D93D03);
  stop-opacity: 0;
}

.xhauz4b4f {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M13.954 6.76h.002l.002-.002l.005-.005l.067-.046q.065-.043.182-.091c.155-.062.378-.112.647-.07a.231.231 0 1 1-.072.458a.77.77 0 0 0-.512.095l-.023.016l-.004.003a.231.231 0 0 1-.294-.358");
}

.xtaxaigve {
  stop-color: var(--svg-color--624e4d, #624E4D);
  stop-opacity: 0;
}

.xtiplndwl {
  stop-color: var(--svg-color--3f222f, #3F222F);
}

.y3iq9j8og {
  stop-color: var(--svg-color--3779d3, #3779D3);
  stop-opacity: 0;
}

.y6eyh2aow {
  width: 0.62px;
  height: 1.395px;
  x: 20.578px;
  y: 2.871px;
  fill: var(--svg-color--482f2c, #482F2C);
  rx: 0.31px;
}

.y8kcl1bix {
  stop-color: var(--svg-color--48454b, #48454B);
  stop-opacity: 0;
}

.y91qr6bma {
  stop-color: var(--svg-color--523e3d, #523E3D);
}

.yautbgb0o {
  cx: 14.526px;
  cy: 7.602px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.169px;
  ry: 0.085px;
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yh2psxb-p {
  stop-color: var(--svg-color--4081dd, #4081DD);
}

.yk21hmsbp {
  stop-color: var(--svg-color--4f2b27, #4F2B27);
}

.yqnsa3b2w {
  d: path("m11.099 14.352l-2.586.139a.3.3 0 0 0-.252.434l.668 1.334a.15.15 0 0 0 .156.08l2.173-.318a.15.15 0 0 0 .128-.163l-.13-1.37a.15.15 0 0 0-.157-.136");
}

.ytssyfa7a {
  stop-color: var(--svg-color--40272a, #40272A);
}

.yww6tz8di {
  stop-color: var(--svg-color--624d4b, #624D4B);
}

.z5ewkjg-x {
  d: path("m14.25 9.83l-4.215 1.199a1.95 1.95 0 0 0-.937.595l1.958 1.623l-.001-.013l3.852-1.095z");
}

.zg7d64buy {
  fill: var(--svg-color--332024, #332024);
  d: path("m15.47 7.887l-.355.737c-.044.151.062.303.212.303h.32c.15 0 .255-.154.21-.303l-.215-.737c-.046-.163-.123-.163-.171 0");
}

.zkcw-qija {
  stop-color: var(--svg-color--2688ed, #2688ED);
  stop-opacity: 0;
}

.zmb-7ybbe {
  cx: 17.656px;
  cy: 7.94px;
  r: 0.431px;
}

.zxbkl_amt {
  width: 0.62px;
  height: 1.395px;
  x: 21.197px;
  y: 2.871px;
  fill: var(--svg-color--482f2c, #482F2C);
  rx: 0.31px;
}

</style>
