<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="l2envlbrx"/><path class="jgxljgb7e"/><path class="ga9xkbieh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:pill-duotone-bold" /></template>
<style>
.ga9xkbieh {
  d: path("m8.5 8.5 7 7");
}

.jgxljgb7e {
  d: path("m3.5 13.5 10 -10a5 5 0 0 1 7 7l-10 10a5 5 0 0 1 -7 -7");
}

.l2envlbrx {
  fill: currentColor;
  d: path("m3.5 13.5 10 -10a5 5 0 0 1 7 7l-10 10a5 5 0 0 1 -7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
