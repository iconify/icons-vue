<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="bucddhbte"/><path class="h_xkaqy0p"/><path class="cqw6oyk8z"/><path class="zwzgjsm-o"/><path class="s_3njwb9k"/><path class="sxnipqb0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:traffic-jam-duotone-bold" /></template>
<style>
.bucddhbte {
  fill: currentColor;
  d: path("M7.5 5.5 10 3h4l2.5 2.5V8h-9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.cqw6oyk8z {
  d: path("M3.5 2v20");
}

.h_xkaqy0p {
  fill: currentColor;
  d: path("M7.5 15.5 10 13h4l2.5 2.5V18h-9Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s_3njwb9k {
  d: path("M7.5 5.5 10 3h4l2.5 2.5V8h-9Z");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sxnipqb0a {
  d: path("M7.5 15.5 10 13h4l2.5 2.5V18h-9Z");
}

.zwzgjsm-o {
  d: path("M20.5 2v20");
}

</style>
