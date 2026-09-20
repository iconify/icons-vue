<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q6l9qkbgm"/><path fill="url(#SVG3pOSdcVV)" class="a4z6c7tes"/><path stroke="url(#SVGRPiaVcyk)" class="fh5n9rbth"/><path clip-rule="evenodd" class="ocknqac6k"/><path class="zjs3f3-ff"/><defs><radialGradient id="SVG3pOSdcVV" cx="0" cy="0" r="1" gradientTransform="matrix(0 18.9762 -13.3573 0 12.018 5.626)" gradientUnits="userSpaceOnUse"><stop offset=".031" class="t_s4jjcam"/><stop offset="1" class="a5wymhb4q"/></radialGradient><linearGradient id="SVGRPiaVcyk" x1="11.999" x2="11.999" y1="2.834" y2="21.164" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="ilc7r0byc"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:usde" /></template>
<style>
.a4z6c7tes {
  fill-opacity: var(--svg-fill-opacity--0-7, 0.7);
  d: path("M12 3a9 9 0 0 0-9 9a9 9 0 0 0 9 9a9 9 0 0 0 9-9a9 9 0 0 0-9-9");
}

.a5wymhb4q {
  stop-color: var(--svg-color--1c1c1c, #1c1c1c);
}

.fh5n9rbth {
  stroke-width: var(--svg-stroke-width--0-33px, 0.33px);
  d: path("M12 3a9 9 0 0 0-9 9a9 9 0 0 0 9 9a9 9 0 0 0 9-9a9 9 0 0 0-9-9Z");
}

.ft5dv1b6b {
  fill: none;
}

.ilc7r0byc {
  stop-color: var(--svg-color--111, #111);
}

.ocknqac6k {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M10.56 4.592a7.54 7.54 0 0 0-6.102 7.399a7.54 7.54 0 0 0 6.102 7.398v-.706a6.846 6.846 0 0 1 0-13.385zm2.88.711v-.706a7.534 7.534 0 0 1 0 14.788v-.707a6.846 6.846 0 0 0 5.395-6.687a6.846 6.846 0 0 0-5.395-6.688");
}

.q6l9qkbgm {
  fill: var(--svg-color--111, #111);
  stroke: var(--svg-color--111, #111);
  stroke-width: var(--svg-stroke-width--0-326px, 0.326px);
  d: path("M12 3.162a8.84 8.84 0 1 1 0 17.676a8.84 8.84 0 0 1 0-17.677Z");
}

.t_s4jjcam {
  stop-color: var(--svg-color--3a3a3a, #3a3a3a);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.zjs3f3-ff {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.066 11.742c.577.11 1.02.323 1.338.632q.477.458.476 1.172v.753q-.001.858-.619 1.384c-.41.346-.955.517-1.624.517h-.231v1.195h-.794V16.2h-.244a2.3 2.3 0 0 1-1.173-.295a2.1 2.1 0 0 1-.794-.845a2.8 2.8 0 0 1-.276-1.27h.793q.001.73.397 1.187c.273.295.633.448 1.071.448h1.228q.65 0 1.052-.305q.396-.317.397-.821v-.753a.9.9 0 0 0-.3-.683q-.29-.284-.794-.364l-1.99-.351c-.558-.102-.996-.314-1.305-.633q-.466-.483-.466-1.209v-.632q0-.857.595-1.362q.61-.518 1.601-.517h.199V6.6h.794v1.195h.254q.94 0 1.514.61q.575.597.576 1.583h-.793q-.001-.646-.356-1.034q-.353-.388-.941-.388H11.4q-.631 0-1.006.305q-.375.292-.374.798v.633q0 .408.277.692c.194.19.452.314.784.374z");
}

</style>
