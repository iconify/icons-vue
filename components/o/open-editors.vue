<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="f9qelxbfr"/><path class="hcv1zzb3y"/><path class="ddue91ytc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:open-editors" /></template>
<style>
.ddue91ytc {
  d: path("M11 6v2.5a2 2 0 0 0 2 2h2.5m-9.5 4h6M6 18h3.5");
}

.f9qelxbfr {
  d: path("M8 6V5a2.5 2.5 0 0 1 2.5-2.5H16L20.5 7v8.5A2.5 2.5 0 0 1 18 18h-2.5");
}

.hcv1zzb3y {
  d: path("M5.5 6H11l4.5 4.5V19a2.5 2.5 0 0 1-2.5 2.5H5.5A2.5 2.5 0 0 1 3 19V8.5A2.5 2.5 0 0 1 5.5 6ZM16 2.5V5a2 2 0 0 0 2 2h2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
