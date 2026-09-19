<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iIc3imb)" class="tkk46s2ga"/><path fill="url(#imEiA8d)" class="tkk46s2ga"/><path fill="url(#ivwhHje)" class="k2cdulbsm"/><path fill="url(#idTmfde)" class="k2cdulbsm"/><path fill="url(#ilbjHHd)" class="k2cdulbsm"/><path fill="url(#iFDtGrd)" class="k2cdulbsm"/><path fill="url(#irqtkOb)" class="u49zracel"/><path fill="url(#iKOIqPb)" class="w_v2j0bnl"/><path fill="url(#iB5cHyc)" class="w_v2j0bnl"/><path fill="url(#ibt3Dtd)" class="c0u_xph-j"/><path fill="url(#i6xPecn)" class="c0u_xph-j"/><path fill="url(#ilFKtwe)" class="c0u_xph-j"/><path fill="url(#i3Escqe)" class="c0u_xph-j"/><path fill="url(#ieBZVGO)" class="c0u_xph-j"/><path fill="url(#ijBx0Wb)" class="c0u_xph-j"/><g filter="url(#iR5KBKc)"><path class="eq7sjuqpv"/></g><g filter="url(#itczlyd)"><path class="xozq3lj7a"/></g><path fill="url(#iwDlNYN)" class="xf-r00bdy"/><g filter="url(#iA0VV4c)"><path class="sbjd83b6j"/></g><path class="bhtzm1pxd"/><path fill="url(#i6AIeIb)" class="f8pkfebeg"/><path fill="url(#isSDrrc)" class="f8pkfebeg"/><path fill="url(#iUQWXte)" class="f8pkfebeg"/><path class="v6fe_va0n"/><path fill="url(#irKpnXb)" class="r86owmbzs"/><path fill="url(#iOFpfmb)" class="r86owmbzs"/><path fill="url(#iHH4EXb)" class="r86owmbzs"/><path fill="url(#iE3t3hb)" class="k3pf03bmr"/><path fill="url(#iwes2Nb)" class="lgd9t0t7h"/><g filter="url(#iymTZzc)"><path stroke="url(#i4IwWDd)" class="qah7xib3r"/></g><g filter="url(#iuzHCGc)"><path fill="url(#ikjaubc)" class="prlidc5yl"/><path fill="url(#i09owWd)" class="prlidc5yl"/></g><path fill="url(#irGHsHc)" class="e6nin-bxt"/><path fill="url(#iwfUiPe)" class="e6nin-bxt"/><path fill="url(#iXlvBQd)" class="e6nin-bxt"/><path fill="url(#iqkftyt)" class="e6nin-bxt"/><defs><linearGradient id="iIc3imb" x1="12.688" x2="12.172" y1="26.469" y2="28.453" gradientUnits="userSpaceOnUse"><stop class="qy_gap38h"/><stop offset="1" class="lux0f0bwt"/></linearGradient><linearGradient id="imEiA8d" x1="11.46" x2="12.391" y1="27.781" y2="28.063" gradientUnits="userSpaceOnUse"><stop class="tymv9cclo"/><stop offset="1" class="wc4ppobbg"/></linearGradient><linearGradient id="ivwhHje" x1="11.46" x2="11.46" y1="28.281" y2="29.375" gradientUnits="userSpaceOnUse"><stop class="y1jqnx6nj"/><stop offset="1" class="vwtdl-che"/></linearGradient><linearGradient id="idTmfde" x1="11.46" x2="11.46" y1="29.996" y2="29.547" gradientUnits="userSpaceOnUse"><stop class="ep-gh42ty"/><stop offset="1" class="kh4wh8bdp"/></linearGradient><linearGradient id="iFDtGrd" x1="12.25" x2="11.234" y1="29.996" y2="29.996" gradientUnits="userSpaceOnUse"><stop class="lux0f0bwt"/><stop offset="1" class="vo9t-cbcf"/></linearGradient><linearGradient id="irqtkOb" x1="15.458" x2="15.458" y1="27.266" y2="29.281" gradientUnits="userSpaceOnUse"><stop class="ssw7krx3h"/><stop offset="1" class="ijq62lbuq"/></linearGradient><linearGradient id="iKOIqPb" x1="22.563" x2="22.563" y1="20.5" y2="26.25" gradientUnits="userSpaceOnUse"><stop class="vq76pqe1z"/><stop offset="1" class="c3htxbc9y"/></linearGradient><linearGradient id="iB5cHyc" x1="24.126" x2="24.126" y1="28.938" y2="24.5" gradientUnits="userSpaceOnUse"><stop class="vy0gzx6od"/><stop offset="1" class="kde62bc8o"/></linearGradient><linearGradient id="ibt3Dtd" x1="12.259" x2="12.259" y1="29.438" y2="11.875" gradientUnits="userSpaceOnUse"><stop class="yo4w3la7l"/><stop offset="1" class="mihv8sb9a"/></linearGradient><linearGradient id="i6xPecn" x1="12.938" x2="12.938" y1="26.996" y2="13.875" gradientUnits="userSpaceOnUse"><stop class="vy0gzx6od"/><stop offset="1" class="kde62bc8o"/></linearGradient><linearGradient id="isSDrrc" x1="11.125" x2="7.063" y1="23.385" y2="13.26" gradientUnits="userSpaceOnUse"><stop class="zga1m_q8g"/><stop offset=".953" class="krybm9-_b"/></linearGradient><linearGradient id="iHH4EXb" x1="10.701" x2="10.013" y1="5.274" y2="4.837" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="i4IwWDd" x1="5.422" x2="7.094" y1="5.59" y2="6.913" gradientUnits="userSpaceOnUse"><stop class="rvhhg_4it"/><stop offset="1" class="e4gg3dbwm"/></linearGradient><linearGradient id="ikjaubc" x1="27.416" x2="20.505" y1="22.156" y2="25.031" gradientUnits="userSpaceOnUse"><stop class="tko4wgpgq"/><stop offset="1" class="spl98vsbp"/></linearGradient><linearGradient id="irGHsHc" x1="15.458" x2="15.458" y1="28.109" y2="30.219" gradientUnits="userSpaceOnUse"><stop class="ssw7krx3h"/><stop offset="1" class="ijq62lbuq"/></linearGradient><linearGradient id="iwfUiPe" x1="15.46" x2="15.46" y1="29.996" y2="29.547" gradientUnits="userSpaceOnUse"><stop class="ep-gh42ty"/><stop offset="1" class="kh4wh8bdp"/></linearGradient><radialGradient id="ilbjHHd" cx="0" cy="0" r="1" gradientTransform="matrix(2.51563 0 0 .55651 7.844 29.248)" gradientUnits="userSpaceOnUse"><stop class="vno3jvbrm"/><stop offset="1" class="t90rrkbux"/></radialGradient><radialGradient id="ilFKtwe" cx="0" cy="0" r="1" gradientTransform="matrix(7.37498 -3.93754 6.29094 11.78288 6.125 23.563)" gradientUnits="userSpaceOnUse"><stop class="im4ye8byt"/><stop offset="1" class="t01iq1bdy"/></radialGradient><radialGradient id="i3Escqe" cx="0" cy="0" r="1" gradientTransform="matrix(1.28125 1.34375 -1.8359 1.7505 7.985 8.562)" gradientUnits="userSpaceOnUse"><stop class="wyjje4nao"/><stop offset=".875" class="zz-4bhbml"/></radialGradient><radialGradient id="ieBZVGO" cx="0" cy="0" r="1" gradientTransform="rotate(160.866 6.184 4.208)scale(3.24158 5.45946)" gradientUnits="userSpaceOnUse"><stop class="cvyk3tgky"/><stop offset="1" class="d23fw14ur"/></radialGradient><radialGradient id="ijBx0Wb" cx="0" cy="0" r="1" gradientTransform="matrix(4.67188 0 0 1.79441 8.969 26.297)" gradientUnits="userSpaceOnUse"><stop class="ry-p-gr9p"/><stop offset="1" class="u2v1a1bvv"/></radialGradient><radialGradient id="iwDlNYN" cx="0" cy="0" r="1" gradientTransform="matrix(-10.5001 -14.03117 6.74117 -5.0447 21.906 25.656)" gradientUnits="userSpaceOnUse"><stop offset=".926" class="ph5qyibfx"/><stop offset="1" class="m1n1sezzt"/></radialGradient><radialGradient id="i6AIeIb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.93753 3.96872 -7.84479 -7.78314 16.438 19.823)" gradientUnits="userSpaceOnUse"><stop offset=".752" class="zga1m_q8g"/><stop offset=".953" class="krybm9-_b"/></radialGradient><radialGradient id="iUQWXte" cx="0" cy="0" r="1" gradientTransform="matrix(-1.21874 1.75001 -2.75817 -1.92084 19.063 23.26)" gradientUnits="userSpaceOnUse"><stop class="h1o4rfbuz"/><stop offset="1" class="gv_5srbco"/></radialGradient><radialGradient id="irKpnXb" cx="0" cy="0" r="1" gradientTransform="rotate(125.838 4.13 5.73)scale(1.38773 1.23721)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="iOFpfmb" cx="0" cy="0" r="1" gradientTransform="matrix(-.53125 .48437 -.42613 -.46737 11.271 5.81)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="iE3t3hb" cx="0" cy="0" r="1" gradientTransform="rotate(95.25 .505 6.931)scale(3.7501 3.79582)" gradientUnits="userSpaceOnUse"><stop offset=".33" class="liqsk19ho"/><stop offset=".791" class="xgvwjslux"/></radialGradient><radialGradient id="iwes2Nb" cx="0" cy="0" r="1" gradientTransform="rotate(129.152 1.799 4.84)scale(4.11041 5.01882)" gradientUnits="userSpaceOnUse"><stop class="i1yo4ybrn"/><stop offset="1" class="hcc_y6bcx"/></radialGradient><radialGradient id="i09owWd" cx="0" cy="0" r="1" gradientTransform="rotate(143.665 10.216 15.139)scale(3.26998 1.30937)" gradientUnits="userSpaceOnUse"><stop class="bey0zbf8r"/><stop offset="1" class="r-jvov03z"/></radialGradient><radialGradient id="iXlvBQd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.20999 0 0 -.79688 18.96 28.86)" gradientUnits="userSpaceOnUse"><stop class="pmkiylb4a"/><stop offset="1" class="di6k7ujjz"/></radialGradient><radialGradient id="iqkftyt" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 .89035 11.719 29.248)" gradientUnits="userSpaceOnUse"><stop class="pmkiylb4a"/><stop offset="1" class="di6k7ujjz"/></radialGradient><filter id="iR5KBKc" width="11.841" height="16.016" x="8.518" y="11.38" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5323" stdDeviation=".5"/></filter><filter id="itczlyd" width="10.255" height="15.82" x="10.25" y="11.376" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.960784 0 0 0 0 0.537255 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_5323"/></filter><filter id="iA0VV4c" width="12.399" height="17.291" x="9.467" y="9.959" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5323" stdDeviation="1.5"/></filter><filter id="iymTZzc" width="3.958" height="3.498" x="3.834" y="5.164" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5323" stdDeviation=".38"/></filter><filter id="iuzHCGc" width="8.911" height="6.25" x="19.505" y="20.625" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5323" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:parrot" /></template>
<style>
.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.bey0zbf8r {
  stop-color: var(--svg-color--ff5b7e, #FF5B7E);
}

.bhtzm1pxd {
  fill: var(--svg-color--3994fb, #3994FB);
  d: path("M19.8 23.816c-4.86-.65-8.71-4.46-9.43-9.29c-.03.13-.05.27-.06.4q-.06.57-.06 1.14c0 5.59 4.16 10.21 9.55 10.93c.45 0 .78-.41.69-.85l-.48-2.34h-.21z");
}

.c0u_xph-j {
  d: path("M16.42 6.266a5.21 5.21 0 0 0-5.38-4.26c-2.7.12-4.82 2.26-4.95 4.95c-.03.71.08 1.4.3 2.02c.25.7.13 1.48-.33 2.06A9.86 9.86 0 0 0 4 17.046c0 5.5 4.55 9.95 10.17 9.95h5.69c.42 0 .73-.38.65-.79z");
}

.c3htxbc9y {
  stop-color: var(--svg-color--ec098c, #EC098C);
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.cvyk3tgky {
  stop-color: var(--svg-color--ff58a2, #FF58A2);
}

.d23fw14ur {
  stop-color: var(--svg-color--ff58a2, #FF58A2);
  stop-opacity: 0;
}

.di6k7ujjz {
  stop-color: var(--svg-color--f9a95b, #F9A95B);
  stop-opacity: 0;
}

.e4gg3dbwm {
  stop-color: var(--svg-color--ffd749, #FFD749);
  stop-opacity: 0;
}

.e6nin-bxt {
  d: path("M18.283 28.5h-5.646a.749.749 0 0 0 .073 1.496h5.5c.41 0 .75-.34.75-.75c0-.385-.3-.708-.677-.746");
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.ep-gh42ty {
  stop-color: var(--svg-color--fa816e, #FA816E);
}

.eq7sjuqpv {
  fill: var(--svg-color--9f205b, #9F205B);
  d: path("M12.8 12.389c-1.811.128-3.22 1.64-3.277 3.51q-.017.528.02 1.051c.362 5.138 4.373 9.123 9.23 9.447c.402-.029.67-.426.561-.825l-2.875-10.53c-.459-1.668-1.98-2.771-3.658-2.653");
}

.f8pkfebeg {
  d: path("M19.8 23.816c-4.86-.65-8.71-4.46-9.43-9.29c-.03.13-.05.27-.06.4q-.06.57-.06 1.14c0 5.59 4.16 10.21 9.55 10.93c.45 0 .78-.41.69-.85l-.48-2.34h-.21z");
}

.ft5dv1b6b {
  fill: none;
}

.gv_5srbco {
  stop-color: var(--svg-color--429bf6, #429BF6);
  stop-opacity: 0;
}

.h1o4rfbuz {
  stop-color: var(--svg-color--429bf6, #429BF6);
}

.hcc_y6bcx {
  stop-color: var(--svg-color--ec9a49, #EC9A49);
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.i1yo4ybrn {
  stop-color: var(--svg-color--ffd151, #FFD151);
}

.ijq62lbuq {
  stop-color: var(--svg-color--fa945d, #FA945D);
}

.im4ye8byt {
  stop-color: var(--svg-color--be476b, #BE476B);
}

.k2cdulbsm {
  d: path("M14.283 28.5H8.637a.749.749 0 0 0 .073 1.496h5.5c.41 0 .75-.34.75-.75c0-.385-.3-.708-.677-.746");
}

.k3pf03bmr {
  d: path("M7.11 9.646a1.76 1.76 0 1 0 0-3.52a1.76 1.76 0 0 0 0 3.52");
}

.kde62bc8o {
  stop-color: var(--svg-color--a73078, #A73078);
  stop-opacity: 0;
}

.kh4wh8bdp {
  stop-color: var(--svg-color--fa816e, #FA816E);
  stop-opacity: 0;
}

.krybm9-_b {
  stop-color: var(--svg-color--3748d5, #3748D5);
}

.lgd9t0t7h {
  d: path("m6.03 8.826l2.81-1.28a2.4 2.4 0 0 0-2.47-1.92c-1.19.05-2.17 1-2.27 2.19c-.07.88.34 1.68 1 2.14c.22.16.54 0 .54-.28v-.24c0-.26.15-.5.39-.61");
}

.liqsk19ho {
  stop-color: var(--svg-color--faad22, #FAAD22);
}

.lux0f0bwt {
  stop-color: var(--svg-color--ca7a27, #CA7A27);
}

.m1n1sezzt {
  stop-color: var(--svg-color--ca8a2a, #CA8A2A);
}

.mihv8sb9a {
  stop-color: var(--svg-color--ef348d, #EF348D);
}

.ph5qyibfx {
  stop-color: var(--svg-color--ca8a2a, #CA8A2A);
  stop-opacity: 0;
}

.pmkiylb4a {
  stop-color: var(--svg-color--f9a95b, #F9A95B);
}

.prlidc5yl {
  d: path("m20.505 22.3l6.91-.675v1.733a2 2 0 0 1-1.772 1.987l-4.618.53z");
}

.qah7xib3r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M6.781 6.2c-.656-.126-1.75.202-1.937 1.452");
}

.qy_gap38h {
  stop-color: var(--svg-color--bc6925, #BC6925);
}

.r-jvov03z {
  stop-color: var(--svg-color--ff5b7e, #FF5B7E);
  stop-opacity: 0;
}

.r86owmbzs {
  d: path("M10.898 7.06a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.rvhhg_4it {
  stop-color: var(--svg-color--ffd749, #FFD749);
}

.ry-p-gr9p {
  stop-color: var(--svg-color--b05282, #B05282);
}

.sbjd83b6j {
  fill: var(--svg-color--ffdd5e, #FFDD5E);
  d: path("m16.632 14.63l2.234 9.62c-3.47-1.396-5.435-5.572-6.33-8.843c-.33-1.203.57-2.338 1.814-2.44a2.16 2.16 0 0 1 2.282 1.663");
}

.spl98vsbp {
  stop-color: var(--svg-color--ff5c80, #FF5C80);
  stop-opacity: 0;
}

.ssw7krx3h {
  stop-color: var(--svg-color--c96d32, #C96D32);
}

.t01iq1bdy {
  stop-color: var(--svg-color--be476b, #BE476B);
  stop-opacity: 0;
}

.t90rrkbux {
  stop-color: var(--svg-color--e0a04d, #E0A04D);
  stop-opacity: 0;
}

.tkk46s2ga {
  d: path("M14.21 28.496h-1.25l1.5-5.31h-1.5l-1.5 5.31H8.71a.749.749 0 1 0 0 1.5h5.5c.41 0 .75-.34.75-.75s-.34-.75-.75-.75");
}

.tko4wgpgq {
  stop-color: var(--svg-color--ff5c80, #FF5C80);
}

.tymv9cclo {
  stop-color: var(--svg-color--c78441, #C78441);
}

.u2v1a1bvv {
  stop-color: var(--svg-color--b05282, #B05282);
  stop-opacity: 0;
}

.u49zracel {
  d: path("M18.21 28.496h-1.25v-5.31h-1.5v5.31h-2.75a.749.749 0 1 0 0 1.5h5.5c.41 0 .75-.34.75-.75s-.34-.75-.75-.75");
}

.v6fe_va0n {
  fill: var(--svg-color--d7d7d7, #D7D7D7);
  d: path("M10.898 8.088a2.028 2.028 0 1 0 0-4.057a2.028 2.028 0 0 0 0 4.057");
}

.vno3jvbrm {
  stop-color: var(--svg-color--e0a04d, #E0A04D);
}

.vo9t-cbcf {
  stop-color: var(--svg-color--ca7a27, #CA7A27);
  stop-opacity: 0;
}

.vq76pqe1z {
  stop-color: var(--svg-color--ed1c26, #ED1C26);
}

.vwtdl-che {
  stop-color: var(--svg-color--db8d3c, #DB8D3C);
}

.vy0gzx6od {
  stop-color: var(--svg-color--a73078, #A73078);
}

.w_v2j0bnl {
  d: path("m27.27 21.056l-7.65.73v5.21h5.21c1.73 0 3.12-1.4 3.12-3.12v-2.19a.623.623 0 0 0-.68-.63");
}

.wc4ppobbg {
  stop-color: var(--svg-color--c78441, #C78441);
  stop-opacity: 0;
}

.wyjje4nao {
  stop-color: var(--svg-color--d52855, #D52855);
}

.xf-r00bdy {
  d: path("M14.24 11.376c-2.03 0-3.72 1.53-3.93 3.55q-.06.57-.06 1.14c0 5.59 4.16 10.21 9.55 10.93c.45 0 .78-.41.69-.85l-2.38-11.62a3.94 3.94 0 0 0-3.87-3.15");
}

.xgvwjslux {
  stop-color: var(--svg-color--c96528, #C96528);
}

.xozq3lj7a {
  fill: var(--svg-color--fcc44c, #FCC44C);
  d: path("M14.24 11.376c-2.03 0-3.72 1.53-3.93 3.55q-.06.57-.06 1.14c0 5.59 4.16 10.21 9.55 10.93c.45 0 .78-.41.69-.85l-2.38-11.62a3.94 3.94 0 0 0-3.87-3.15");
}

.y1jqnx6nj {
  stop-color: var(--svg-color--ca8234, #CA8234);
}

.yo4w3la7l {
  stop-color: var(--svg-color--b2286c, #B2286C);
}

.zga1m_q8g {
  stop-color: var(--svg-color--3748d4, #3748D4);
  stop-opacity: 0;
}

.zz-4bhbml {
  stop-color: var(--svg-color--d52855, #D52855);
  stop-opacity: 0;
}

</style>
