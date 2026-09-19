<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#i3ZRItb)" class="rdt1-bbby"/><path fill="url(#iE8QcEd)" class="rdt1-bbby"/><path fill="url(#ivEnSkc)" class="rdt1-bbby"/><path fill="url(#iHBKMWi)" class="fxarinb1j"/><path fill="url(#iKP1mWb)" class="rdt1-bbby"/><path fill="url(#ipSnfmL)" class="rdt1-bbby"/><path fill="url(#ihEkwIW)" class="rdt1-bbby"/><path fill="url(#iHqW0db)" class="rdt1-bbby"/><path stroke="url(#iMSL6Fc)" class="nls7ddbof"/><g filter="url(#ijh9jFd)"><path fill="url(#iI1bTvc)" class="l5cc3tuxx"/></g><path fill="url(#iO3OHpS)" clip-rule="evenodd" class="zl7g57bbr"/><path fill="url(#iDOVAIr)" clip-rule="evenodd" class="zl7g57bbr"/><path fill="url(#iSdwZOd)" clip-rule="evenodd" class="zl7g57bbr"/><path fill="url(#iThBxwd)" class="t_uvmtf5c"/><path fill="url(#i5OlYpc)" class="t_uvmtf5c"/><path fill="url(#iIBLlFb)" class="t_uvmtf5c"/><path fill="url(#iSFVn2d)" class="t_uvmtf5c"/><ellipse fill="url(#ixvZgkb)" transform="rotate(-25.883 11.138 9.143)" class="z95w7wbuk"/><path fill="url(#iHUusad)" class="dqyk6wb1j"/><path fill="url(#ifN9D9i)" class="dqyk6wb1j"/><path fill="url(#iKZgldb)" class="dqyk6wb1j"/><path fill="url(#imLmlRd)" class="dqyk6wb1j"/><ellipse fill="url(#ibn3pub)" transform="rotate(-25.883 27.172 9.143)" class="uobc7cbuk"/><defs><radialGradient id="i3ZRItb" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.785 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iHBKMWi" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 17.999 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="iKP1mWb" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.433)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ihEkwIW" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.499 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="iHqW0db" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.172)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="iMSL6Fc" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.9375 -16.8684 0 15.999 17.815)" gradientUnits="userSpaceOnUse"><stop offset=".146" class="m8pwa1xcy"/><stop offset=".276" class="gvfj_gdms"/><stop offset=".343" class="gw349qs5e"/></radialGradient><radialGradient id="iO3OHpS" cx="0" cy="0" r="1" gradientTransform="matrix(2.3751 12.0625 -24.99626 4.92174 21.123 5.752)" gradientUnits="userSpaceOnUse"><stop class="ur1--u96b"/><stop offset="1" class="bdzagfbmn"/></radialGradient><radialGradient id="iDOVAIr" cx="0" cy="0" r="1" gradientTransform="matrix(1.1405 5.39508 -6.06084 1.28124 23.89 11.013)" gradientUnits="userSpaceOnUse"><stop offset=".776" class="khhqemb4t"/><stop offset=".938" class="d_60mubre"/></radialGradient><radialGradient id="iSdwZOd" cx="0" cy="0" r="1" gradientTransform="rotate(-122.735 13.667 -.97)scale(4.68093 3.43606)" gradientUnits="userSpaceOnUse"><stop offset=".769" class="obwsb4bxf"/><stop offset="1" class="hv7_4hbcv"/></radialGradient><radialGradient id="iThBxwd" cx="0" cy="0" r="1" gradientTransform="rotate(121.845 2.823 7.504)scale(5.92276 6.72838)" gradientUnits="userSpaceOnUse"><stop class="qizne2b8s"/><stop offset="1" class="e0q4-gbmp"/></radialGradient><radialGradient id="i5OlYpc" cx="0" cy="0" r="1" gradientTransform="matrix(.375 7.5 -11.13699 .55685 9.468 9.221)" gradientUnits="userSpaceOnUse"><stop offset=".647" class="x9ntrxb-v"/><stop offset="1" class="q626yqbzd"/></radialGradient><radialGradient id="iIBLlFb" cx="0" cy="0" r="1" gradientTransform="rotate(-99.513 10.993 5.1)scale(11.5336 11.4216)" gradientUnits="userSpaceOnUse"><stop offset=".859" class="cn0qvxbwv"/><stop offset="1" class="wvkym0buw"/></radialGradient><radialGradient id="iSFVn2d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.62498 7.5 -7.03889 -1.52508 8.75 8.471)" gradientUnits="userSpaceOnUse"><stop offset=".872" class="cn0qvxbwv"/><stop offset="1" class="kaet8obni"/></radialGradient><radialGradient id="iHUusad" cx="0" cy="0" r="1" gradientTransform="rotate(121.289 9.893 11.263)scale(6.61888 9.94211)" gradientUnits="userSpaceOnUse"><stop class="qizne2b8s"/><stop offset="1" class="e0q4-gbmp"/></radialGradient><radialGradient id="ifN9D9i" cx="0" cy="0" r="1" gradientTransform="matrix(-.375 7.5 -11.13699 -.55685 22.53 9.221)" gradientUnits="userSpaceOnUse"><stop offset=".647" class="x9ntrxb-v"/><stop offset="1" class="q626yqbzd"/></radialGradient><radialGradient id="iKZgldb" cx="0" cy="0" r="1" gradientTransform="matrix(2.2051 -10.0313 9.93382 2.18367 23.919 15.44)" gradientUnits="userSpaceOnUse"><stop offset=".859" class="cn0qvxbwv"/><stop offset="1" class="wvkym0buw"/></radialGradient><radialGradient id="imLmlRd" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 7.5 -7.03889 1.52509 23.249 8.471)" gradientUnits="userSpaceOnUse"><stop offset=".872" class="cn0qvxbwv"/><stop offset="1" class="kaet8obni"/></radialGradient><linearGradient id="iI1bTvc" x1="22.686" x2="8.624" y1="12.014" y2="17.377" gradientUnits="userSpaceOnUse"><stop class="k16vjtfqs"/><stop offset="1" class="h8fwzvbad"/></linearGradient><linearGradient id="ixvZgkb" x1="11.792" x2="10.398" y1="7.795" y2="10.957" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset=".974" class="stui2mbih"/></linearGradient><linearGradient id="ibn3pub" x1="27.826" x2="26.433" y1="7.795" y2="10.957" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset=".974" class="stui2mbih"/></linearGradient><filter id="ijh9jFd" width="28.572" height="14.222" x="2.348" y="4.903" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_6813_5229" stdDeviation=".6"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:smiling-face-with-sunglasses" /></template>
<style>
.bdzagfbmn {
  stop-color: var(--svg-color--5c3085, #5C3085);
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.cn0qvxbwv {
  stop-color: var(--svg-color--2e1d57, #2E1D57);
  stop-opacity: 0;
}

.d_60mubre {
  stop-color: var(--svg-color--77579c, #77579C);
  stop-opacity: 0;
}

.dqyk6wb1j {
  d: path("M28.17 6.683a4.5 4.5 0 0 0-2.163-.58h-.311c-1.393 0-3.675-.002-4.53.157c-.828.155-1.096.267-1.21.316a2.89 2.89 0 0 0-1.832 2.692v.031c-.18 4.211 3.027 6.749 6.027 6.468q.396-.053.784-.149c3.652-.904 4.856-4.088 4.783-6.475h-.002c-.04-1.068-.614-1.899-1.546-2.46");
}

.e0q4-gbmp {
  stop-color: var(--svg-color--361c5d, #361C5D);
}

.fqgjm_v0b {
  stop-color: var(--svg-color--715b32, #715B32);
}

.ft5dv1b6b {
  fill: none;
}

.fxarinb1j {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.998 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.664 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.g4z4xncfo {
  stop-color: var(--svg-color--ffb849, #FFB849);
}

.gvfj_gdms {
  stop-color: var(--svg-color--503a4a, #503A4A);
}

.gw349qs5e {
  stop-color: var(--svg-color--4b2744, #4B2744);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.h8fwzvbad {
  stop-color: var(--svg-color--d07000, #D07000);
}

.hv7_4hbcv {
  stop-color: var(--svg-color--534687, #534687);
  stop-opacity: 0;
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k16vjtfqs {
  stop-color: var(--svg-color--e78f00, #E78F00);
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.kaet8obni {
  stop-color: var(--svg-color--20143d, #20143D);
  stop-opacity: 0.6;
}

.khhqemb4t {
  stop-color: var(--svg-color--77579c, #77579C);
}

.l5cc3tuxx {
  d: path("M3.548 14.596c.22.906.848 2.628 2.855 3.125a9 9 0 0 0 .93.173c4.306.404 7.152-3.235 7.29-7.194c.012-.329.265-.606.593-.61q.263-.004.543 0c.327.007.578.283.59.61c.14 3.959 2.983 7.598 7.29 7.194l.042-.005q.442-.058.888-.168c2.659-.659 4.308-2.406 5.152-4.28a15.4 15.4 0 0 0-.56-2.298c-.252 2.203-1.431 2.481-4.592 3.264c-.26.064-1.149.684-1.414.72c-3 .281-3.844-1.686-5.544-4.828v-.074q.165.021.332.047l.274-1.776a2.9 2.9 0 0 1 1.226-.92c.114-.049.382-.161 1.21-.316c.856-.16 3.137-.157 4.53-.156h.31c.736 0 1.404.213 1.835.409q-.528-.73-1.163-1.372a6 6 0 0 0-.671-.037h-.315c-.694 0-1.622-.002-2.485.018c-.836.019-2.075.072-2.596.17c-.86.16-1.208.288-1.409.374a3.64 3.64 0 0 0-1.402.988c-.247.282-.596.47-.97.453c-.6-.026-1.164-.023-1.67-.003c-.371.015-.718-.172-.963-.452a3.65 3.65 0 0 0-1.401-.986c-.201-.086-.548-.214-1.41-.375c-.52-.097-1.759-.15-2.595-.17c-.863-.019-1.791-.018-2.485-.017H5.78q-.497.498-.93 1.05a4 4 0 0 1 .628-.05h.311c1.393-.001 3.674-.003 4.53.156c.828.155 1.095.267 1.21.316c.47.185.879.49 1.19.876l.343 1.814q.122-.022.299-.048v.081c.18 4.211-3.027 6.749-6.027 6.468a8 8 0 0 1-.784-.149c-2.299-.569-2.132-2.257-2.783-3.866c-.115.591-.166 1.226-.219 1.844");
}

.m8pwa1xcy {
  stop-color: var(--svg-color--2e1529, #2E1529);
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.nls7ddbof {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11.327 19s1.402 2 4.672 2s4.672-2 4.672-2");
}

.obwsb4bxf {
  stop-color: var(--svg-color--4e3d92, #4E3D92);
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.q626yqbzd {
  stop-color: var(--svg-color--5b2b84, #5B2B84);
}

.qizne2b8s {
  stop-color: var(--svg-color--4c3d70, #4C3D70);
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rdt1-bbby {
  d: path("M15.998 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.664 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t_uvmtf5c {
  d: path("M3.828 6.683a4.5 4.5 0 0 1 2.163-.58h.311c1.393 0 3.674-.002 4.53.157c.828.155 1.095.267 1.21.316a2.89 2.89 0 0 1 1.832 2.692v.031c.18 4.211-3.027 6.749-6.027 6.468a8 8 0 0 1-.784-.149C3.41 14.714 2.207 11.53 2.28 9.143h.002c.04-1.068.614-1.899 1.546-2.46");
}

.uobc7cbuk {
  cx: 27.172px;
  cy: 9.143px;
  rx: 1.494px;
  ry: 1.879px;
}

.ur1--u96b {
  stop-color: var(--svg-color--5f5b9b, #5F5B9B);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.wvkym0buw {
  stop-color: var(--svg-color--20143d, #20143D);
}

.x9ntrxb-v {
  stop-color: var(--svg-color--5b2b84, #5B2B84);
  stop-opacity: 0;
}

.z95w7wbuk {
  cx: 11.138px;
  cy: 9.143px;
  rx: 1.494px;
  ry: 1.879px;
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

.zl7g57bbr {
  fill-rule: evenodd;
  d: path("M12.796 5.666c.552.22 1.026.56 1.4.986c.246.28.593.467.965.452c.505-.02 1.07-.023 1.67.003c.373.017.722-.171.968-.453c.375-.428.85-.767 1.403-.988c.201-.086.548-.214 1.41-.375c.52-.097 1.759-.15 2.595-.17c.863-.019 1.791-.018 2.485-.017h.315c1.189 0 2.362.376 2.828.656c1.047.531 2.015 1.547 2.085 3.295q.005.039.005.079c.083 2.688-1.587 6.533-5.843 7.587a9 9 0 0 1-.93.173c-4.307.404-7.15-3.235-7.29-7.194c-.012-.327-.263-.603-.59-.61a18 18 0 0 0-.543 0c-.328.004-.58.281-.592.61c-.14 3.959-2.985 7.598-7.29 7.194l-.043-.005a9 9 0 0 1-.888-.168C2.659 15.667.99 11.822 1.072 9.134q.001-.04.006-.08c.07-1.747 1.038-2.763 2.085-3.294c.465-.28 1.639-.656 2.828-.656h.315c.694 0 1.622-.002 2.485.018c.836.019 2.075.072 2.596.17c.86.16 1.208.288 1.409.374M2.489 8.165c.25-.609.714-1.106 1.339-1.482a4.5 4.5 0 0 1 2.163-.58h.311c1.393 0 3.674-.002 4.53.157c.828.155 1.095.267 1.21.316c.47.185.879.49 1.19.876l.343 1.814q.123-.023.299-.048V9.3c.18 4.211-3.027 6.749-6.027 6.468a8 8 0 0 1-.785-.149c-3.16-.782-4.487-3.272-4.739-5.475a7 7 0 0 1-.043-.99v-.01h.002v-.01a2.8 2.8 0 0 1 .207-.968m15.635 1.06V9.3c-.18 4.211 3.027 6.749 6.027 6.468q.396-.053.784-.149c3.16-.782 4.488-3.272 4.74-5.475q.058-.511.043-.99v-.01h-.002v-.01a2.8 2.8 0 0 0-.208-.968c-.25-.609-.713-1.106-1.338-1.482a4.5 4.5 0 0 0-2.163-.58h-.311c-1.393 0-3.675-.002-4.53.157c-.828.155-1.096.267-1.21.316c-.488.192-.91.513-1.226.92l-.274 1.776z");
}

</style>
