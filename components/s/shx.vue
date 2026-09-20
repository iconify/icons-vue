<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGIKNA9XLm)" class="bf9twr13p"/><path fill="url(#SVG0rfgJg3s)" class="aabrqevbv"/><path fill="url(#SVGWUJJ2cIJ)" class="hjcuhbc0r"/><defs><linearGradient id="SVGIKNA9XLm" x1="12.002" x2="12.002" y1="3" y2="21.581" gradientUnits="userSpaceOnUse"><stop offset=".64" class="kthujbbma"/><stop offset="1" class="pj_t7pb0g"/></linearGradient><linearGradient id="SVG0rfgJg3s" x1="3.289" x2="5.97" y1="4.596" y2="22.565" gradientUnits="userSpaceOnUse"><stop class="lr9a9x-9w"/><stop offset=".77" class="rhb_tgb8k"/></linearGradient><linearGradient id="SVGWUJJ2cIJ" x1="3.141" x2="12.309" y1="4.057" y2="13.875" gradientUnits="userSpaceOnUse"><stop class="je2pbbsmd"/><stop offset="1" class="z29halbjv"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:shx" /></template>
<style>
.aabrqevbv {
  d: path("m20.236 18.712l-8.222-4.366V3h1.15v1.161h1.353L14.273 3h1.51z");
}

.bf9twr13p {
  d: path("M8.35 3L3.31 20.385a.476.476 0 0 0 .447.615h16.49c.308 0 .529-.302.447-.61L15.776 3h-1.51l.245 1.161h-1.347V3H10.84v1.161H9.645L9.819 3H8.344z");
}

.ft5dv1b6b {
  fill: none;
}

.hjcuhbc0r {
  d: path("m3.78 18.712l8.222-4.366V3h-.825v1.161H9.493L9.743 3h-1.51z");
}

.je2pbbsmd {
  stop-color: var(--svg-color--025ee3, #025ee3);
}

.kthujbbma {
  stop-color: var(--svg-color--054dc9, #054dc9);
}

.lr9a9x-9w {
  stop-color: var(--svg-color--0556d9, #0556d9);
}

.pj_t7pb0g {
  stop-color: var(--svg-color--0b3299, #0b3299);
}

.rhb_tgb8k {
  stop-color: var(--svg-color--0a2993, #0a2993);
}

.z29halbjv {
  stop-color: var(--svg-color--0e2fa2, #0e2fa2);
}

</style>
