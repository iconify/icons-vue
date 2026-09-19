<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iOgEq3k)" transform="rotate(39.16 14.713 7.693)" class="j2g9xu4kz"/><path fill="url(#i9P6Pfe)" class="g1kh2qb1q"/><g filter="url(#i0gUlIQ)"><path fill="url(#ib3tmPe)" class="u1q_a9hhw"/><path fill="url(#iC6ZAkb)" class="u1q_a9hhw"/><path fill="url(#i5iwlPe)" class="u1q_a9hhw"/></g><path clip-rule="evenodd" class="db3mztq5s"/><g filter="url(#i7SU7Cd)"><path clip-rule="evenodd" class="sv3-mib2z"/></g><g filter="url(#i5sdmUc)"><path class="v8aobmb-x"/><path fill="url(#i7HMoQd)" class="zsh3y5h9j"/></g><path fill="url(#idDNuHb)" class="o6j7dz83m"/><path fill="url(#iqDkHVV)" class="ro1ldqjks"/><path fill="url(#iHVDSsc)" class="ro1ldqjks"/><path fill="url(#iWeK0Nb)" class="ro1ldqjks"/><path fill="url(#ikLYk6c)" class="ro1ldqjks"/><g filter="url(#ieVjKTd)"><path fill="url(#ifNfzDd)" class="sdqj75bps"/><path fill="url(#iVi05nd)" class="sdqj75bps"/><path fill="url(#im9LEre)" class="sdqj75bps"/></g><g filter="url(#i7r7Utb)"><rect fill="url(#icJNbkV)" class="kye1_glzb"/><rect fill="url(#it8Yyrc)" class="kye1_glzb"/><rect fill="url(#i0P34jd)" class="kye1_glzb"/><rect fill="url(#i5xqwHd)" class="kye1_glzb"/></g><rect fill="url(#i9euRxc)" transform="rotate(-21.787 19.523 13.05)" class="mqis46b6x"/><path fill="url(#iRPRnQX)" class="gaeav5bxj"/><path fill="url(#ipqP9db)" class="gaeav5bxj"/><path fill="url(#iGZJpTd)" class="gaeav5bxj"/><g filter="url(#i3mlFIS)"><path fill="url(#iIIdFte)" class="pmi710-fw"/></g><g filter="url(#iRhp4Ic)"><path fill="url(#i3462dc)" class="pm433v4xq"/><path fill="url(#ixf2lic)" class="pm433v4xq"/><path fill="url(#ipgbQBd)" class="pm433v4xq"/></g><g filter="url(#iRZzW0G)"><path class="kwiil8sub"/><path fill="url(#ipbZuMd)" class="oojmopbyl"/></g><g filter="url(#iayiXyc)"><path stroke="url(#i8euLGY)" class="gihz4osgq"/></g><g filter="url(#iGBqRCd)"><path fill="url(#izOQc6b)" class="jxwh-cp3v"/></g><path fill="url(#i1Ip81c)" class="c-cmwqxza"/><path class="wpbyp44yl"/><path fill="url(#ittguvr)" class="uc7h4ibxx"/><path fill="url(#iiQV1xd)" class="fd88gpbqi"/><path class="xsrxwtkxf"/><g filter="url(#iAde7Rc)"><path fill="url(#iIfbWUd)" class="j8sx0ac5d"/><path fill="url(#iKwQwDc)" class="j8sx0ac5d"/></g><defs><radialGradient id="iOgEq3k" cx="0" cy="0" r="1" gradientTransform="rotate(112.51 5.32 9.65)scale(1.02069 1.88161)" gradientUnits="userSpaceOnUse"><stop offset=".142" class="vcu64j97k"/><stop offset="1" class="gunhc6l2n"/></radialGradient><radialGradient id="i9P6Pfe" cx="0" cy="0" r="1" gradientTransform="rotate(109.376 6.266 10.516)scale(.62401 .57809)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="h3zh53qvw"/><stop offset="1" class="fi90oja5q"/></radialGradient><radialGradient id="ib3tmPe" cx="0" cy="0" r="1" gradientTransform="rotate(161.861 8.173 5.272)scale(2.84448 2.94485)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="r-d7trp-i"/><stop offset="1" class="r6qq21ggw"/></radialGradient><radialGradient id="iC6ZAkb" cx="0" cy="0" r="1" gradientTransform="rotate(107.289 5.875 10.18)scale(.61776 .64399)" gradientUnits="userSpaceOnUse"><stop class="f1i_yegdv"/><stop offset="1" class="u88gs8tgg"/></radialGradient><radialGradient id="i5iwlPe" cx="0" cy="0" r="1" gradientTransform="matrix(-.60106 2 -1.01904 -.30625 16.903 6.087)" gradientUnits="userSpaceOnUse"><stop offset=".128" class="ckhkjqgwn"/><stop offset="1" class="qji6614xa"/></radialGradient><radialGradient id="i7HMoQd" cx="0" cy="0" r="1" gradientTransform="rotate(72.474 -1.04 15.235)scale(4.35856 2.29046)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="ik1b347lr"/><stop offset="1" class="fyswmcz3l"/></radialGradient><radialGradient id="idDNuHb" cx="0" cy="0" r="1" gradientTransform="rotate(15.117 -49.08 48.648)scale(4.82315 2.16799)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="espuh9d_f"/><stop offset=".77" class="z7o0euhwd"/></radialGradient><radialGradient id="iWeK0Nb" cx="0" cy="0" r="1" gradientTransform="matrix(5.5625 -6.21875 2.25745 2.01923 13.145 22.014)" gradientUnits="userSpaceOnUse"><stop class="e21-2rm4b"/><stop offset="1" class="d8-6g_bzt"/></radialGradient><radialGradient id="ikLYk6c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.15625 -1.84376 1.36973 -1.60188 11.332 21.92)" gradientUnits="userSpaceOnUse"><stop class="rqyiu8baj"/><stop offset="1" class="wwotuurhh"/></radialGradient><radialGradient id="ifNfzDd" cx="0" cy="0" r="1" gradientTransform="rotate(133.063 7.223 15.085)scale(9.15342 18.4848)" gradientUnits="userSpaceOnUse"><stop class="b2ub1pmeu"/><stop offset="1" class="bit9nibqa"/></radialGradient><radialGradient id="iVi05nd" cx="0" cy="0" r="1" gradientTransform="rotate(-133.468 9.89 10.4)scale(4.13363 7.33334)" gradientUnits="userSpaceOnUse"><stop class="hob-w_b7u"/><stop offset="1" class="wqxg4jbgc"/></radialGradient><radialGradient id="im9LEre" cx="0" cy="0" r="1" gradientTransform="matrix(-4.875 .37502 -1.76114 -22.89326 31.55 23.108)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="ifzxkw8wi"/><stop offset="1" class="e_s-6on8g"/></radialGradient><radialGradient id="it8Yyrc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -1 27.55 16.139)" gradientUnits="userSpaceOnUse"><stop class="akun2bbyl"/><stop offset="1" class="fsljb8bqi"/></radialGradient><radialGradient id="i0P34jd" cx="0" cy="0" r="1" gradientTransform="matrix(16.1875 0 0 .71644 4.27 16.61)" gradientUnits="userSpaceOnUse"><stop class="xqbtmwqoi"/><stop offset="1" class="y866tkb_w"/></radialGradient><radialGradient id="i5xqwHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8125 -9.78125 0 17.957 16.389)" gradientUnits="userSpaceOnUse"><stop class="bkb526bql"/><stop offset="1" class="mpozi6wus"/></radialGradient><radialGradient id="i9euRxc" cx="0" cy="0" r="1" gradientTransform="matrix(.6797 -.01657 .00353 .14487 20.018 13.311)" gradientUnits="userSpaceOnUse"><stop class="sl7x9k6lz"/><stop offset="1" class="mhva3mbnf"/></radialGradient><radialGradient id="iRPRnQX" cx="0" cy="0" r="1" gradientTransform="rotate(135.21 8.316 10.764)scale(12.0651 1.31103)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="s5cu-8c1s"/><stop offset="1" class="zuv3brbdp"/></radialGradient><radialGradient id="iIIdFte" cx="0" cy="0" r="1" gradientTransform="matrix(-3.55739 3.43749 -2.0246 -2.09522 14.64 20.951)" gradientUnits="userSpaceOnUse"><stop class="ja67fo1gr"/><stop offset="1" class="lx7f_77ow"/></radialGradient><radialGradient id="ixf2lic" cx="0" cy="0" r="1" gradientTransform="matrix(-3.09375 0 0 -12.375 30.176 28.92)" gradientUnits="userSpaceOnUse"><stop class="ncdif6bxa"/><stop offset="1" class="qjl30cblz"/></radialGradient><radialGradient id="ipbZuMd" cx="0" cy="0" r="1" gradientTransform="matrix(.60937 -.29688 .16254 .33364 20.747 13.9)" gradientUnits="userSpaceOnUse"><stop class="p1w13ebbm"/><stop offset="1" class="tiuzwhbbw"/></radialGradient><radialGradient id="izOQc6b" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 2.4375 -1.4473 1.28031 15.176 10.139)" gradientUnits="userSpaceOnUse"><stop offset=".049" class="d8l2uy9_q"/><stop offset="1" class="ml-wi-9ur"/></radialGradient><radialGradient id="i1Ip81c" cx="0" cy="0" r="1" gradientTransform="matrix(-.36061 .26664 -.28066 -.37957 17.457 7.26)" gradientUnits="userSpaceOnUse"><stop class="m8h6tdgkz"/><stop offset="1" class="ju-dj4awd"/></radialGradient><radialGradient id="ittguvr" cx="0" cy="0" r="1" gradientTransform="matrix(.12683 -.48047 .539 .14228 17.543 7.748)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="k23k8xbao"/><stop offset="1" class="cemcwib4u"/></radialGradient><radialGradient id="iiQV1xd" cx="0" cy="0" r="1" gradientTransform="matrix(.07385 .26172 -.25328 .07147 17.49 7.483)" gradientUnits="userSpaceOnUse"><stop class="m8h6tdgkz"/><stop offset="1" class="ju-dj4awd"/></radialGradient><radialGradient id="iIfbWUd" cx="0" cy="0" r="1" gradientTransform="rotate(163.724 8.884 4.308)scale(5.51064 6.88411)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="n1atf6iop"/><stop offset="1" class="z8cj4zb3m"/></radialGradient><radialGradient id="iKwQwDc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35938 .17969 -.15962 -1.20756 18.854 5.306)" gradientUnits="userSpaceOnUse"><stop class="e4cf86x4h"/><stop offset="1" class="dar5wrbvj"/></radialGradient><filter id="i0gUlIQ" width="4.364" height="4.439" x="14.22" y="5.444" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.25098 0 0 0 0 0.219608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23068"/></filter><filter id="i7SU7Cd" width=".763" height=".367" x="17.245" y="6.579" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.133333 0 0 0 0 0.0705882 0 0 0 0 0.0941176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23068"/></filter><filter id="i5sdmUc" width="6.377" height="6.141" x="9.574" y="8.943" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.321569 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23068"/></filter><filter id="ieVjKTd" width="27.983" height="6.037" x="2.059" y="20.514" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.541176 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23068"/></filter><filter id="i7r7Utb" width="24.059" height="2.191" x="3.886" y="15.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.529412 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23068"/></filter><filter id="i3mlFIS" width="6.802" height="6.803" x="8.337" y="19.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.556863 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23068"/></filter><filter id="iRhp4Ic" width="27.983" height="6.037" x="1.959" y="24.014" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.843137 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23068"/></filter><filter id="iRZzW0G" width="6.678" height="4.108" x="14.785" y="10.838" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.419608 0 0 0 0 0.286275 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23068"/></filter><filter id="iayiXyc" width="5.181" height="3.008" x="14.876" y="11.184" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23068" stdDeviation=".2"/></filter><filter id="iGBqRCd" width="3.882" height="3.705" x="12.803" y="9.239" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.15"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.243137 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23068"/></filter><filter id="iAde7Rc" width="6.317" height="5.313" x="12.906" y="3.831" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0588235 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23068"/></filter><linearGradient id="iqDkHVV" x1="25.051" x2="7.801" y1="18.858" y2="24.233" gradientUnits="userSpaceOnUse"><stop offset=".353" class="wvez-gyvu"/><stop offset="1" class="a-c1axuni"/></linearGradient><linearGradient id="iHVDSsc" x1="27.145" x2="26.441" y1="20.42" y2="20.42" gradientUnits="userSpaceOnUse"><stop class="v5wfdhbpr"/><stop offset="1" class="jv6m1sr_z"/></linearGradient><linearGradient id="icJNbkV" x1="16.015" x2="16.395" y1="15.264" y2="18.795" gradientUnits="userSpaceOnUse"><stop class="rltzfib1k"/><stop offset="1" class="f6scwccnd"/></linearGradient><linearGradient id="ipqP9db" x1="17.168" x2="17.582" y1="16.299" y2="16.694" gradientUnits="userSpaceOnUse"><stop class="pna-0uy1p"/><stop offset="1" class="v15kcqbep"/></linearGradient><linearGradient id="iGZJpTd" x1="19.52" x2="19.184" y1="15.983" y2="15.631" gradientUnits="userSpaceOnUse"><stop class="f3ogmdbgo"/><stop offset="1" class="a_bfjubwy"/></linearGradient><linearGradient id="i3462dc" x1="18.457" x2="12.738" y1="23.389" y2="33.483" gradientUnits="userSpaceOnUse"><stop class="afnbbr78b"/><stop offset="1" class="k73oz-bdw"/></linearGradient><linearGradient id="ipgbQBd" x1="18.02" x2="18.02" y1="29.951" y2="29.67" gradientUnits="userSpaceOnUse"><stop class="pjzjl2c9v"/><stop offset="1" class="dzuixsuao"/></linearGradient><linearGradient id="i8euLGY" x1="15.804" x2="20.086" y1="12.244" y2="13.962" gradientUnits="userSpaceOnUse"><stop class="ul9idmbej"/><stop offset="1" class="w86a2obti"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-rowing-boat-medium-dark" /></template>
<style>
.a_bfjubwy {
  stop-color: var(--svg-color--d59c7a, #D59C7A);
  stop-opacity: 0;
}

.a-c1axuni {
  stop-color: var(--svg-color--679951, #679951);
}

.afnbbr78b {
  stop-color: var(--svg-color--5fcdff, #5FCDFF);
}

.akun2bbyl {
  stop-color: var(--svg-color--78bb7d, #78BB7D);
}

.b2ub1pmeu {
  stop-color: var(--svg-color--379fe9, #379FE9);
}

.bit9nibqa {
  stop-color: var(--svg-color--3691df, #3691DF);
}

.bkb526bql {
  stop-color: var(--svg-color--70a762, #70A762);
}

.c-cmwqxza {
  d: path("m16.914 7.468l.116.062l.57-.289c-.28-.16-.543-.127-.722.025c-.068.058-.042.16.036.202");
}

.cemcwib4u {
  stop-color: var(--svg-color--a38c84, #A38C84);
}

.ckhkjqgwn {
  stop-color: var(--svg-color--926d66, #926D66);
}

.d8-6g_bzt {
  stop-color: var(--svg-color--79af4c, #79AF4C);
  stop-opacity: 0;
}

.d8l2uy9_q {
  stop-color: var(--svg-color--9178d3, #9178D3);
}

.dar5wrbvj {
  stop-color: var(--svg-color--3f3438, #3F3438);
  stop-opacity: 0;
}

.db3mztq5s {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M16.98 8.458a.1.1 0 0 1 .132.05c.032.07.15.243.339.324a.1.1 0 0 1-.079.184a.92.92 0 0 1-.442-.425a.1.1 0 0 1 .05-.133");
}

.dzuixsuao {
  stop-color: var(--svg-color--55beff, #55BEFF);
  stop-opacity: 0;
}

.e_s-6on8g {
  stop-color: var(--svg-color--38a7fb, #38A7FB);
  stop-opacity: 0;
}

.e21-2rm4b {
  stop-color: var(--svg-color--659941, #659941);
}

.e4cf86x4h {
  stop-color: var(--svg-color--3f3438, #3F3438);
}

.espuh9d_f {
  stop-color: var(--svg-color--8d8695, #8D8695);
}

.f1i_yegdv {
  stop-color: var(--svg-color--9a796d, #9A796D);
}

.f3ogmdbgo {
  stop-color: var(--svg-color--d59c7a, #D59C7A);
}

.f6scwccnd {
  stop-color: var(--svg-color--4d8c4e, #4D8C4E);
}

.fd88gpbqi {
  d: path("M17.641 7.769q.045-.05.061-.11c.027-.099-.019-.206-.097-.227c-.08-.021-.17.04-.198.148a.3.3 0 0 0-.002.126z");
}

.fi90oja5q {
  stop-color: var(--svg-color--7c5741, #7C5741);
}

.fsljb8bqi {
  stop-color: var(--svg-color--78bb7d, #78BB7D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fyswmcz3l {
  stop-color: var(--svg-color--57399f, #57399F);
  stop-opacity: 0;
}

.g1kh2qb1q {
  d: path("M18.232 8.05c-.081-.148-.066-.412-.047-.505l-.445 1.02c.14.074.378.139.515-.032c.098-.12.079-.3-.023-.484");
}

.gaeav5bxj {
  d: path("M21.334 12.266a.59.59 0 0 1 .829.84l-8.439 8.331a.59.59 0 1 1-.829-.84z");
}

.gihz4osgq {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M15.43 11.712c.291.35.889.871 1.804 1.165c1.438.46 1.734.515 2.36.726");
}

.gunhc6l2n {
  stop-color: var(--svg-color--754f43, #754F43);
}

.h3zh53qvw {
  stop-color: var(--svg-color--8d6e63, #8D6E63);
}

.hob-w_b7u {
  stop-color: var(--svg-color--286ec5, #286EC5);
}

.ifzxkw8wi {
  stop-color: var(--svg-color--38a7fb, #38A7FB);
}

.ik1b347lr {
  stop-color: var(--svg-color--57399f, #57399F);
}

.j2g9xu4kz {
  d: path("M14.713 7.693h1.744v2h-1.744z");
}

.j8sx0ac5d {
  d: path("M13.6 6.773c.332-.227.418-.442.515-1.094c.219-1.094.542-1.306.969-1.547c.449-.254 1.195-.188 1.703.195c.558.42.668.341 1.348.363c.722.024.972.496.988.91c.015.415-.207.981-.934 1.032c-.834.058-.875-.688-1.574-.531c-.596.133-.727 1.316-.976 1.796c-.159.306-.3 1.013-1.165 1.211c-.921.211-1.68-.562-1.554-1.328c.1-.612.382-.805.68-1.007");
}

.ja67fo1gr {
  stop-color: var(--svg-color--fbc998, #FBC998);
}

.ju-dj4awd {
  stop-color: var(--svg-color--191919, #191919);
}

.jv6m1sr_z {
  stop-color: var(--svg-color--99d852, #99D852);
  stop-opacity: 0;
}

.jxwh-cp3v {
  d: path("M13.004 11.06c.6.72 1.333 1.556 1.625 1.884l1.656-1.485c-.33-.396-1.117-1.303-1.617-1.765c-.625-.578-1.27-.192-1.469 0c-.172.165-.672.687-.195 1.367");
}

.k23k8xbao {
  stop-color: var(--svg-color--6b4841, #6B4841);
}

.k73oz-bdw {
  stop-color: var(--svg-color--4aadff, #4AADFF);
}

.kwiil8sub {
  fill: var(--svg-color--886657, #886657);
  d: path("M16.504 13.772c-.713-.332-1.443-.966-1.719-1.242l1.281-1.192c1.157 1.11 2.375 1.278 2.684 1.352c.395.093 1.538.3 2.168.73c.516.352.379.992.07 1.266c-.254.225-.675.336-1.011.203s-.559-.27-1.227-.398a10 10 0 0 1-2.246-.72");
}

.kye1_glzb {
  width: 23.859px;
  height: 2.191px;
  x: 4.086px;
  y: 15.515px;
  rx: 1.095px;
}

.lx7f_77ow {
  stop-color: var(--svg-color--e9b37e, #E9B37E);
}

.m8h6tdgkz {
  stop-color: var(--svg-color--3d3d3d, #3D3D3D);
}

.mhva3mbnf {
  stop-color: var(--svg-color--76594d, #76594D);
}

.ml-wi-9ur {
  stop-color: var(--svg-color--7151be, #7151BE);
}

.mpozi6wus {
  stop-color: var(--svg-color--70a762, #70A762);
  stop-opacity: 0;
}

.mqis46b6x {
  width: 1.28px;
  height: 0.637px;
  x: 19.523px;
  y: 13.051px;
  rx: 0.318px;
}

.n1atf6iop {
  stop-color: var(--svg-color--31222a, #31222A);
}

.ncdif6bxa {
  stop-color: var(--svg-color--65deff, #65DEFF);
}

.o6j7dz83m {
  d: path("M9.598 13.717c-.243.895-.203 1.762-.11 2.024l6.309-.063z");
}

.oojmopbyl {
  d: path("M16.504 13.772c-.713-.332-1.443-.966-1.719-1.242l1.281-1.192c1.157 1.11 2.375 1.278 2.684 1.352c.395.093 1.538.3 2.168.73c.516.352.379.992.07 1.266c-.254.225-.675.336-1.011.203s-.559-.27-1.227-.398a10 10 0 0 1-2.246-.72");
}

.p1w13ebbm {
  stop-color: var(--svg-color--977970, #977970);
}

.pjzjl2c9v {
  stop-color: var(--svg-color--59a0ff, #59A0FF);
}

.pm433v4xq {
  d: path("M3.504 24.436c-.775-.425-1.254-.422-1.445-.422v5.937H29.94v-5.937c-1.562 0-2.214 1.156-3.53 1.156c-1.317 0-2.188-1.156-3.548-1.156c-1.117 0-2.242 1.156-3.508 1.156c-.972 0-2.203-1.156-3.39-1.156c-1.258 0-2.262 1.156-3.399 1.156c-.558 0-.836-.101-1.539-.437s-1.324-.704-1.98-.704c-.654 0-1.311.334-1.88.622l-.007.003c-.57.29-1.031.516-1.656.516s-1.031-.203-2-.734");
}

.pmi710-fw {
  d: path("M11.366 20.315a1.917 1.917 0 1 1 2.712 2.71l-2.468 2.47a1.917 1.917 0 1 1-2.712-2.711z");
}

.pna-0uy1p {
  stop-color: var(--svg-color--cd9157, #CD9157);
}

.qji6614xa {
  stop-color: var(--svg-color--926d66, #926D66);
  stop-opacity: 0;
}

.qjl30cblz {
  stop-color: var(--svg-color--5dc9ff, #5DC9FF);
  stop-opacity: 0;
}

.r-d7trp-i {
  stop-color: var(--svg-color--8f695d, #8F695D);
}

.r6qq21ggw {
  stop-color: var(--svg-color--81534e, #81534E);
}

.rltzfib1k {
  stop-color: var(--svg-color--79b34c, #79B34C);
}

.ro1ldqjks {
  d: path("m5.232 16.973l21.725-.022v6.25l-18.008-.117z");
}

.rqyiu8baj {
  stop-color: var(--svg-color--528c3f, #528C3F);
}

.s5cu-8c1s {
  stop-color: var(--svg-color--fecca0, #FECCA0);
}

.sdqj75bps {
  d: path("M3.504 20.936c-.775-.425-1.254-.422-1.445-.422v5.937H29.94v-5.937c-1.562 0-2.214 1.156-3.53 1.156c-1.317 0-2.188-1.156-3.548-1.156c-1.117 0-2.242 1.156-3.508 1.156c-.972 0-2.203-1.156-3.39-1.156c-1.258 0-2.262 1.156-3.399 1.156c-.558 0-.836-.101-1.539-.437s-1.324-.704-1.98-.704c-.654 0-1.311.334-1.88.622l-.007.003c-.57.29-1.031.516-1.656.516s-1.031-.203-2-.734");
}

.sl7x9k6lz {
  stop-color: var(--svg-color--81675e, #81675E);
}

.sv3-mib2z {
  fill: var(--svg-color--453a3a, #453A3A);
  fill-rule: evenodd;
  d: path("M17.866 6.937a.72.72 0 0 0-.488-.028a.1.1 0 0 1-.066-.189a.92.92 0 0 1 .637.035a.1.1 0 1 1-.083.182");
}

.tiuzwhbbw {
  stop-color: var(--svg-color--977970, #977970);
  stop-opacity: 0;
}

.u1q_a9hhw {
  d: path("M15.931 9.654c-.914-.453-1.535-1.234-1.71-1.617l.662-1.593a1.2 1.2 0 0 1 1.034-.738l1.656-.11c.13-.008.263-.002.372.067c.288.182.576.644.369 1.475c-.229 1.081-.501 1.744-.749 2.227c-.177.344-.533.572-.916.506a3.2 3.2 0 0 1-.718-.217");
}

.u88gs8tgg {
  stop-color: var(--svg-color--9a796d, #9A796D);
  stop-opacity: 0;
}

.uc7h4ibxx {
  d: path("M17.72 7.79c.02-.036.038-.063.051-.112c.048-.178-.02-.355-.169-.394c-.138-.037-.296.079-.343.256a.5.5 0 0 0-.012.124z");
}

.ul9idmbej {
  stop-color: var(--svg-color--957168, #957168);
}

.v15kcqbep {
  stop-color: var(--svg-color--eeb683, #EEB683);
  stop-opacity: 0;
}

.v5wfdhbpr {
  stop-color: var(--svg-color--99d852, #99D852);
}

.v8aobmb-x {
  fill: var(--svg-color--7355bd, #7355BD);
  d: path("M11.168 10.56c-1.006 1.232-1.414 2.669-1.594 3.274l3.992 1.25c.125-1.023.75-2.718 1.172-3.375c.422-.656.489-.87.555-1.347s-.256-1.195-1.336-1.395c-.844-.156-1.854.45-2.789 1.594");
}

.vcu64j97k {
  stop-color: var(--svg-color--683a26, #683A26);
}

.w86a2obti {
  stop-color: var(--svg-color--957168, #957168);
  stop-opacity: 0;
}

.wpbyp44yl {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.645 7.77c.048.013.099-.026.124-.083l.003-.01c.066-.246-.096-.437-.295-.49c-.189-.05-.434.031-.5.277l-.003.01c-.015.06.01.119.066.134z");
}

.wqxg4jbgc {
  stop-color: var(--svg-color--286ec5, #286EC5);
  stop-opacity: 0;
}

.wvez-gyvu {
  stop-color: var(--svg-color--86bf45, #86BF45);
}

.wwotuurhh {
  stop-color: var(--svg-color--528c3f, #528C3F);
  stop-opacity: 0;
}

.xqbtmwqoi {
  stop-color: var(--svg-color--7caf55, #7CAF55);
}

.xsrxwtkxf {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.545 7.398c.016-.037.07-.048.119-.026s.075.07.059.106c-.017.036-.07.048-.119.026s-.075-.07-.059-.106");
}

.y866tkb_w {
  stop-color: var(--svg-color--7caf55, #7CAF55);
  stop-opacity: 0;
}

.z7o0euhwd {
  stop-color: var(--svg-color--697167, #697167);
}

.z8cj4zb3m {
  stop-color: var(--svg-color--2d2029, #2D2029);
}

.zsh3y5h9j {
  d: path("M11.168 10.56c-1.006 1.232-1.414 2.669-1.594 3.274l3.992 1.25c.125-1.023.75-2.718 1.172-3.375c.422-.656.489-.87.555-1.347s-.256-1.195-1.336-1.395c-.844-.156-1.854.45-2.789 1.594");
}

.zuv3brbdp {
  stop-color: var(--svg-color--da9c63, #DA9C63);
}

</style>
