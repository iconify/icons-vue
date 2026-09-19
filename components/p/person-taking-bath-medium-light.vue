<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="em34d8-nz"/><path fill="url(#i0LZGIc)" class="rhskt_b-r"/><path fill="url(#iounIld)" class="rhskt_b-r"/><g filter="url(#i1Wp4gN)"><path fill="url(#iaTh8Ib)" class="ktvgo0bpt"/><path fill="url(#iW5p4BB)" class="ktvgo0bpt"/><path fill="url(#iAjXOte)" class="ktvgo0bpt"/><path fill="url(#i4CTiEb)" class="ktvgo0bpt"/></g><g filter="url(#isE04tb)"><path fill="url(#i5Qtdhn)" class="wqe3bt4-b"/><path fill="url(#ilIzwjd)" class="wqe3bt4-b"/><path fill="url(#iOQqirI)" class="wqe3bt4-b"/></g><path fill="url(#iiVj7Uo)" class="bnico_6vq"/><path fill="url(#iXYCC8d)" class="bnico_6vq"/><path fill="url(#ieLlOSc)" class="bnico_6vq"/><path clip-rule="evenodd" class="lv5qar2ad"/><g filter="url(#iZIXLdb)"><path clip-rule="evenodd" class="kr36wmbly"/></g><path class="xjjevr_na"/><path fill="url(#ipli86d)" class="g17isxbne"/><path fill="url(#iKBqonc)" class="ydzd-6xfl"/><ellipse fill="url(#ihScDWc)" transform="matrix(-.26548 .96412 .96417 .26529 8.65 11.325)" class="l--rvobkj"/><g filter="url(#iknxqxe)"><path fill="url(#is7xtUd)" class="z3-z59blv"/></g><g filter="url(#i7cyNLe)"><path fill="url(#iLq7KOi)" class="xpr216bbc"/><path fill="url(#ifZuVwc)" class="xpr216bbc"/></g><g filter="url(#i76ZrEb)"><path class="flppowlks"/><path fill="url(#ipjlowb)" class="guflbqm7f"/></g><g filter="url(#i3tV1bb)"><path class="meiw-xrht"/><path fill="url(#ilL39Oe)" class="cq6x-s4vk"/><path fill="url(#iyhf5mc)" class="cq6x-s4vk"/></g><g filter="url(#idtYZcd)"><circle fill="url(#i9E4ZGc)" class="b4p3l-beb"/><circle fill="url(#iRCaZZu)" class="b4p3l-beb"/></g><g filter="url(#iCKWpMO)"><path fill="url(#iZjMcVc)" clip-rule="evenodd" class="dxrk3h91i"/></g><rect fill="url(#i9HZAie)" transform="scale(-1 1)rotate(45 -41.293 -13.09)" class="hrxlqmt6c"/><rect fill="url(#iwL7NEd)" transform="scale(-1 1)rotate(45 -41.293 -13.09)" class="hrxlqmt6c"/><rect fill="url(#i0csxTc)" transform="scale(-1 1)rotate(45 -41.293 -13.09)" class="hrxlqmt6c"/><rect transform="rotate(45 11.795 25.365)" class="ix8u2obha"/><rect fill="url(#iAVHEsd)" transform="rotate(45 11.795 25.365)" class="m1i194eil"/><rect fill="url(#iT7JOxh)" transform="rotate(45 11.795 25.365)" class="m1i194eil"/><g filter="url(#iwZmf9d)"><path fill="url(#ifh64Ec)" class="m2bpawubo"/></g><path fill="url(#ioP1fre)" class="m2bpawubo"/><path fill="url(#iYGjCvb)" class="m2bpawubo"/><g filter="url(#izB5O4b)"><rect fill="url(#il4GwWc)" class="r8983pbtu"/><rect fill="url(#i7vpCdE)" class="r8983pbtu"/></g><rect fill="url(#iOAZnmc)" class="r8983pbtu"/><g filter="url(#iV2TS9c)"><path stroke="url(#iWxR8xM)" class="qxali02-e"/></g><g filter="url(#irYh9kc)"><path stroke="url(#iRQKGtc)" class="r5v5x5bvd"/></g><path fill="url(#inJyJFp)" class="h2po-_e3f"/><path fill="url(#i9UbvAd)" class="h2po-_e3f"/><defs><radialGradient id="i0LZGIc" cx="0" cy="0" r="1" gradientTransform="matrix(-.13677 .66665 -.94086 -.19303 10.537 10.95)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="rcpmccbyc"/><stop offset=".684" class="wdglv_bwm"/></radialGradient><radialGradient id="iounIld" cx="0" cy="0" r="1" gradientTransform="matrix(-.1835 -.35083 .52661 -.27544 10.515 11.595)" gradientUnits="userSpaceOnUse"><stop class="zkj259b3a"/><stop offset="1" class="iv0p50s_n"/></radialGradient><radialGradient id="iW5p4BB" cx="0" cy="0" r="1" gradientTransform="matrix(.63614 -.8497 1.03568 .77538 6.904 13.905)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pfu46_y1s"/><stop offset="1" class="ccv6f1brb"/></radialGradient><radialGradient id="iAjXOte" cx="0" cy="0" r="1" gradientTransform="matrix(-4.99011 -4.1872 1.62739 -1.93945 10.385 12.077)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="nkfrpdbdq"/><stop offset="1" class="eqwiy2pxg"/></radialGradient><radialGradient id="i4CTiEb" cx="0" cy="0" r="1" gradientTransform="rotate(40 -12.11 17.817)scale(.49052 .76519)" gradientUnits="userSpaceOnUse"><stop offset=".155" class="c-xbvquvy"/><stop offset="1" class="ksl77bchk"/></radialGradient><radialGradient id="i5Qtdhn" cx="0" cy="0" r="1" gradientTransform="rotate(168.976 2.74 6.482)scale(3.88884 5.91142)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="te4zz7dbn"/><stop offset="1" class="otf1z2b9l"/></radialGradient><radialGradient id="ilIzwjd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.81093 .4488 -.72197 -2.9132 7.042 8.918)" gradientUnits="userSpaceOnUse"><stop class="r-95cxbic"/><stop offset="1" class="efo8wovhu"/></radialGradient><radialGradient id="iOQqirI" cx="0" cy="0" r="1" gradientTransform="matrix(.5654 -.38384 .18855 .27774 6.356 16.267)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="cl2mrcsll"/><stop offset="1" class="hms2sfnpk"/></radialGradient><radialGradient id="iiVj7Uo" cx="0" cy="0" r="1" gradientTransform="matrix(-.78953 .52884 -.25806 -.38527 6.973 13.595)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="gneqelmmi"/><stop offset="1" class="enl5oqy9k"/></radialGradient><radialGradient id="iXYCC8d" cx="0" cy="0" r="1" gradientTransform="matrix(.9524 1.16968 -1.21917 .9927 6.658 13.382)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="rdgulqvms"/><stop offset="1" class="vmk6x9_kg"/></radialGradient><radialGradient id="ipli86d" cx="0" cy="0" r="1" gradientTransform="matrix(-.22077 .2631 -.51104 -.4288 8.884 11.691)" gradientUnits="userSpaceOnUse"><stop offset=".895" class="l0aricxam"/><stop offset="1" class="n9r91ylyy"/></radialGradient><radialGradient id="iKBqonc" cx="0" cy="0" r="1" gradientTransform="matrix(-.20185 .24055 -.52043 -.4367 9.04 11.546)" gradientUnits="userSpaceOnUse"><stop class="gv3iwdbvq"/><stop offset=".813" class="ubyl24bdb"/></radialGradient><radialGradient id="iLq7KOi" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.09375 .5802 0 20.815 15.15)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="i4zotxb2l"/><stop offset="1" class="h26j_7pvv"/></radialGradient><radialGradient id="ifZuVwc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.49998 -3.09376 1.67378 -.81152 23.534 14.713)" gradientUnits="userSpaceOnUse"><stop class="yltphm5hh"/><stop offset="1" class="d5hu6_bok"/></radialGradient><radialGradient id="ipjlowb" cx="0" cy="0" r="1" gradientTransform="rotate(-45.372 16.76 -19.212)scale(6.80605 3.84932)" gradientUnits="userSpaceOnUse"><stop class="xy0op_eyz"/><stop offset="1" class="p53pr-blg"/></radialGradient><radialGradient id="ilL39Oe" cx="0" cy="0" r="1" gradientTransform="rotate(-150.994 14.706 4.711)scale(3.60894 4.34333)" gradientUnits="userSpaceOnUse"><stop class="v7qdu5boj"/><stop offset="1" class="kdd3vfboh"/></radialGradient><radialGradient id="iyhf5mc" cx="0" cy="0" r="1" gradientTransform="matrix(1.0625 2.625 -1.48498 .60106 19.503 13.838)" gradientUnits="userSpaceOnUse"><stop class="xwt5g5sto"/><stop offset="1" class="x484pmbxx"/></radialGradient><radialGradient id="i9E4ZGc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.90038 -2.5625 2.1013 -1.55835 20.764 15.874)" gradientUnits="userSpaceOnUse"><stop class="nmlj7qb8u"/><stop offset="1" class="wijlc3r_o"/></radialGradient><radialGradient id="iRCaZZu" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 -2.34375 2.00586 1.12328 16.858 16.405)" gradientUnits="userSpaceOnUse"><stop class="n35yqc9wi"/><stop offset="1" class="e9nymn0gr"/></radialGradient><radialGradient id="iZjMcVc" cx="0" cy="0" r="1" gradientTransform="rotate(-138.668 11.437 4.375)scale(4.20282 3.66642)" gradientUnits="userSpaceOnUse"><stop class="fgfvt8_za"/><stop offset="1" class="kb1q69u9p"/></radialGradient><radialGradient id="iwL7NEd" cx="0" cy="0" r="1" gradientTransform="rotate(79.16 -.565 1.44)scale(1.58615 1.72717)" gradientUnits="userSpaceOnUse"><stop class="lkqdv0bwp"/><stop offset="1" class="vou8iltko"/></radialGradient><radialGradient id="i0csxTc" cx="0" cy="0" r="1" gradientTransform="rotate(-89.442 2.4 1.929)scale(1.40065 .72809)" gradientUnits="userSpaceOnUse"><stop class="go679fbfb"/><stop offset="1" class="jo92-ub-i"/></radialGradient><radialGradient id="iT7JOxh" cx="0" cy="0" r="1" gradientTransform="rotate(-47.663 40.384 1.484)scale(.6726 1.0441)" gradientUnits="userSpaceOnUse"><stop class="brjpzuruh"/><stop offset="1" class="ea_rhjb1f"/></radialGradient><radialGradient id="ifh64Ec" cx="0" cy="0" r="1" gradientTransform="matrix(-15.56247 -.06247 .03888 -9.68481 26.003 22.307)" gradientUnits="userSpaceOnUse"><stop class="vn7ncpb8d"/><stop offset="1" class="htcu-gvqd"/></radialGradient><radialGradient id="ioP1fre" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.625 -39.1562 0 17.128 19.37)" gradientUnits="userSpaceOnUse"><stop offset=".572" class="mh1kw6b0u"/><stop offset="1" class="mg_zulb9j"/></radialGradient><radialGradient id="il4GwWc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.25 -15.4957 0 25.253 16.65)" gradientUnits="userSpaceOnUse"><stop class="ypx_bsb1m"/><stop offset="1" class="o3pqq4zbd"/></radialGradient><radialGradient id="iWxR8xM" cx="0" cy="0" r="1" gradientTransform="matrix(-6.71874 10.18756 -7.15636 -4.71965 28.784 3.62)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="yi5996bix"/><stop offset="1" class="p_197nrym"/></radialGradient><radialGradient id="iRQKGtc" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 -3.53125 2.69792 1.14602 19.551 6.572)" gradientUnits="userSpaceOnUse"><stop offset=".008" class="yi5996bix"/><stop offset="1" class="p_197nrym"/></radialGradient><radialGradient id="inJyJFp" cx="0" cy="0" r="1" gradientTransform="matrix(-4.53418 0 0 -3.55867 20.659 8.611)" gradientUnits="userSpaceOnUse"><stop offset=".145" class="yi5996bix"/><stop offset=".717" class="wvcdyrpfm"/></radialGradient><filter id="i1Wp4gN" width="7.788" height="6.596" x="3.97" y="9.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2" dy="-.2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.654902 0 0 0 0 0.560784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24059"/></filter><filter id="isE04tb" width="5.591" height="8.62" x="2.451" y="8.369" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.901961 0 0 0 0 0.682353 0 0 0 0 0.505882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24059"/></filter><filter id="iZIXLdb" width=".814" height="1.199" x="7.127" y="10.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.270588 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24059"/></filter><filter id="iknxqxe" width="3.831" height="3.045" x="2.723" y="12.115" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24059" stdDeviation=".25"/></filter><filter id="i7cyNLe" width="7.367" height="4.959" x="17.424" y="12.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".1"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.768627 0 0 0 0 0.6 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24059"/></filter><filter id="i76ZrEb" width="9.125" height="15.5" x="17.94" y="1.619" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.501961 0 0 0 0 0.498039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24059"/></filter><filter id="i3tV1bb" width="14.805" height="6.438" x="11.19" y="12.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.678431 0 0 0 0 0.74902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24059"/></filter><filter id="idtYZcd" width="5.582" height="5.582" x="16.073" y="13.94" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24059" stdDeviation=".25"/></filter><filter id="iCKWpMO" width="6.341" height="6.485" x="11.299" y="12.793" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24059" stdDeviation=".25"/></filter><filter id="iwZmf9d" width="28.578" height="11" x="3.784" y="16.807" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="3" dy="-1"/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.678431 0 0 0 0 0.654902 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24059"/></filter><filter id="izB5O4b" width="28.344" height="2.496" x="2.674" y="15.658" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.698039 0 0 0 0 0.705882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24059"/></filter><filter id="iV2TS9c" width="5.047" height="14.518" x="21.799" y="1.789" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24059" stdDeviation=".25"/></filter><filter id="irYh9kc" width="2.999" height="4.468" x="17.989" y="2.604" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24059" stdDeviation=".25"/></filter><linearGradient id="iaTh8Ib" x1="7.87" x2="10.347" y1="14.204" y2="11.588" gradientUnits="userSpaceOnUse"><stop class="w6b0chbuk"/><stop offset="1" class="n3dqqoxxk"/></linearGradient><linearGradient id="ieLlOSc" x1="7.083" x2="6.974" y1="13.598" y2="13.75" gradientUnits="userSpaceOnUse"><stop class="qdq-erb7u"/><stop offset="1" class="yfv3nqb2s"/></linearGradient><linearGradient id="ihScDWc" x1="-.009" x2=".225" y1=".062" y2=".139" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="is7xtUd" x1="5.599" x2="2.452" y1="14.451" y2="12.538" gradientUnits="userSpaceOnUse"><stop offset=".421" class="esqjgpxir"/><stop offset="1" class="lj6qdgbam"/></linearGradient><linearGradient id="i9HZAie" x1="1.641" x2="-.116" y1="2.961" y2="3.171" gradientUnits="userSpaceOnUse"><stop class="t7wbu9b2k"/><stop offset="1" class="t9935ox4b"/></linearGradient><linearGradient id="iAVHEsd" x1="11.481" x2="13.028" y1="28.867" y2="28.624" gradientUnits="userSpaceOnUse"><stop class="gbuoa-pfp"/><stop offset="1" class="h8mgf7b3a"/></linearGradient><linearGradient id="iYGjCvb" x1="16.573" x2="16.573" y1="17.807" y2="19.213" gradientUnits="userSpaceOnUse"><stop class="nihdd8-bi"/><stop offset="1" class="x6h_eubpf"/></linearGradient><linearGradient id="i7vpCdE" x1="2.878" x2="12.128" y1="17.244" y2="17.244" gradientUnits="userSpaceOnUse"><stop class="d673tl90q"/><stop offset="1" class="f-q8xrbdi"/></linearGradient><linearGradient id="iOAZnmc" x1="17.94" x2="17.94" y1="18.154" y2="17.619" gradientUnits="userSpaceOnUse"><stop class="b0b_4h8fx"/><stop offset="1" class="vngbibvro"/></linearGradient><linearGradient id="i9UbvAd" x1="19.424" x2="19.424" y1="8.611" y2="8.104" gradientUnits="userSpaceOnUse"><stop class="dcrtohb5r"/><stop offset="1" class="k3-gog70w"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-taking-bath-medium-light" /></template>
<style>
.b0b_4h8fx {
  stop-color: var(--svg-color--b1a1c2, #B1A1C2);
}

.b4p3l-beb {
  cx: 18.864px;
  cy: 16.73px;
  r: 2.291px;
}

.bnico_6vq {
  d: path("m7.935 14.154l-1.546-.97a.913.913 0 0 0 1.546.97");
}

.brjpzuruh {
  stop-color: var(--svg-color--88828e, #88828E);
}

.c-xbvquvy {
  stop-color: var(--svg-color--e6aa86, #E6AA86);
}

.ccv6f1brb {
  stop-color: var(--svg-color--dd9c79, #DD9C79);
  stop-opacity: 0;
}

.cl2mrcsll {
  stop-color: var(--svg-color--ffdda9, #FFDDA9);
}

.cq6x-s4vk {
  d: path("M14.409 19.432a3.22 3.22 0 0 0 2.705-1.475a2.5 2.5 0 0 0 1.658.615c.66 0 1.256-.245 1.687-.64c.51.615 1.401 1.023 2.415 1.023c1.585 0 2.87-.998 2.87-2.23c0-1.051-1.285-2.23-2.87-2.23c-.79 0-1.505.247-2.023.647a.107.107 0 0 1-.15-.019c-.432-.546-1.135-.902-1.929-.902c-.531 0-1.021.159-1.417.428a.107.107 0 0 1-.152-.035a3.219 3.219 0 1 0-2.794 4.818");
}

.d5hu6_bok {
  stop-color: var(--svg-color--e1bca1, #E1BCA1);
  stop-opacity: 0;
}

.d673tl90q {
  stop-color: var(--svg-color--bcb9bf, #BCB9BF);
}

.dcrtohb5r {
  stop-color: var(--svg-color--807f86, #807F86);
}

.dxrk3h91i {
  fill-rule: evenodd;
  d: path("M17.14 15.157a2.32 2.32 0 0 0-.631 2.789a2.742 2.742 0 1 1 .631-2.789");
}

.e9nymn0gr {
  stop-color: var(--svg-color--3dc6eb, #3DC6EB);
  stop-opacity: 0;
}

.ea_rhjb1f {
  stop-color: var(--svg-color--88828e, #88828E);
  stop-opacity: 0;
}

.efo8wovhu {
  stop-color: var(--svg-color--ffeeb8, #FFEEB8);
  stop-opacity: 0;
}

.em34d8-nz {
  fill: var(--svg-color--b58272, #B58272);
  d: path("m8.314 15.657l1.422-1.034l1.332 1.832l-1.422 1.034z");
}

.enl5oqy9k {
  stop-color: var(--svg-color--e1a587, #E1A587);
}

.eqwiy2pxg {
  stop-color: var(--svg-color--fbbca1, #FBBCA1);
  stop-opacity: 0;
}

.esqjgpxir {
  stop-color: var(--svg-color--fff9bd, #FFF9BD);
}

.f-q8xrbdi {
  stop-color: var(--svg-color--bcb9bf, #BCB9BF);
  stop-opacity: 0;
}

.fgfvt8_za {
  stop-color: var(--svg-color--6bf3ff, #6BF3FF);
}

.flppowlks {
  fill: var(--svg-color--adadad, #ADADAD);
  d: path("M24.965 6.182v10.937h1.6V6.182a4.313 4.313 0 0 0-8.625 0v1.03h1.6v-1.03a2.712 2.712 0 1 1 5.425 0");
}

.ft5dv1b6b {
  fill: none;
}

.g17isxbne {
  d: path("m8.64 12.024l-.004-.003c-.308-.259-.447-.6-.31-.763c.136-.163.497-.086.805.173l.004.003z");
}

.gbuoa-pfp {
  stop-color: var(--svg-color--807d83, #807D83);
}

.gneqelmmi {
  stop-color: var(--svg-color--ebb497, #EBB497);
}

.go679fbfb {
  stop-color: var(--svg-color--bebac2, #BEBAC2);
}

.guflbqm7f {
  d: path("M24.965 6.182v10.937h1.6V6.182a4.313 4.313 0 0 0-8.625 0v1.03h1.6v-1.03a2.712 2.712 0 1 1 5.425 0");
}

.gv3iwdbvq {
  stop-color: var(--svg-color--666361, #666361);
}

.h26j_7pvv {
  stop-color: var(--svg-color--d3a88b, #D3A88B);
}

.h2po-_e3f {
  d: path("M21.104 8.611c.28 0 .509-.23.457-.504c-.25-1.307-1.37-2.293-2.715-2.293s-2.465.986-2.714 2.293c-.052.274.177.504.456.504z");
}

.h8mgf7b3a {
  stop-color: var(--svg-color--807d83, #807D83);
  stop-opacity: 0;
}

.hms2sfnpk {
  stop-color: var(--svg-color--ffdda9, #FFDDA9);
  stop-opacity: 0;
}

.hrxlqmt6c {
  width: 1.608px;
  height: 5.132px;
  rx: 0.804px;
}

.htcu-gvqd {
  stop-color: var(--svg-color--c7bdd3, #C7BDD3);
}

.i4zotxb2l {
  stop-color: var(--svg-color--c79b8d, #C79B8D);
}

.iv0p50s_n {
  stop-color: var(--svg-color--f0aa89, #F0AA89);
  stop-opacity: 0;
}

.ix8u2obha {
  width: 1.608px;
  height: 5.132px;
  x: 11.795px;
  y: 25.365px;
  fill: var(--svg-color--735f86, #735F86);
  rx: 0.804px;
}

.jo92-ub-i {
  stop-color: var(--svg-color--968da0, #968DA0);
  stop-opacity: 0;
}

.k3-gog70w {
  stop-color: var(--svg-color--8f9198, #8F9198);
  stop-opacity: 0;
}

.kb1q69u9p {
  stop-color: var(--svg-color--6bf3ff, #6BF3FF);
  stop-opacity: 0;
}

.kdd3vfboh {
  stop-color: var(--svg-color--66ebff, #66EBFF);
  stop-opacity: 0;
}

.kr36wmbly {
  fill: var(--svg-color--915d37, #915D37);
  fill-rule: evenodd;
  d: path("M7.72 11.102a1 1 0 0 1 .16-.222a.188.188 0 0 0-.255-.276a1.3 1.3 0 0 0-.235.317c-.078.143-.15.328-.163.532a.188.188 0 1 0 .376.023a.9.9 0 0 1 .118-.375");
}

.ksl77bchk {
  stop-color: var(--svg-color--e6aa86, #E6AA86);
  stop-opacity: 0;
}

.ktvgo0bpt {
  d: path("M8.773 10.314c-.801-.61-1.382-.672-1.59-.645l-3.013 3.59l2.993 2.614c2.74.88 4.963-1.592 4.544-2.592s-2.005-2.261-2.934-2.967");
}

.l--rvobkj {
  rx: 0.081px;
  ry: 0.11px;
}

.l0aricxam {
  stop-color: var(--svg-color--916a62, #916A62);
}

.lj6qdgbam {
  stop-color: var(--svg-color--fff9bd, #FFF9BD);
  stop-opacity: 0;
}

.lkqdv0bwp {
  stop-color: var(--svg-color--7a6a8b, #7A6A8B);
}

.lv5qar2ad {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M9.598 13.058c.008.086.085.15.171.141c.417-.04.753-.323.852-.42a.157.157 0 1 0-.219-.225c-.084.082-.355.303-.663.333a.157.157 0 0 0-.141.171");
}

.m1i194eil {
  width: 1.608px;
  height: 5.132px;
  x: 11.795px;
  y: 25.365px;
  rx: 0.804px;
}

.m2bpawubo {
  d: path("m5.24 22.376l-1.456-4.57h25.578l-1.477 4.59a7.8 7.8 0 0 1-7.425 5.41h-7.788a7.8 7.8 0 0 1-7.432-5.43");
}

.meiw-xrht {
  fill: var(--svg-color--4bd1f1, #4BD1F1);
  d: path("M14.409 19.432a3.22 3.22 0 0 0 2.705-1.475a2.5 2.5 0 0 0 1.658.615c.66 0 1.256-.245 1.687-.64c.51.615 1.401 1.023 2.415 1.023c1.585 0 2.87-.998 2.87-2.23c0-1.051-1.285-2.23-2.87-2.23c-.79 0-1.505.247-2.023.647a.107.107 0 0 1-.15-.019c-.432-.546-1.135-.902-1.929-.902c-.531 0-1.021.159-1.417.428a.107.107 0 0 1-.152-.035a3.219 3.219 0 1 0-2.794 4.818");
}

.mg_zulb9j {
  stop-color: var(--svg-color--a887c7, #A887C7);
}

.mh1kw6b0u {
  stop-color: var(--svg-color--bba9cd, #BBA9CD);
  stop-opacity: 0;
}

.n35yqc9wi {
  stop-color: var(--svg-color--3dc6eb, #3DC6EB);
}

.n3dqqoxxk {
  stop-color: var(--svg-color--f2b592, #F2B592);
}

.n9r91ylyy {
  stop-color: var(--svg-color--824d44, #824D44);
}

.nihdd8-bi {
  stop-color: var(--svg-color--a090b0, #A090B0);
}

.nkfrpdbdq {
  stop-color: var(--svg-color--fbbca1, #FBBCA1);
}

.nmlj7qb8u {
  stop-color: var(--svg-color--6ef3ff, #6EF3FF);
}

.o3pqq4zbd {
  stop-color: var(--svg-color--d5d3d8, #D5D3D8);
}

.otf1z2b9l {
  stop-color: var(--svg-color--ffedae, #FFEDAE);
}

.p_197nrym {
  stop-color: var(--svg-color--c1c1c2, #C1C1C2);
  stop-opacity: 0;
}

.p53pr-blg {
  stop-color: var(--svg-color--a09fa0, #A09FA0);
  stop-opacity: 0;
}

.pfu46_y1s {
  stop-color: var(--svg-color--dd9c79, #DD9C79);
}

.qdq-erb7u {
  stop-color: var(--svg-color--e5a88d, #E5A88D);
}

.qxali02-e {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M22.315 2.666c1.219-.052 3.656.94 3.656 3.766v9.375");
}

.r-95cxbic {
  stop-color: var(--svg-color--ffeeb8, #FFEEB8);
}

.r5v5x5bvd {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M20.239 3.385c-.458.406-1.375 1.612-1.375 3.187");
}

.r8983pbtu {
  width: 27.844px;
  height: 2.246px;
  x: 2.674px;
  y: 15.908px;
  rx: 1.123px;
}

.rcpmccbyc {
  stop-color: var(--svg-color--fec19d, #FEC19D);
}

.rdgulqvms {
  stop-color: var(--svg-color--e1a38b, #E1A38B);
  stop-opacity: 0;
}

.rhskt_b-r {
  d: path("M9.881 10.876a1.26 1.26 0 0 1-.648-.12l-.145.172l1.082.908c.305-.096.533-.409.41-.662c-.107-.217-.365-.337-.699-.298");
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t7wbu9b2k {
  stop-color: var(--svg-color--887a96, #887A96);
}

.t9935ox4b {
  stop-color: var(--svg-color--a9a6ac, #A9A6AC);
}

.te4zz7dbn {
  stop-color: var(--svg-color--ffe2ad, #FFE2AD);
}

.ubyl24bdb {
  stop-color: var(--svg-color--565352, #565352);
}

.v7qdu5boj {
  stop-color: var(--svg-color--66ebff, #66EBFF);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vmk6x9_kg {
  stop-color: var(--svg-color--dd9a7e, #DD9A7E);
}

.vn7ncpb8d {
  stop-color: var(--svg-color--e1daea, #E1DAEA);
}

.vngbibvro {
  stop-color: var(--svg-color--bbb2c3, #BBB2C3);
  stop-opacity: 0;
}

.vou8iltko {
  stop-color: var(--svg-color--7a6a8b, #7A6A8B);
  stop-opacity: 0;
}

.w6b0chbuk {
  stop-color: var(--svg-color--dfa289, #DFA289);
}

.wdglv_bwm {
  stop-color: var(--svg-color--f2b08a, #F2B08A);
}

.wijlc3r_o {
  stop-color: var(--svg-color--6ef3ff, #6EF3FF);
  stop-opacity: 0;
}

.wqe3bt4-b {
  d: path("M6.388 8.56a1.29 1.29 0 0 0-1.35.48c-.65.865-.458 1.218-1.24 1.837c-.826.653-1.106 1.083-1.236 1.55l-.003.009c-.128.46-.394 1.413 1.017 2.597c1.3 1.09 2.376 1.203 2.81 1.185l-.022.057c-.106.29.054.581.344.688c.248.09.56-.058.766-.402c.236-.392.402-.686.53-.919a.31.31 0 0 0-.074-.389l-1.07-.898c-.451-.378-.453-.922-.416-1.13c-.453-.406-.548-.729-.465-1.056c.137-.543.33-.585 1.048-1.555c.723-.975.187-1.848-.639-2.054");
}

.wvcdyrpfm {
  stop-color: var(--svg-color--929192, #929192);
}

.x484pmbxx {
  stop-color: var(--svg-color--6af0ff, #6AF0FF);
  stop-opacity: 0;
}

.x6h_eubpf {
  stop-color: var(--svg-color--bcb0c8, #BCB0C8);
  stop-opacity: 0;
}

.xjjevr_na {
  fill: var(--svg-color--fff, #fff);
  d: path("m9.128 11.442l-.798.951c-.377-.316-.503-.785-.283-1.048c.22-.262.704-.219 1.08.097");
}

.xpr216bbc {
  d: path("M18.514 13.578a2.288 2.288 0 0 1 4.216-.309l1.812 3.6h-7.118z");
}

.xwt5g5sto {
  stop-color: var(--svg-color--6af0ff, #6AF0FF);
}

.xy0op_eyz {
  stop-color: var(--svg-color--a09fa0, #A09FA0);
}

.ydzd-6xfl {
  d: path("M8.797 11.836a1 1 0 0 1-.073-.054c-.178-.15-.26-.347-.18-.44c.078-.094.286-.048.464.102q.036.03.067.062z");
}

.yfv3nqb2s {
  stop-color: var(--svg-color--e4a88b, #E4A88B);
  stop-opacity: 0;
}

.yi5996bix {
  stop-color: var(--svg-color--c1c1c2, #C1C1C2);
}

.yltphm5hh {
  stop-color: var(--svg-color--e1bca1, #E1BCA1);
}

.ypx_bsb1m {
  stop-color: var(--svg-color--fefcff, #FEFCFF);
}

.z3-z59blv {
  d: path("M4.814 13.134a16 16 0 0 0 1.239 1.494a3.64 3.64 0 0 1-2.55-.617c-.52-.354-.264-1.165.335-1.357c.432-.14.707.114.976.48");
}

.zkj259b3a {
  stop-color: var(--svg-color--f0aa89, #F0AA89);
}

</style>
