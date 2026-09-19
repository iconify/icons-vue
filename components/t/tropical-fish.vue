<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#i6ByFUc)" class="fx4ktu0uo"/><circle fill="url(#i1KDyCd)" class="fx4ktu0uo"/><circle fill="url(#iSqxzye)" class="mg03avwsp"/><path fill="url(#iRuERfe)" class="sfzax6lde"/><path fill="url(#ikBTsgb)" class="sfzax6lde"/><path fill="url(#iCvSUdb)" class="sfzax6lde"/><path fill="url(#iUN08Hc)" class="sfzax6lde"/><path fill="url(#iX5yq3q)" class="sfzax6lde"/><path fill="url(#iZ32fWB)" class="sfzax6lde"/><path fill="url(#i2igOPe)" class="sfzax6lde"/><path fill="url(#iCaqtbf)" class="sfzax6lde"/><circle fill="url(#ipnVxWb)" class="zlzhoibkd"/><circle fill="url(#i37Kgxd)" class="zlzhoibkd"/><circle fill="url(#ioTmlZc)" class="zlzhoibkd"/><circle fill="url(#iLuvhCe)" class="zlzhoibkd"/><path fill="url(#iMq1ple)" class="ei_rq464g"/><g filter="url(#ivt1EEe)"><path class="sgux7bc4o"/></g><path fill="url(#ilL7lje)" class="xnha08bsh"/><path fill="url(#iS3TzOW)" class="xnha08bsh"/><path fill="url(#ieKJclc)" class="xnha08bsh"/><circle fill="url(#ihqDajb)" class="a4ug1-2-k"/><circle fill="url(#idpvfDc)" class="a4ug1-2-k"/><circle fill="url(#ibvmkkc)" class="a4ug1-2-k"/><path fill="url(#iVUr2de)" class="k6htmebyc"/><path fill="url(#ihEYbru)" class="k6htmebyc"/><path fill="url(#iY0ZHuc)" class="k6htmebyc"/><defs><radialGradient id="i6ByFUc" cx="0" cy="0" r="1" gradientTransform="matrix(1.3125 -.53906 .83075 2.02268 2 20.484)" gradientUnits="userSpaceOnUse"><stop class="acv6znvnx"/><stop offset="1" class="dgt5kebrd"/></radialGradient><radialGradient id="i1KDyCd" cx="0" cy="0" r="1" gradientTransform="rotate(98.219 -6.59 10.698)scale(.71042 .794)" gradientUnits="userSpaceOnUse"><stop class="cr-m4mbyj"/><stop offset="1" class="q6211-k4g"/></radialGradient><radialGradient id="iSqxzye" cx="0" cy="0" r="1" gradientTransform="matrix(1.625 0 0 2.50428 1.875 17.945)" gradientUnits="userSpaceOnUse"><stop class="acv6znvnx"/><stop offset="1" class="dgt5kebrd"/></radialGradient><radialGradient id="ikBTsgb" cx="0" cy="0" r="1" gradientTransform="matrix(8.0625 -3.625 5.13835 11.4284 17.188 31.625)" gradientUnits="userSpaceOnUse"><stop class="w7y026zsw"/><stop offset="1" class="wgdx8sbwm"/></radialGradient><radialGradient id="iCvSUdb" cx="0" cy="0" r="1" gradientTransform="rotate(46.65 -12.942 36.264)scale(5.37182 7.61442)" gradientUnits="userSpaceOnUse"><stop class="w7y026zsw"/><stop offset="1" class="wgdx8sbwm"/></radialGradient><radialGradient id="iX5yq3q" cx="0" cy="0" r="1" gradientTransform="matrix(16.7498 18.68764 -12.28497 11.01107 9.25 10.625)" gradientUnits="userSpaceOnUse"><stop offset=".943" class="wgdx8sbwm"/><stop offset="1" class="w7y026zsw"/></radialGradient><radialGradient id="iZ32fWB" cx="0" cy="0" r="1" gradientTransform="rotate(143.673 11.127 8.392)scale(3.95643 5.87059)" gradientUnits="userSpaceOnUse"><stop class="digbd6blf"/><stop offset=".654" class="z3ta75bti"/></radialGradient><radialGradient id="i2igOPe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.0625 11.8125 0 27.125 14.938)" gradientUnits="userSpaceOnUse"><stop class="digbd6blf"/><stop offset="1" class="z3ta75bti"/></radialGradient><radialGradient id="ipnVxWb" cx="0" cy="0" r="1" gradientTransform="matrix(-10.49993 18.125 -19.41091 -11.24487 22.813 9.75)" gradientUnits="userSpaceOnUse"><stop class="dks77wb2a"/><stop offset="1" class="u4q3zwskh"/></radialGradient><radialGradient id="i37Kgxd" cx="0" cy="0" r="1" gradientTransform="matrix(0 23.0625 -17.9752 0 14.5 9.063)" gradientUnits="userSpaceOnUse"><stop offset=".786" class="cxg8wbbam"/><stop offset=".929" class="jxrlegb5g"/></radialGradient><radialGradient id="ioTmlZc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.6875 0 0 -6.17092 28.5 18.813)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="jxrlegb5g"/><stop offset="1" class="cxg8wbbam"/></radialGradient><radialGradient id="iLuvhCe" cx="0" cy="0" r="1" gradientTransform="matrix(2.37499 2.81251 -7.52137 6.35133 7.875 8.125)" gradientUnits="userSpaceOnUse"><stop class="blhqdzm_o"/><stop offset="1" class="frf1pcc2i"/></radialGradient><radialGradient id="iMq1ple" cx="0" cy="0" r="1" gradientTransform="matrix(23.875 0 0 34.7797 .625 18.467)" gradientUnits="userSpaceOnUse"><stop offset=".065" class="rgrsk5qhc"/><stop offset=".262" class="k63cwfost"/></radialGradient><radialGradient id="ieKJclc" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.5 -.71873 0 18 15.844)" gradientUnits="userSpaceOnUse"><stop class="rzcfekbdm"/><stop offset="1" class="f17588j8v"/></radialGradient><radialGradient id="ihqDajb" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 .5625 -.5015 -.3622 7.57 16.23)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="idpvfDc" cx="0" cy="0" r="1" gradientTransform="rotate(137.643 .653 9.607)scale(.35946 .31624)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="iVUr2de" cx="0" cy="0" r="1" gradientTransform="matrix(-4.375 0 0 -8.85937 30.375 18.89)" gradientUnits="userSpaceOnUse"><stop offset=".329" class="etd7ppb9i"/><stop offset="1" class="vnaryxbfl"/></radialGradient><radialGradient id="ihEYbru" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.59375 -1.28023 0 30.063 17.094)" gradientUnits="userSpaceOnUse"><stop class="fa0cecb6a"/><stop offset="1" class="pxmux-03k"/></radialGradient><radialGradient id="iY0ZHuc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.375 0 0 -5.125 31.188 18.89)" gradientUnits="userSpaceOnUse"><stop offset=".892" class="iwgaflb0k"/><stop offset="1" class="uwb9lojpt"/></radialGradient><linearGradient id="iRuERfe" x1="30.813" x2="20.5" y1="17.375" y2="17.375" gradientUnits="userSpaceOnUse"><stop class="cac4eqbig"/><stop offset="1" class="p-g9s0bcq"/></linearGradient><linearGradient id="iUN08Hc" x1="26" x2="26" y1="30.656" y2="29.438" gradientUnits="userSpaceOnUse"><stop offset=".118" class="w7y026zsw"/><stop offset="1" class="wgdx8sbwm"/></linearGradient><linearGradient id="iCaqtbf" x1="19.094" x2="19.219" y1="6.313" y2="7.625" gradientUnits="userSpaceOnUse"><stop class="f9dfo-hco"/><stop offset="1" class="b1cjxz-kz"/></linearGradient><linearGradient id="ilL7lje" x1="18" x2="13.813" y1="17.875" y2="17.875" gradientUnits="userSpaceOnUse"><stop class="rzcfekbdm"/><stop offset="1" class="khlpk0gto"/></linearGradient><linearGradient id="iS3TzOW" x1="15.752" x2="14.281" y1="19.594" y2="20.625" gradientUnits="userSpaceOnUse"><stop class="mzmj0pqtf"/><stop offset="1" class="khlpk0gto"/></linearGradient><linearGradient id="ibvmkkc" x1="7.324" x2="6.98" y1="15.998" y2="15.779" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><filter id="ivt1EEe" width="5.995" height="8.777" x="12.364" y="14.392" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5989" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:tropical-fish" /></template>
<style>
.a4ug1-2-k {
  cx: 7.422px;
  cy: 16.391px;
  r: 0.5px;
}

