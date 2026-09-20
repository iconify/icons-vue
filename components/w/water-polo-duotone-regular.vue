<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xnrghp1vk"/><path class="o-4bk_b4n"/><path class="w6_tlja0w"/><path class="kpspt_bpo"/><path class="d2vyd9blc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:water-polo-duotone-regular" /></template>
<style>
.d2vyd9blc {
  d: path("M3 18c3 -2 6 2 9 0s6 2 9 0");
}

.kpspt_bpo {
  d: path("M7 8h10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o-4bk_b4n {
  d: path("M7 8a5 5 0 1 0 10 0A5 5 0 1 0 7 8");
}

.w6_tlja0w {
  d: path("M12 3v10");
}

.xnrghp1vk {
  fill: currentColor;
  d: path("M7 8a5 5 0 1 0 10 0A5 5 0 1 0 7 8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
