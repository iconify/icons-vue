<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i6Xbpnc)"><path class="kjkcnpftl"/><path fill="url(#iue6npJ)" class="j1z7pbbbo"/><path fill="url(#iOYmnmd)" class="j1z7pbbbo"/><path fill="url(#iJbgRUp)" class="j1z7pbbbo"/></g><path fill="url(#iKaMRtR)" class="dghiu33oz"/><path fill="url(#iYsndle)" class="dghiu33oz"/><path fill="url(#iADzhFd)" class="dghiu33oz"/><g filter="url(#iaEdLIS)"><rect transform="rotate(-22.578 4.94 8.864)" class="y2p0ho9os"/></g><path fill="url(#iTCE3dy)" class="h0rtv8bes"/><path fill="url(#iZTcZDf)" class="h0rtv8bes"/><path fill="url(#i6mwYye)" class="h0rtv8bes"/><path fill="url(#iKEmHXU)" class="h0rtv8bes"/><path fill="url(#igwQBmc)" class="h0rtv8bes"/><g filter="url(#iC2hZZn)"><rect transform="rotate(-19.107 9.287 5.616)" class="bx1qcr8op"/></g><path fill="url(#iBg347c)" class="pf1lpbc4v"/><path fill="url(#iiYXkva)" class="pf1lpbc4v"/><path fill="url(#iPGS4Dd)" class="pf1lpbc4v"/><path fill="url(#iFGQq8w)" class="pf1lpbc4v"/><path fill="url(#iep4d6b)" class="pf1lpbc4v"/><g filter="url(#iHq7BNL)"><rect fill="url(#ixjcX4b)" transform="rotate(16.763 19.015 3.608)" class="ce-rjlvov"/></g><path fill="url(#iMKbKAd)" class="h802rfb4i"/><path fill="url(#iKxOCPd)" class="h802rfb4i"/><path fill="url(#ikp8h3d)" class="h802rfb4i"/><path fill="url(#iFNC95c)" class="h802rfb4i"/><g filter="url(#ilhWFFb)"><rect fill="url(#iWMhpDe)" transform="rotate(20.79 23.286 5.7)" class="ewfnf5ijd"/></g><g filter="url(#iHDIbWd)"><path stroke="url(#i5aPyTc)" class="uxy3yk0bv"/></g><path fill="url(#iulH0nc)" class="hq26renpk"/><path fill="url(#idkL93d)" class="hq26renpk"/><g filter="url(#iIvidre)"><path stroke="url(#iFBLvOc)" class="jrmxsr73p"/></g><g filter="url(#i879TMP)"><path stroke="url(#izoHWPd)" class="rzgkgdcgx"/></g><g filter="url(#iqHFTrb)"><path stroke="url(#iKcAD0b)" class="bt-o6mb1h"/></g><g filter="url(#iIh84ZK)"><path stroke="url(#ilbwEec)" class="yhx-yvbws"/></g><g filter="url(#iE6jndA)"><path stroke="url(#iRBwqpI)" class="jsmhdtb5y"/></g><path fill="url(#iILzjIc)" class="xn-pf7auk"/><path fill="url(#iK0nWJe)" class="xn-pf7auk"/><path fill="url(#iJdF2QF)" class="xn-pf7auk"/><path fill="url(#isilBQa)" class="xn-pf7auk"/><path fill="url(#i9Lvxkc)" class="xn-pf7auk"/><path fill="url(#i60aIyb)" class="xn-pf7auk"/><path fill="url(#ioPTZsE)" class="xn-pf7auk"/><defs><linearGradient id="iKaMRtR" x1="9.166" x2="7.619" y1="11.757" y2="12.302" gradientUnits="userSpaceOnUse"><stop class="swab9xvjw"/><stop offset="1" class="ktrxt1b5o"/></linearGradient><linearGradient id="iYsndle" x1="9.892" x2="8.544" y1="14.372" y2="13.093" gradientUnits="userSpaceOnUse"><stop class="lyot_fbwv"/><stop offset="1" class="d95nnob8o"/></linearGradient><linearGradient id="iTCE3dy" x1="8.064" x2="10.544" y1="11.602" y2="10.686" gradientUnits="userSpaceOnUse"><stop class="da3thxvdw"/><stop offset="1" class="i8lby6hve"/></linearGradient><linearGradient id="i6mwYye" x1="13.712" x2="11.17" y1="8.926" y2="9.688" gradientUnits="userSpaceOnUse"><stop class="eqg3zbc2t"/><stop offset="1" class="mrx-mta2y"/><stop offset="1" class="pkoe_9n2o"/></linearGradient><linearGradient id="iKEmHXU" x1="12.274" x2="11.931" y1="14.551" y2="13.457" gradientUnits="userSpaceOnUse"><stop class="lyot_fbwv"/><stop offset="1" class="d95nnob8o"/></linearGradient><linearGradient id="iBg347c" x1="14.068" x2="16.62" y1="8.252" y2="9.033" gradientUnits="userSpaceOnUse"><stop class="u8k763igq"/><stop offset="1" class="e6b-jdq7u"/></linearGradient><linearGradient id="iiYXkva" x1="19.704" x2="18.459" y1="10.385" y2="9.97" gradientUnits="userSpaceOnUse"><stop class="ef2hcibro"/><stop offset="1" class="rfpayfbmn"/></linearGradient><linearGradient id="iPGS4Dd" x1="19.332" x2="18.93" y1="10.419" y2="10.291" gradientUnits="userSpaceOnUse"><stop class="sosxdhbyi"/><stop offset="1" class="c11ad9byq"/></linearGradient><linearGradient id="iFGQq8w" x1="17.431" x2="15.63" y1="15.04" y2="11.571" gradientUnits="userSpaceOnUse"><stop class="eikks2bvz"/><stop offset="1" class="lde1lbc4x"/></linearGradient><linearGradient id="ixjcX4b" x1="20.429" x2="20.36" y1="4.796" y2="15.422" gradientUnits="userSpaceOnUse"><stop class="okcr8bcgn"/><stop offset="1" class="j1_0hmb-z"/></linearGradient><linearGradient id="iMKbKAd" x1="18.612" x2="21.713" y1="10.502" y2="11.497" gradientUnits="userSpaceOnUse"><stop class="satevfbvr"/><stop offset="1" class="qukmd6-ht"/></linearGradient><linearGradient id="iKxOCPd" x1="19.69" x2="20.631" y1="15.903" y2="14.009" gradientUnits="userSpaceOnUse"><stop class="ivymufunm"/><stop offset="1" class="by1xrq2gn"/></linearGradient><linearGradient id="iWMhpDe" x1="24.79" x2="24.725" y1="6.887" y2="17.514" gradientUnits="userSpaceOnUse"><stop class="n7ki7rm8i"/><stop offset="1" class="h3-kpdg0w"/></linearGradient><linearGradient id="i5aPyTc" x1="21.103" x2="20.345" y1="17.027" y2="16.5" gradientUnits="userSpaceOnUse"><stop class="w12xup1lx"/><stop offset="1" class="jt1f-bcod"/></linearGradient><linearGradient id="iFBLvOc" x1="27.214" x2="23.115" y1="14.779" y2="19.925" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="izoHWPd" x1="10.007" x2="8.388" y1="17.478" y2="18.002" gradientUnits="userSpaceOnUse"><stop class="lk7dbcc7r"/><stop offset="1" class="tmqbcuz_q"/></linearGradient><linearGradient id="iKcAD0b" x1="13" x2="11.754" y1="14.95" y2="14.9" gradientUnits="userSpaceOnUse"><stop class="lk7dbcc7r"/><stop offset="1" class="tmqbcuz_q"/></linearGradient><linearGradient id="ilbwEec" x1="17.827" x2="16.575" y1="14.996" y2="16.081" gradientUnits="userSpaceOnUse"><stop class="lk7dbcc7r"/><stop offset="1" class="tmqbcuz_q"/></linearGradient><linearGradient id="iRBwqpI" x1="21.604" x2="20.351" y1="17.221" y2="18.307" gradientUnits="userSpaceOnUse"><stop class="lk7dbcc7r"/><stop offset="1" class="tmqbcuz_q"/></linearGradient><radialGradient id="iue6npJ" cx="0" cy="0" r="1" gradientTransform="matrix(5.57964 -3.27694 6.45506 10.99104 7.087 26.821)" gradientUnits="userSpaceOnUse"><stop class="kava7d4sq"/><stop offset="1" class="ks214lbap"/></radialGradient><radialGradient id="iOYmnmd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.50706 8.21304 -8.36063 -3.57008 22.5 25.22)" gradientUnits="userSpaceOnUse"><stop class="btsp6rbtk"/><stop offset="1" class="vv0xjz_lx"/></radialGradient><radialGradient id="iJbgRUp" cx="0" cy="0" r="1" gradientTransform="rotate(129.756 10.244 17.636)scale(9.70275 6.73697)" gradientUnits="userSpaceOnUse"><stop class="i3rbzskiq"/><stop offset="1" class="qtnyoe6zz"/><stop offset="1" class="l9pur1csk"/></radialGradient><radialGradient id="iADzhFd" cx="0" cy="0" r="1" gradientTransform="rotate(68.515 -2.993 7.072)scale(2.99536 5.57619)" gradientUnits="userSpaceOnUse"><stop class="da29j-lzx"/><stop offset="1" class="vfztw_b5g"/></radialGradient><radialGradient id="iZTcZDf" cx="0" cy="0" r="1" gradientTransform="matrix(.41951 -.13185 1.49361 4.7524 8.706 12.211)" gradientUnits="userSpaceOnUse"><stop class="bma3owbau"/><stop offset="1" class="i6onak34h"/></radialGradient><radialGradient id="igwQBmc" cx="0" cy="0" r="1" gradientTransform="matrix(.8227 2.71004 -3.53608 1.07347 8.78 4.054)" gradientUnits="userSpaceOnUse"><stop class="gxifl7u3b"/><stop offset="1" class="hbzhtubqt"/></radialGradient><radialGradient id="iep4d6b" cx="0" cy="0" r="1" gradientTransform="rotate(103.309 9.004 8.45)scale(3.79934 4.20751)" gradientUnits="userSpaceOnUse"><stop class="l910ugb3j"/><stop offset="1" class="pv5xzqh5q"/></radialGradient><radialGradient id="ikp8h3d" cx="0" cy="0" r="1" gradientTransform="rotate(-160.567 12.535 6.14)scale(.74532 1.9169)" gradientUnits="userSpaceOnUse"><stop class="y1ea_7b_c"/><stop offset="1" class="gntgsyb6u"/></radialGradient><radialGradient id="iFNC95c" cx="0" cy="0" r="1" gradientTransform="rotate(101.271 10.156 11.506)scale(3.74953 4.50938)" gradientUnits="userSpaceOnUse"><stop class="huzidx7ok"/><stop offset="1" class="hz3-s9nlv"/></radialGradient><radialGradient id="iulH0nc" cx="0" cy="0" r="1" gradientTransform="matrix(1.29719 1.10259 -3.33471 3.92326 24.014 13.654)" gradientUnits="userSpaceOnUse"><stop class="f6og14bdq"/><stop offset="1" class="sso9s_bho"/></radialGradient><radialGradient id="idkL93d" cx="0" cy="0" r="1" gradientTransform="rotate(113.749 10.164 15.104)scale(4.01662 4.13507)" gradientUnits="userSpaceOnUse"><stop class="s7zx1gbow"/><stop offset="1" class="lkmk6jbgz"/></radialGradient><radialGradient id="iILzjIc" cx="0" cy="0" r="1" gradientTransform="rotate(93.244 2.453 12.857)scale(19.7866 19.1478)" gradientUnits="userSpaceOnUse"><stop offset=".837" class="c0v2h1bql"/><stop offset="1" class="z--odq6yb"/></radialGradient><radialGradient id="iK0nWJe" cx="0" cy="0" r="1" gradientTransform="matrix(-.02402 2.56503 -.76778 -.0072 13.848 10.241)" gradientUnits="userSpaceOnUse"><stop offset=".304" class="jmqvhxbnt"/><stop offset="1" class="a9t2ncb-x"/></radialGradient><radialGradient id="iJdF2QF" cx="0" cy="0" r="1" gradientTransform="rotate(136.84 11.79 12.521)scale(3.56633 2.41749)" gradientUnits="userSpaceOnUse"><stop class="py05vebrj"/><stop offset="1" class="btubfmbhj"/></radialGradient><radialGradient id="isilBQa" cx="0" cy="0" r="1" gradientTransform="rotate(124.344 10.997 9.514)scale(2.30423 2.42474)" gradientUnits="userSpaceOnUse"><stop class="py05vebrj"/><stop offset="1" class="btubfmbhj"/></radialGradient><radialGradient id="i9Lvxkc" cx="0" cy="0" r="1" gradientTransform="rotate(124.706 9.416 6.898)scale(3.09549 2.22986)" gradientUnits="userSpaceOnUse"><stop class="py05vebrj"/><stop offset="1" class="btubfmbhj"/></radialGradient><radialGradient id="i60aIyb" cx="0" cy="0" r="1" gradientTransform="matrix(-.90997 2.55112 -1.66421 -.59361 10.93 5.456)" gradientUnits="userSpaceOnUse"><stop class="py05vebrj"/><stop offset="1" class="btubfmbhj"/></radialGradient><radialGradient id="ioPTZsE" cx="0" cy="0" r="1" gradientTransform="matrix(-.47664 1.081 -1.22113 -.53843 5.86 9.39)" gradientUnits="userSpaceOnUse"><stop class="py05vebrj"/><stop offset="1" class="btubfmbhj"/></radialGradient><filter id="i6Xbpnc" width="27.027" height="28.645" x="2.958" y="1.337" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.65098 0 0 0 0 0.592157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1683"/></filter><filter id="iaEdLIS" width="7.038" height="10.612" x="3.67" y="7.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1683" stdDeviation=".75"/></filter><filter id="iC2hZZn" width="7.095" height="12.002" x="7.99" y="3.83" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1683" stdDeviation=".75"/></filter><filter id="iHq7BNL" width="7.078" height="13.072" x="14.684" y="2.291" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1683" stdDeviation=".75"/></filter><filter id="ilhWFFb" width="7.735" height="12.875" x="18.307" y="4.429" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1683" stdDeviation=".75"/></filter><filter id="iHDIbWd" width="2.968" height="5.692" x="19.958" y="12.235" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1683" stdDeviation=".3"/></filter><filter id="iIvidre" width="8.372" height="8.6" x="20.842" y="12.551" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1683" stdDeviation=".75"/></filter><filter id="i879TMP" width="4.049" height="3.811" x="6.726" y="14.095" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1683" stdDeviation=".3"/></filter><filter id="iqHFTrb" width="3.874" height="3.076" x="10.581" y="11.871" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1683" stdDeviation=".3"/></filter><filter id="iIh84ZK" width="4.556" height="2.719" x="14.008" y="12.961" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1683" stdDeviation=".3"/></filter><filter id="iE6jndA" width="4.556" height="2.719" x="17.785" y="15.187" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1683" stdDeviation=".3"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:vulcan-salute-light" /></template>
<style>
.a9t2ncb-x {
  stop-color: var(--svg-color--daa287, #DAA287);
  stop-opacity: 0;
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.bma3owbau {
  stop-color: var(--svg-color--cc8566, #CC8566);
}

.bt-o6mb1h {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M11.481 14.047c.363-.057 1.514-.346 2.074-1.276");
}

.btsp6rbtk {
  stop-color: var(--svg-color--fec8b8, #FEC8B8);
}

.btubfmbhj {
  stop-color: var(--svg-color--ffe4c8, #FFE4C8);
  stop-opacity: 0;
}

.bx1qcr8op {
  width: 1.494px;
  height: 9.439px;
  x: 9.287px;
  y: 5.616px;
  fill: var(--svg-color--ffd8c2, #FFD8C2);
  rx: 0.747px;
}

.by1xrq2gn {
  stop-color: var(--svg-color--fbc5b3, #FBC5B3);
  stop-opacity: 0;
}

.c0v2h1bql {
  stop-color: var(--svg-color--ba7d97, #BA7D97);
  stop-opacity: 0;
}

.c11ad9byq {
  stop-color: var(--svg-color--cc896b, #CC896B);
  stop-opacity: 0;
}

.ce-rjlvov {
  width: 1.494px;
  height: 10.452px;
  x: 19.015px;
  y: 3.608px;
  rx: 0.747px;
}

.d95nnob8o {
  stop-color: var(--svg-color--fbc5b2, #FBC5B2);
  stop-opacity: 0;
}

.da29j-lzx {
  stop-color: var(--svg-color--daac92, #DAAC92);
}

.da3thxvdw {
  stop-color: var(--svg-color--e09a7c, #E09A7C);
}

.dghiu33oz {
  d: path("M4.665 15.815a4.99 4.99 0 0 0 5.086-1.405L7.452 8.593a2.45 2.45 0 0 0-4.351 2.172l.679 1.903l.057.169c.196.57.557 1.622.828 2.978");
}

.e6b-jdq7u {
  stop-color: var(--svg-color--e6ad92, #E6AD92);
  stop-opacity: 0;
}

.ef2hcibro {
  stop-color: var(--svg-color--da997a, #DA997A);
}

.eikks2bvz {
  stop-color: var(--svg-color--fcc5b3, #FCC5B3);
}

.eqg3zbc2t {
  stop-color: var(--svg-color--f1bda1, #F1BDA1);
}

.ewfnf5ijd {
  width: 1.589px;
  height: 10.452px;
  x: 23.286px;
  y: 5.699px;
  rx: 0.794px;
}

.f6og14bdq {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
}

.ft5dv1b6b {
  fill: none;
}

.gntgsyb6u {
  stop-color: var(--svg-color--eab194, #EAB194);
  stop-opacity: 0;
}

.gxifl7u3b {
  stop-color: var(--svg-color--deaf92, #DEAF92);
}

.h0rtv8bes {
  d: path("M13.596 11.583a.15.15 0 0 0 .037.06l.495 1.982c-1.612 1.434-3.434 1.475-4.143 1.386l-.237-.598l.003-.004l-2.299-5.816l.019.029l-.369-1.034a2.43 2.43 0 0 1 1.473-3.104c1.278-.455 2.72.173 3.165 1.486c.298.879 1.256 3.788 1.856 5.613");
}

.h3-kpdg0w {
  stop-color: var(--svg-color--f9c4b1, #F9C4B1);
  stop-opacity: 0;
}

.h802rfb4i {
  d: path("m20.515 6.64l-2.85 8.68c.46.614 1.787 1.855 3.799 1.94c0-.036.3-.584.787-1.449l3.146-8.22a2.457 2.457 0 0 0-1.462-3.181c-1.263-.458-2.666.182-3.122 1.446l-.425 1.187z");
}

.hbzhtubqt {
  stop-color: var(--svg-color--deaf92, #DEAF92);
  stop-opacity: 0;
}

.hq26renpk {
  d: path("m22.258 15.792l-.008.012c-.348 1.417-.32 4.259 1.725 6.454c.62-1.007 1.632-2.361 2.242-3.151l2.283-2.58c.953-1.03 1.042-2.55-.104-3.61c-1.03-.952-2.735-.807-3.862.438l-2.283 2.457z");
}

.huzidx7ok {
  stop-color: var(--svg-color--e1b296, #E1B296);
}

.hz3-s9nlv {
  stop-color: var(--svg-color--e1b296, #E1B296);
  stop-opacity: 0;
}

.i3rbzskiq {
  stop-color: var(--svg-color--e9b5aa, #E9B5AA);
}

.i6onak34h {
  stop-color: var(--svg-color--cc8566, #CC8566);
  stop-opacity: 0;
}

.i8lby6hve {
  stop-color: var(--svg-color--e09a7c, #E09A7C);
  stop-opacity: 0;
}

.ivymufunm {
  stop-color: var(--svg-color--fbc5b3, #FBC5B3);
}

.j1_0hmb-z {
  stop-color: var(--svg-color--f8c3b0, #F8C3B0);
  stop-opacity: 0;
}

.j1z7pbbbo {
  d: path("M20.947 5.277a2.45 2.45 0 0 0-1.588-3.072a2.43 2.43 0 0 0-3.061 1.56a290 290 0 0 0-2.415 7.812c-.041.142-.241.146-.287.006c-.6-1.825-1.558-4.734-1.856-5.613c-.446-1.313-1.887-1.941-3.165-1.486a2.43 2.43 0 0 0-1.473 3.104l.368 1.034a2.45 2.45 0 0 0-4.369 2.143l.679 1.903c.235.697.904 2.518 1.148 4.87l.065.644c.244 2.454.519 5.22 1.953 7.523a8.33 8.33 0 0 0 7.28 4.277a8.3 8.3 0 0 0 3.476-.758c1.361-.584 2.62-1.48 3.6-2.801c1.16-1.473 1.546-2.167 2.139-3.23q.152-.275.33-.59c.576-1.02 1.763-2.612 2.445-3.496l2.284-2.58c.953-1.03 1.042-2.55-.104-3.61c-1.03-.952-2.735-.807-3.862.438l-2.283 2.457l3.146-8.222a2.457 2.457 0 0 0-1.462-3.18c-1.263-.458-2.666.182-3.122 1.446q-.198.548-.425 1.187z");
}

.jmqvhxbnt {
  stop-color: var(--svg-color--daa287, #DAA287);
}

.jrmxsr73p {
  stroke-linecap: round;
  d: path("m22.842 19.151l4.372-4.6");
}

.jsmhdtb5y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M18.685 16.087c.405.297 1.524.897 2.756.918");
}

.jt1f-bcod {
  stop-color: var(--svg-color--ffd9bf, #FFD9BF);
  stop-opacity: 0;
}

.kava7d4sq {
  stop-color: var(--svg-color--d8a196, #D8A196);
}

.kjkcnpftl {
  fill: var(--svg-color--fbc5b2, #FBC5B2);
  d: path("M20.947 5.277a2.45 2.45 0 0 0-1.588-3.072a2.43 2.43 0 0 0-3.061 1.56a290 290 0 0 0-2.415 7.812c-.041.142-.241.146-.287.006c-.6-1.825-1.558-4.734-1.856-5.613c-.446-1.313-1.887-1.941-3.165-1.486a2.43 2.43 0 0 0-1.473 3.104l.368 1.034a2.45 2.45 0 0 0-4.369 2.143l.679 1.903c.235.697.904 2.518 1.148 4.87l.065.644c.244 2.454.519 5.22 1.953 7.523a8.33 8.33 0 0 0 7.28 4.277a8.3 8.3 0 0 0 3.476-.758c1.361-.584 2.62-1.48 3.6-2.801c1.16-1.473 1.546-2.167 2.139-3.23q.152-.275.33-.59c.576-1.02 1.763-2.612 2.445-3.496l2.284-2.58c.953-1.03 1.042-2.55-.104-3.61c-1.03-.952-2.735-.807-3.862.438l-2.283 2.457l3.146-8.222a2.457 2.457 0 0 0-1.462-3.18c-1.263-.458-2.666.182-3.122 1.446q-.198.548-.425 1.187z");
}

.ks214lbap {
  stop-color: var(--svg-color--d8a196, #D8A196);
  stop-opacity: 0;
}

.ktrxt1b5o {
  stop-color: var(--svg-color--e19f83, #E19F83);
  stop-opacity: 0;
}

.l910ugb3j {
  stop-color: var(--svg-color--d9ad93, #D9AD93);
}

.l9pur1csk {
  stop-color: var(--svg-color--e9b5aa, #E9B5AA);
  stop-opacity: 0;
}

.lde1lbc4x {
  stop-color: var(--svg-color--fcc5b3, #FCC5B3);
  stop-opacity: 0;
}

.lk7dbcc7r {
  stop-color: var(--svg-color--ffd6bf, #FFD6BF);
}

.lkmk6jbgz {
  stop-color: var(--svg-color--e7b89b, #E7B89B);
  stop-opacity: 0;
}

.lyot_fbwv {
  stop-color: var(--svg-color--fbc5b2, #FBC5B2);
}

.mrx-mta2y {
  stop-color: var(--svg-color--d7a889, #D7A889);
  stop-opacity: 0;
}

.n7ki7rm8i {
  stop-color: var(--svg-color--f9c4b1, #F9C4B1);
}

.okcr8bcgn {
  stop-color: var(--svg-color--f8c3b0, #F8C3B0);
}

.pf1lpbc4v {
  d: path("M13.8 11.673c.083 2.689 2.763 3.826 3.94 3.482l2.865-8.797l.342-1.081a2.45 2.45 0 0 0-1.588-3.072a2.43 2.43 0 0 0-3.061 1.56a290 290 0 0 0-2.415 7.812a.15.15 0 0 1-.083.096");
}

.pkoe_9n2o {
  stop-color: var(--svg-color--f1bda1, #F1BDA1);
  stop-opacity: 0;
}

.pv5xzqh5q {
  stop-color: var(--svg-color--d9ad93, #D9AD93);
  stop-opacity: 0;
}

.py05vebrj {
  stop-color: var(--svg-color--ffe4c8, #FFE4C8);
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qtnyoe6zz {
  stop-color: var(--svg-color--86575f, #86575F);
  stop-opacity: 0;
}

.qukmd6-ht {
  stop-color: var(--svg-color--d69478, #D69478);
  stop-opacity: 0;
}

.rfpayfbmn {
  stop-color: var(--svg-color--da997a, #DA997A);
  stop-opacity: 0;
}

.rzgkgdcgx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M7.626 17.005c.332-.158 1.522-1.11 2.249-2.01");
}

.s7zx1gbow {
  stop-color: var(--svg-color--e7b89b, #E7B89B);
}

.satevfbvr {
  stop-color: var(--svg-color--d69478, #D69478);
}

.sosxdhbyi {
  stop-color: var(--svg-color--cc896b, #CC896B);
}

.sso9s_bho {
  stop-color: var(--svg-color--e1aa8c, #E1AA8C);
  stop-opacity: 0;
}

.swab9xvjw {
  stop-color: var(--svg-color--e19f83, #E19F83);
}

.tmqbcuz_q {
  stop-color: var(--svg-color--ffd6bf, #FFD6BF);
  stop-opacity: 0;
}

.u8k763igq {
  stop-color: var(--svg-color--e6ad92, #E6AD92);
}

.uxy3yk0bv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("m20.858 17.027l1.167-3.892");
}

.vfztw_b5g {
  stop-color: var(--svg-color--daac92, #DAAC92);
  stop-opacity: 0;
}

.vv0xjz_lx {
  stop-color: var(--svg-color--fec8b8, #FEC8B8);
  stop-opacity: 0;
}

.w12xup1lx {
  stop-color: var(--svg-color--ffd9bf, #FFD9BF);
}

.xn-pf7auk {
  d: path("M20.986 5.272A2.45 2.45 0 0 0 19.394 2.2a2.436 2.436 0 0 0-3.068 1.559a290 290 0 0 0-2.42 7.813c-.041.142-.241.146-.287.006c-.601-1.825-1.562-4.735-1.86-5.614c-.447-1.312-1.892-1.94-3.172-1.485A2.43 2.43 0 0 0 7.11 7.583l.37 1.034a2.46 2.46 0 0 0-2.892-.986A2.447 2.447 0 0 0 3.1 10.76l.68 1.903c.236.697.907 2.518 1.15 4.87q.034.318.066.645c.245 2.454.52 5.22 1.957 7.523a8.35 8.35 0 0 0 7.296 4.276a8.3 8.3 0 0 0 3.484-.758c1.363-.583 2.626-1.48 3.607-2.8c1.162-1.473 1.55-2.167 2.143-3.231l.331-.59c.578-1.02 1.767-2.611 2.451-3.496l2.289-2.58c.954-1.03 1.044-2.549-.105-3.61c-1.031-.952-2.74-.806-3.87.438l-2.288 2.457l3.153-8.221a2.456 2.456 0 0 0-1.465-3.181c-1.266-.458-2.672.182-3.129 1.446l-.426 1.187z");
}

.y1ea_7b_c {
  stop-color: var(--svg-color--eab194, #EAB194);
}

.y2p0ho9os {
  width: 1.494px;
  height: 8.12px;
  x: 4.941px;
  y: 8.864px;
  fill: var(--svg-color--ffd8c2, #FFD8C2);
  rx: 0.747px;
}

.yhx-yvbws {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M14.908 13.861c.406.297 1.524.897 2.757.919");
}

.z--odq6yb {
  stop-color: var(--svg-color--ba7d97, #BA7D97);
}

</style>
