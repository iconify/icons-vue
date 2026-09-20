<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xugsw1b4j"/><path class="oto6z4zwr"/><path class="uwjz-dbef"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:persistent-volume-claim-duotone-bold" /></template>
<style>
.oto6z4zwr {
  d: path("M4 6a8 3 0 0 1 16 0v12a8 3 0 0 1 -16 0Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uwjz-dbef {
  d: path("m9 12 2 2 4 -4");
}

.xugsw1b4j {
  fill: currentColor;
  d: path("M4 6a8 3 0 0 1 16 0v12a8 3 0 0 1 -16 0Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
