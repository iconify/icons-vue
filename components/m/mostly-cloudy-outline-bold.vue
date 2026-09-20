<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="htoy-r04r"/><path class="pkd2_xalb"/><path class="i13g5lbrq"/><path class="uspjb2blh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mostly-cloudy-outline-bold" /></template>
<style>
.htoy-r04r {
  d: path("M12 6a4 4 0 0 1 8 0");
}

.i13g5lbrq {
  d: path("m22 3.5 -2 2");
}

.pkd2_xalb {
  d: path("m10 3.5 2 2");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.uspjb2blh {
  d: path("M4 20a4 4 0 0 1 2 -7.5 5 5 0 0 1 9.5 -1.5 5.5 5.5 0 0 1 4.5 9Z");
}

</style>
