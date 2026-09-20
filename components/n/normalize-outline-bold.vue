<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xgrfb-bqu"/><path class="o759xmblc"/><path class="h7bcztycq"/><path class="c27cgq4un"/><path class="xyj-l9cjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:normalize-outline-bold" /></template>
<style>
.c27cgq4un {
  d: path("M18 8v8");
}

.h7bcztycq {
  d: path("M12 8v8");
}

.o759xmblc {
  d: path("M6 8v8");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

.xyj-l9cjp {
  d: path("M3 18h18");
}

</style>
