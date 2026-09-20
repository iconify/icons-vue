<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jp0zyeb8a"/><path class="vmb9_db5e"/><path class="k9u7_xb8c"/><path class="t6k3bm-ng"/><path class="d7liw45th"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:moonlight-duotone-thin" /></template>
<style>
.d7liw45th {
  d: path("m17 17 3 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jp0zyeb8a {
  fill: currentColor;
  d: path("M14 3a7 7 0 1 0 0 12 5.5 5.5 0 0 1 0 -12");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.k9u7_xb8c {
  d: path("m8 17 -3 3");
}

.t6k3bm-ng {
  d: path("M13 17v4");
}

.vmb9_db5e {
  d: path("M14 3a7 7 0 1 0 0 12 5.5 5.5 0 0 1 0 -12");
}

</style>
