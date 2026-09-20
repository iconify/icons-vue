<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="xabpd8buq"/><path class="suc-rpe6f"/><path clip-rule="evenodd" class="qjrkbdlzi"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:obvious-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qjrkbdlzi {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("m20 6.768l-2.647-.466l-.96 8.003l1.765.31zm-3.346 11.215a1.118 1.118 0 1 0 .389-2.201a1.118 1.118 0 1 0-.389 2.201");
}

.suc-rpe6f {
  fill: var(--svg-color--000, #000);
  d: path("M9.608 17.624q-1.677 0-2.94-.738a5.3 5.3 0 0 1-1.965-2.04Q4 13.53 4 11.813t.703-3.018A5.3 5.3 0 0 1 6.668 6.74q1.263-.74 2.94-.739q1.662 0 2.924.739a5.13 5.13 0 0 1 1.966 2.055q.702 1.3.703 3.018q0 1.718-.703 3.035a5.16 5.16 0 0 1-1.966 2.039q-1.262.738-2.924.738m0-1.846q1.598 0 2.541-1.06q.959-1.06.959-2.906t-.959-2.906q-.942-1.06-2.54-1.06t-2.557 1.06t-.959 2.906t.959 2.906t2.556 1.06");
}

.xabpd8buq {
  fill: var(--svg-color--a1e5ce, #a1e5ce);
  d: path("M24 0H0v24h24z");
}

</style>
