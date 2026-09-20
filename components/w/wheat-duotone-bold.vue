<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="sd4em8b-j"/><path class="nco06-bkq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wheat-duotone-bold" /></template>
<style>
.nco06-bkq {
  d: path("M12 21V4m0 4L7 3m5 5 5 -5m-5 10L7 8m5 5 5 -5m-5 10 -5 -5m5 5 5 -5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sd4em8b-j {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 21V4m0 4L7 3m5 5 5 -5m-5 10L7 8m5 5 5 -5m-5 10 -5 -5m5 5 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
