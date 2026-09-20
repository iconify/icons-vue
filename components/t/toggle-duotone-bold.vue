<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="xc-pw4ble"/><path class="mgt26xbkp"/><path class="unjh48car"/><path class="vjdmi0bfh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:toggle-duotone-bold" /></template>
<style>
.mgt26xbkp {
  fill: currentColor;
  d: path("M14 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
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

.unjh48car {
  d: path("M2 12a5 5 0 0 1 5 -5h10a5 5 0 0 1 5 5 5 5 0 0 1 -5 5H7a5 5 0 0 1 -5 -5");
}

.vjdmi0bfh {
  d: path("M14 12a3 3 0 1 0 6 0 3 3 0 1 0 -6 0");
}

.xc-pw4ble {
  fill: currentColor;
  d: path("M2 12a5 5 0 0 1 5 -5h10a5 5 0 0 1 5 5 5 5 0 0 1 -5 5H7a5 5 0 0 1 -5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
