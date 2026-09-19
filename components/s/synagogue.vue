<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ixOV1ie)" class="bnq2bsbuj"/><path fill="url(#itEpURb)" class="hg4hic0nq"/><path fill="url(#izTVGsd)" class="hg4hic0nq"/><path fill="url(#iAYBQNb)" class="hg4hic0nq"/><path fill="url(#i6AvuBb)" class="hg4hic0nq"/><g filter="url(#ip6C68b)"><path fill="url(#iAgNMbb)" class="hz2wrjh_f"/></g><g filter="url(#iCYAiJd)"><path class="p-_cz8wsd"/></g><path fill="url(#iRaILye)" class="qz0wemu0b"/><path class="spgdlzs3p"/><path fill="url(#i7EQiKq)" class="dt60qg_8h"/><path fill="url(#ik8AQvz)" class="dt60qg_8h"/><path fill="url(#icsfrtb)" class="dt60qg_8h"/><path fill="url(#ioOhBQc)" class="dt60qg_8h"/><path class="mamtbyyll"/><path fill="url(#igFrMfc)" class="zf9up5jej"/><path fill="url(#ivzs5bd)" class="zf9up5jej"/><path fill="url(#i4wL0Hd)" class="zf9up5jej"/><path fill="url(#iyo0NYb)" class="zf9up5jej"/><g filter="url(#ifbRtQb)"><path fill="url(#ibcJDDb)" class="sv--jpb3w"/></g><g filter="url(#itOk6Je)"><path fill="url(#iKYzjnP)" class="bom45ubwn"/></g><g filter="url(#i4rWVCb)"><path fill="url(#i44pOAe)" class="rrdfe3b2o"/></g><path fill="url(#iPI3Sqd)" class="mg4-90ybp"/><path fill="url(#inw8VLc)" class="mg4-90ybp"/><path fill="url(#iS09tyc)" class="petbirbfr"/><path fill="url(#iYPpzfe)" class="petbirbfr"/><g filter="url(#ijZQW5c)"><path fill="url(#iCsetCx)" class="dz6002fbo"/></g><defs><linearGradient id="itEpURb" x1="26.047" x2="6.42" y1="19.5" y2="19.5" gradientUnits="userSpaceOnUse"><stop class="esvm0qm6t"/><stop offset="1" class="oim_occdf"/></linearGradient><linearGradient id="izTVGsd" x1="5.476" x2="9.986" y1="12.9" y2="12.9" gradientUnits="userSpaceOnUse"><stop class="nzo0j8b9n"/><stop offset="1" class="ybelgrd7e"/></linearGradient><linearGradient id="iAgNMbb" x1="26.709" x2="26.709" y1="14.738" y2="29.5" gradientUnits="userSpaceOnUse"><stop offset=".787" class="ljuw6us4x"/><stop offset=".801" class="lub9e42jp"/><stop offset="1" class="lub9e42jp"/></linearGradient><linearGradient id="iRaILye" x1="20.17" x2="12.67" y1="12.125" y2="19.313" gradientUnits="userSpaceOnUse"><stop class="i9wp1k1xy"/><stop offset="1" class="tfdne74pp"/></linearGradient><linearGradient id="i7EQiKq" x1="4.545" x2="4.545" y1="13.625" y2="16.125" gradientUnits="userSpaceOnUse"><stop class="o-tc7ub_t"/><stop offset="1" class="m-uiz0b-n"/></linearGradient><linearGradient id="ik8AQvz" x1="2.045" x2="4.545" y1="22.688" y2="22.688" gradientUnits="userSpaceOnUse"><stop class="zdgtlwbjh"/><stop offset="1" class="ecmgqvbmq"/></linearGradient><linearGradient id="icsfrtb" x1="7.358" x2="4.545" y1="24.875" y2="24.875" gradientUnits="userSpaceOnUse"><stop class="qq9yfw6mo"/><stop offset="1" class="qdep263ov"/></linearGradient><linearGradient id="igFrMfc" x1="27.565" x2="27.565" y1="13.625" y2="16.125" gradientUnits="userSpaceOnUse"><stop class="o-tc7ub_t"/><stop offset="1" class="m-uiz0b-n"/></linearGradient><linearGradient id="ivzs5bd" x1="25.065" x2="27.565" y1="22.688" y2="22.688" gradientUnits="userSpaceOnUse"><stop class="lw-0amlka"/><stop offset="1" class="hmmp5o_5m"/></linearGradient><linearGradient id="i4wL0Hd" x1="30.378" x2="27.565" y1="24.875" y2="24.875" gradientUnits="userSpaceOnUse"><stop class="qq9yfw6mo"/><stop offset="1" class="qdep263ov"/></linearGradient><linearGradient id="ibcJDDb" x1="9.381" x2="12.045" y1="28.323" y2="28.323" gradientUnits="userSpaceOnUse"><stop class="q05y8-b9h"/><stop offset="1" class="j15cckxph"/></linearGradient><linearGradient id="iKYzjnP" x1="20.256" x2="22.92" y1="28.323" y2="28.323" gradientUnits="userSpaceOnUse"><stop class="q05y8-b9h"/><stop offset="1" class="j15cckxph"/></linearGradient><linearGradient id="i44pOAe" x1="13.716" x2="19.045" y1="27.485" y2="27.485" gradientUnits="userSpaceOnUse"><stop class="q05y8-b9h"/><stop offset="1" class="j15cckxph"/></linearGradient><linearGradient id="iPI3Sqd" x1="2.045" x2="5.42" y1="28.501" y2="28.501" gradientUnits="userSpaceOnUse"><stop class="vu74pcb_k"/><stop offset="1" class="orjg3ybga"/></linearGradient><linearGradient id="inw8VLc" x1="7.045" x2="6.139" y1="28.313" y2="28.313" gradientUnits="userSpaceOnUse"><stop class="h72jflitp"/><stop offset="1" class="b9-a65b9e"/></linearGradient><linearGradient id="iS09tyc" x1="25.045" x2="28.42" y1="28.501" y2="28.501" gradientUnits="userSpaceOnUse"><stop class="vu74pcb_k"/><stop offset="1" class="orjg3ybga"/></linearGradient><linearGradient id="iYPpzfe" x1="30.045" x2="29.139" y1="28.313" y2="28.313" gradientUnits="userSpaceOnUse"><stop class="h72jflitp"/><stop offset="1" class="b9-a65b9e"/></linearGradient><linearGradient id="iCsetCx" x1="25.295" x2="14.732" y1="9.625" y2="9.625" gradientUnits="userSpaceOnUse"><stop class="iqfep_wyq"/><stop offset="1" class="xndyouusz"/></linearGradient><filter id="ip6C68b" width="6.133" height="16.762" x="23.643" y="13.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7362" stdDeviation=".5"/></filter><filter id="iCYAiJd" width="5.577" height="16.432" x="2.65" y="14.278" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7362" stdDeviation=".5"/></filter><filter id="ifbRtQb" width="3" height="4.25" x="9.045" y="26" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.105882 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7362"/></filter><filter id="itOk6Je" width="3" height="4.25" x="19.92" y="26" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.105882 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7362"/></filter><filter id="i4rWVCb" width="6" height="6.25" x="13.045" y="24" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.105882 0 0 0 0 0.145098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_7362"/></filter><filter id="ijZQW5c" width="13.5" height="3.156" x="12.795" y="8.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_7362" stdDeviation=".25"/></filter><radialGradient id="ixOV1ie" cx="0" cy="0" r="1" gradientTransform="matrix(-11.7848 0 0 -15.3083 23.108 8.625)" gradientUnits="userSpaceOnUse"><stop class="kb3q5ybvn"/><stop offset=".526" class="nmxjnki_n"/><stop offset="1" class="sqfnv53sy"/></radialGradient><radialGradient id="iAYBQNb" cx="0" cy="0" r="1" gradientTransform="matrix(1.83127 0 0 2.85591 6.333 29.078)" gradientUnits="userSpaceOnUse"><stop class="ql3jz5g1t"/><stop offset="1" class="im4ypjate"/></radialGradient><radialGradient id="i6AvuBb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.12513 2.22678 0 26.622 30.608)" gradientUnits="userSpaceOnUse"><stop class="r7d3q9b4a"/><stop offset="1" class="xqdzgxbqq"/></radialGradient><radialGradient id="ioOhBQc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5625 1.1875 -1.6825 -2.2138 6.451 15.031)" gradientUnits="userSpaceOnUse"><stop class="sxcg7xbvd"/><stop offset="1" class="cb5jqrb2r"/></radialGradient><radialGradient id="iyo0NYb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.5625 1.1875 -1.6825 -2.2138 29.471 15.031)" gradientUnits="userSpaceOnUse"><stop class="sxcg7xbvd"/><stop offset="1" class="cb5jqrb2r"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:synagogue" /></template>
<style>
.b9-a65b9e {
  stop-color: var(--svg-color--5c3b59, #5C3B59);
  stop-opacity: 0;
}

.bnq2bsbuj {
  d: path("M18.595 3.44a8 8 0 0 0-2.6-.44c-.86 0-1.69.14-2.47.4c-2.91.94-5.1 3.49-5.5 6.6h15.95a8.06 8.06 0 0 0-5.38-6.56");
}

.bom45ubwn {
  d: path("M22.92 30h-3v-2.5c0-.83.67-1.5 1.5-1.5s1.5.67 1.5 1.5z");
}

.cb5jqrb2r {
  stop-color: var(--svg-color--ffdc9e, #FFDC9E);
  stop-opacity: 0;
}

.dt60qg_8h {
  d: path("M7.045 30h-5V16.5a2.5 2.5 0 0 1 5 0z");
}

.dz6002fbo {
  d: path("M23.701 9.406H13.295c.719.719 3.53.719 8.219.719c3.156 0 4.02 1.156 4.281 1.438c-.025-1.65-.812-2.157-2.094-2.157");
}

.ecmgqvbmq {
  stop-color: var(--svg-color--916e43, #916E43);
  stop-opacity: 0;
}

.esvm0qm6t {
  stop-color: var(--svg-color--ffd8a6, #FFD8A6);
}

.ft5dv1b6b {
  fill: none;
}

.h72jflitp {
  stop-color: var(--svg-color--5c3b59, #5C3B59);
}

.hg4hic0nq {
  d: path("M26.045 30h-20V11.04c0-1.13.91-2.04 2.04-2.04h15.92c1.13 0 2.04.91 2.04 2.04z");
}

.hmmp5o_5m {
  stop-color: var(--svg-color--ad7133, #AD7133);
  stop-opacity: 0;
}

.hz2wrjh_f {
  d: path("M28.775 29.5h-4.132V17.044c0-1.273.925-2.306 2.066-2.306s2.066 1.033 2.066 2.306z");
}

.i9wp1k1xy {
  stop-color: var(--svg-color--271833, #271833);
}

.im4ypjate {
  stop-color: var(--svg-color--754916, #754916);
  stop-opacity: 0;
}

.iqfep_wyq {
  stop-color: var(--svg-color--ffe7af, #FFE7AF);
}

.j15cckxph {
  stop-color: var(--svg-color--2d1939, #2D1939);
}

.kb3q5ybvn {
  stop-color: var(--svg-color--70617c, #70617C);
}

.ljuw6us4x {
  stop-color: var(--svg-color--8b4d3a, #8B4D3A);
}

.lub9e42jp {
  stop-color: var(--svg-color--684742, #684742);
}

.lw-0amlka {
  stop-color: var(--svg-color--ad7133, #AD7133);
}

.m-uiz0b-n {
  stop-color: var(--svg-color--cfab77, #CFAB77);
  stop-opacity: 0;
}

.mamtbyyll {
  fill: var(--svg-color--ecb983, #ECB983);
  d: path("M30.065 30h-5V16.5a2.5 2.5 0 0 1 5 0z");
}

.mg4-90ybp {
  d: path("M2.045 30h5v-3h-5z");
}

.nmxjnki_n {
  stop-color: var(--svg-color--564a61, #564A61);
}

.nzo0j8b9n {
  stop-color: var(--svg-color--946e3f, #946E3F);
}

.o-tc7ub_t {
  stop-color: var(--svg-color--cfab77, #CFAB77);
}

.oim_occdf {
  stop-color: var(--svg-color--d0934e, #D0934E);
}

.orjg3ybga {
  stop-color: var(--svg-color--5e4d6c, #5E4D6C);
}

.p-_cz8wsd {
  fill: var(--svg-color--c06d1d, #C06D1D);
  d: path("M7.227 29.71H3.65V17.533c0-1.245.801-2.255 1.789-2.255s1.788 1.01 1.788 2.255z");
}

.petbirbfr {
  d: path("M25.045 30h5v-3h-5z");
}

.q05y8-b9h {
  stop-color: var(--svg-color--433b4a, #433B4A);
}

.qdep263ov {
  stop-color: var(--svg-color--ffdea0, #FFDEA0);
  stop-opacity: 0;
}

.ql3jz5g1t {
  stop-color: var(--svg-color--754916, #754916);
}

.qq9yfw6mo {
  stop-color: var(--svg-color--ffdea0, #FFDEA0);
}

.qz0wemu0b {
  d: path("M21.025 15.46a4.98 4.98 0 1 1-9.96-.001a4.98 4.98 0 0 1 9.96.001m-7.25-2.02h-.85c-.12 0-.23.02-.3.14s-.03.22.03.33c.28.47.56.95.85 1.43c.04.07.05.13 0 .21c-.3.49-.59.99-.89 1.48c-.07.11-.11.22-.04.34c.07.11.18.14.3.14h1.78c.09 0 .13.03.18.1c.31.53.62 1.06.94 1.59c.16.26.38.27.54.01c.32-.53.64-1.05.95-1.58c.05-.08.1-.12.2-.12c.58.01 1.17 0 1.75 0c.25 0 .37-.22.24-.43c-.29-.49-.58-.98-.88-1.47c-.04-.07-.04-.12 0-.19c.3-.5.6-.99.9-1.49c.06-.11.1-.21.04-.33c-.07-.12-.18-.14-.3-.14h-1.77c-.1 0-.15-.03-.2-.11c-.31-.53-.62-1.05-.93-1.58c-.16-.27-.38-.27-.54 0c-.32.53-.64 1.06-.96 1.6c-.04.07-.09.1-.17.1c-.29-.03-.58-.03-.87-.03m2.15-1.01l-.52.9c-.02.04.01.09.05.09h1.04c.05 0 .08-.05.05-.09l-.52-.9c-.02-.04-.08-.04-.1 0m.12 6.07l.52-.9c.02-.04-.01-.09-.05-.09h-1.04c-.05 0-.08.05-.05.09l.52.9c.01.04.07.04.1 0m-2.8-4.49l.53.9c.02.04.09.04.11 0l.52-.91c.02-.04-.01-.09-.06-.09l-1.04.01c-.06 0-.09.05-.06.09m5.5 2.86l-.53-.9c-.02-.04-.09-.04-.11 0l-.52.91c-.02.04.01.09.06.09l1.04-.01c.05 0 .08-.05.06-.09m-5.45.08l1.04-.02c.05 0 .08-.05.05-.1l-.54-.9c-.03-.04-.09-.04-.11 0l-.51.91c-.01.06.02.11.07.11m5.42-3.02l-1.04.02c-.05 0-.08.05-.05.1l.54.9c.03.04.09.04.11 0l.51-.91c.01-.06-.02-.12-.07-.11m-3.58.05c-.09 0-.14.02-.18.1c-.25.42-.5.84-.76 1.26c-.05.08-.05.13 0 .21c.26.43.52.87.77 1.31c.04.07.08.1.17.1h1.73c.07 0 .12-.02.16-.09c.25-.43.51-.86.77-1.28c.04-.07.04-.12 0-.18c-.27-.44-.53-.89-.79-1.33c-.04-.07-.09-.09-.16-.09h-.86c-.29-.01-.57-.01-.85-.01");
}

.r7d3q9b4a {
  stop-color: var(--svg-color--6a4943, #6A4943);
}

.rrdfe3b2o {
  d: path("M19.045 30h-6v-3c0-1.66 1.34-3 3-3s3 1.34 3 3z");
}

.spgdlzs3p {
  fill: var(--svg-color--ecb983, #ECB983);
  d: path("M7.045 30h-5V16.5a2.5 2.5 0 0 1 5 0z");
}

.sqfnv53sy {
  stop-color: var(--svg-color--2f2b32, #2F2B32);
}

.sv--jpb3w {
  d: path("M12.045 30h-3v-2.5c0-.83.67-1.5 1.5-1.5s1.5.67 1.5 1.5z");
}

.sxcg7xbvd {
  stop-color: var(--svg-color--ffdc9e, #FFDC9E);
}

.tfdne74pp {
  stop-color: var(--svg-color--272229, #272229);
}

.vu74pcb_k {
  stop-color: var(--svg-color--2c2830, #2C2830);
}

.xndyouusz {
  stop-color: var(--svg-color--ffe7af, #FFE7AF);
  stop-opacity: 0;
}

.xqdzgxbqq {
  stop-color: var(--svg-color--6a4943, #6A4943);
  stop-opacity: 0;
}

.ybelgrd7e {
  stop-color: var(--svg-color--946e3f, #946E3F);
  stop-opacity: 0;
}

.zdgtlwbjh {
  stop-color: var(--svg-color--916e43, #916E43);
}

.zf9up5jej {
  d: path("M30.065 30h-5V16.5a2.5 2.5 0 0 1 5 0z");
}

</style>