.acv6znvnx {
  stop-color: var(--svg-color--6d5a93, #6D5A93);
}

.b1cjxz-kz {
  stop-color: var(--svg-color--ffb941, #FFB941);
  stop-opacity: 0;
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.blhqdzm_o {
  stop-color: var(--svg-color--65afe3, #65AFE3);
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.cac4eqbig {
  stop-color: var(--svg-color--ffe359, #FFE359);
}

.cr-m4mbyj {
  stop-color: var(--svg-color--442e79, #442E79);
}

.cxg8wbbam {
  stop-color: var(--svg-color--5a67ff, #5A67FF);
  stop-opacity: 0;
}

.dgt5kebrd {
  stop-color: var(--svg-color--5f498c, #5F498C);
}

.digbd6blf {
  stop-color: var(--svg-color--ffe65e, #FFE65E);
}

.dks77wb2a {
  stop-color: var(--svg-color--76cdff, #76CDFF);
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.ei_rq464g {
  d: path("M6.7 10.05a10.8 10.8 0 0 1 3.988 8.388c0 3.417-1.586 6.464-4.06 8.445A11.47 11.47 0 0 1 3 18.5a11.47 11.47 0 0 1 3.7-8.45");
}

.etd7ppb9i {
  stop-color: var(--svg-color--ffc256, #FFC256);
}

.f17588j8v {
  stop-color: var(--svg-color--ffd65c, #FFD65C);
  stop-opacity: 0;
}

.f9dfo-hco {
  stop-color: var(--svg-color--ffb941, #FFB941);
}

.fa0cecb6a {
  stop-color: var(--svg-color--ffd661, #FFD661);
}

.frf1pcc2i {
  stop-color: var(--svg-color--65afe3, #65AFE3);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fx4ktu0uo {
  cx: 3.055px;
  cy: 19.945px;
  r: 1.055px;
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.iwgaflb0k {
  stop-color: var(--svg-color--f37539, #F37539);
  stop-opacity: 0;
}

.jxrlegb5g {
  stop-color: var(--svg-color--5a67ff, #5A67FF);
}

.k63cwfost {
  stop-color: var(--svg-color--6f53a3, #6F53A3);
}

.k6htmebyc {
  d: path("M30.063 15.955c0-.672-.766-1.476-1.82-.956A4.5 4.5 0 0 0 26 18.893c0 1.662.901 3.114 2.242 3.893c.759.441 1.82-.073 1.82-.83z");
}

.khlpk0gto {
  stop-color: var(--svg-color--ff8c42, #FF8C42);
}

.mg03avwsp {
  cx: 3.055px;
  cy: 17.945px;
  r: 1.055px;
}

.mzmj0pqtf {
  stop-color: var(--svg-color--ff8c42, #FF8C42);
  stop-opacity: 0;
}

.p-g9s0bcq {
  stop-color: var(--svg-color--ffbe3e, #FFBE3E);
}

.pxmux-03k {
  stop-color: var(--svg-color--ffd661, #FFD661);
  stop-opacity: 0;
}

.q6211-k4g {
  stop-color: var(--svg-color--442e79, #442E79);
  stop-opacity: 0;
}

.rgrsk5qhc {
  stop-color: var(--svg-color--80739f, #80739F);
}

.rzcfekbdm {
  stop-color: var(--svg-color--ffd65c, #FFD65C);
}

.sfzax6lde {
  d: path("M14.375 7H23a3 3 0 0 1 3 3v17a3 3 0 0 1-3 3h-8.625z");
}

.sgux7bc4o {
  fill: var(--svg-color--4d82fd, #4D82FD);
  d: path("M17.61 21.717v-5.873a.7.7 0 0 0-1.174-.516l-2.998 2.753a1 1 0 0 0 .01 1.483l2.995 2.675a.7.7 0 0 0 1.166-.522");
}

.u4q3zwskh {
  stop-color: var(--svg-color--5181ff, #5181FF);
}

.uwb9lojpt {
  stop-color: var(--svg-color--f37539, #F37539);
}

.vnaryxbfl {
  stop-color: var(--svg-color--ff8646, #FF8646);
}

.w7y026zsw {
  stop-color: var(--svg-color--ff835d, #FF835D);
}

.wgdx8sbwm {
  stop-color: var(--svg-color--ff835d, #FF835D);
  stop-opacity: 0;
}

.xnha08bsh {
  d: path("M18 21.452v-5.874a.7.7 0 0 0-1.174-.516l-2.997 2.754a1 1 0 0 0 .01 1.482l2.995 2.676A.7.7 0 0 0 18 21.452");
}

.z3ta75bti {
  stop-color: var(--svg-color--ffe65e, #FFE65E);
  stop-opacity: 0;
}

.zlzhoibkd {
  cx: 14.5px;
  cy: 18.5px;
  r: 11.5px;
}

</style>
