<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="sk-0k46vg"/><path class="nptt5bbgx"/><path class="r182r524c"/><path class="uokpg3btu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mouse-duotone-bold" /></template>
<style>
.nptt5bbgx {
  d: path("M7 7a5 5 0 0 1 5 -5 5 5 0 0 1 5 5v10a5 5 0 0 1 -5 5 5 5 0 0 1 -5 -5Z");
}

.r182r524c {
  d: path("M7 9h10");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.sk-0k46vg {
  fill: currentColor;
  d: path("M7 7a5 5 0 0 1 5 -5 5 5 0 0 1 5 5v10a5 5 0 0 1 -5 5 5 5 0 0 1 -5 -5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.uokpg3btu {
  d: path("M12 5v3");
}

</style>
