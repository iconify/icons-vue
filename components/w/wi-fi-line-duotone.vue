<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dt_kzxb6g"/><path class="focqhos4p"/><path class="g1pa1nbfl"/><path class="zj2p4py0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wi-fi-line-duotone" /></template>
<style>
.dt_kzxb6g {
  d: path("M8.66699 15.8931C10.5079 13.9061 13.4927 13.9061 15.3337 15.8931");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.focqhos4p {
  d: path("M5.33301 12.295C9.01491 8.32093 14.9844 8.32093 18.6663 12.295");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.g1pa1nbfl {
  d: path("M2 8.69694C7.52285 2.73579 16.4772 2.73579 22 8.69694");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zj2p4py0y {
  stroke-linejoin: round;
  d: path("M12.0176 19.4644H12.0177");
}

</style>
