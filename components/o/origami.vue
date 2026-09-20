<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><radialGradient id="SVGO7u3OVxo" cx="26.196%" cy="9.36%" r="105.51%" fx="26.196%" fy="9.36%" gradientTransform="matrix(.52886 .8454 -.8487 .5268 .203 -.177)"><stop offset="0%" class="r6491-b-q"/><stop offset="100%" class="j3p6wz2ax"/></radialGradient><radialGradient id="SVGMqAlqdXv" cx="-15.313%" cy="-13.633%" r="181.001%" fx="-15.313%" fy="-13.633%" gradientTransform="matrix(.9647 .23955 -.26337 .87744 -.041 .02)"><stop offset="0%" class="vc--wpv5i"/><stop offset="100%" class="s4fzwtfrp"/></radialGradient><radialGradient id="SVGeoJZybyG" cx="69.551%" cy="-14.976%" r="205.05%" fx="69.551%" fy="-14.976%" gradientTransform="matrix(-.45604 .51346 -.88996 -.26311 .88 -.546)"><stop offset="0%" class="vc--wpv5i"/><stop offset="100%" class="b2u37pb-f"/></radialGradient><radialGradient id="SVGbLM63sVI" cx="40.071%" cy="19.981%" r="98.92%" fx="40.071%" fy="19.981%" gradientTransform="matrix(.5143 .57232 -.8576 .34322 .366 -.098)"><stop offset="0%" class="vc--wpv5i"/><stop offset="100%" class="nk3q848ho"/></radialGradient><path id="SVGCeJmwdht" class="jka-c_b6l"/></defs><path fill="url(#SVGO7u3OVxo)" class="jka-c_b6l"/><mask id="SVG8oxFqeJa" class="n1mjunbsu"><use href="#SVGCeJmwdht"/></mask><path mask="url(#SVG8oxFqeJa)" class="g-js_lm2u"/><path mask="url(#SVG8oxFqeJa)" class="ufm-kzbdr"/><path fill="url(#SVGMqAlqdXv)" mask="url(#SVG8oxFqeJa)" class="g3t4mwbhy"/><path fill="url(#SVGeoJZybyG)" mask="url(#SVG8oxFqeJa)" class="pwnc0vb0o"/><path mask="url(#SVG8oxFqeJa)" class="n-juof00b"/><path fill="url(#SVGbLM63sVI)" mask="url(#SVG8oxFqeJa)" class="m5gtc8bbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:origami" /></template>
<style>
.b2u37pb-f {
  stop-color: var(--svg-color--7ac2ff, #7ac2ff);
}

.g-js_lm2u {
  fill: var(--svg-color--e8f5ff, #e8f5ff);
  d: path("m136.982 58.764l57.763 61.091l-49.756-11.637z");
}

.g3t4mwbhy {
  d: path("M21.364 140.8L-94 13.964L6.172 35.907z");
}

.j3p6wz2ax {
  stop-color: var(--svg-color--046cf4, #046cf4);
}

.jka-c_b6l {
  d: path("M127.755 256c70.416 0 127.5-57.307 127.5-128c0-70.692-57.084-128-127.5-128C57.338 0 .255 57.308.255 128s57.083 128 127.5 128");
}

.m5gtc8bbx {
  d: path("m56.725 335.585l-97.279-226.846L4.621 35.491l155.091 161.683z");
}

.n-juof00b {
  fill: var(--svg-color--4492d2, #4492d2);
  d: path("m89.116 116.735l34.936 43.464l-37.688-40.054z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.nk3q848ho {
  stop-color: var(--svg-color--cbe7ff, #cbe7ff);
}

.pwnc0vb0o {
  d: path("M159.488 196.997L136.503 58.764L79.735 127.88z");
}

.r6491-b-q {
  stop-color: var(--svg-color--51c3f7, #51c3f7);
}

.s4fzwtfrp {
  stop-color: var(--svg-color--5cb5ff, #5cb5ff);
}

.ufm-kzbdr {
  fill: var(--svg-color--64a4d8, #64a4d8);
  d: path("m138.379 67.243l14.525 42.993l-8.211-2.018z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

</style>
