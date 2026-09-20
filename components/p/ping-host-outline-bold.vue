<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ks8dyvldl"/><path class="yw0xzbbmi"/><path class="zd9q8ha4t"/><path class="w1_ilb-be"/><path class="pu4b1osbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:ping-host-outline-bold" /></template>
<style>
.ks8dyvldl {
  d: path("M15.5 8a2 2 0 0 1 2 -2H20a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2h-2.5a2 2 0 0 1 -2 -2Z");
}

.pu4b1osbn {
  d: path("M12 12h3.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.w1_ilb-be {
  d: path("M8.5 5.94a7 7 0 0 1 0 12.12");
}

.yw0xzbbmi {
  d: path("M4 12a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.zd9q8ha4t {
  d: path("M7 8.54a4 4 0 0 1 0 6.92");
}

</style>
