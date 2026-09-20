<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG0rlcwbhA)" class="r4i437pya"/><path class="ruh_2ac2f"/><path class="c1b6dr0fx"/></g><defs><linearGradient id="SVG0rlcwbhA" x1="12.002" x2="12.002" y1="4" y2="20.516" gradientUnits="userSpaceOnUse"><stop offset=".64" class="kthujbbma"/><stop offset="1" class="pj_t7pb0g"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:shx-background" /></template>
<style>
.c1b6dr0fx {
  fill: var(--svg-color--fff, #fff);
  d: path("m19.32 17.966l-7.308-3.88V4h1.022v1.032h1.202L14.02 4h1.342zm-14.627 0l7.309-3.88V4h-.733v1.032H9.772L9.994 4H8.652z");
}

.ft5dv1b6b {
  fill: none;
}

.kthujbbma {
  stop-color: var(--svg-color--054dc9, #054dc9);
}

.pj_t7pb0g {
  stop-color: var(--svg-color--0b3299, #0b3299);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.ruh_2ac2f {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.755 4l-4.48 15.453a.423.423 0 0 0 .398.547H19.33c.273 0 .47-.268.397-.542L15.357 4h-1.342l.216 1.032h-1.197V4H10.97v1.032H9.907L10.061 4h-1.31z");
}

</style>
