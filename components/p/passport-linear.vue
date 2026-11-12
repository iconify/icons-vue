<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rap11obza"/><circle class="fr_tmn9fp"/><path class="ga7t0girt"/><path class="chuhguiil"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:passport-linear" /></template>
<style>
.chuhguiil {
  d: path("M10 19H14");
}

.fr_tmn9fp {
  cx: 12px;
  cy: 13px;
  r: 3px;
}

.ga7t0girt {
  stroke-linejoin: round;
  d: path("M18 6.00002H5.07107C4.47953 6.00002 4 5.52049 4 4.92895C4 4.39594 4.39193 3.94403 4.91959 3.86865L15.7172 2.32614C16.922 2.15402 18 3.08894 18 4.30604V6.00002Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rap11obza {
  stroke-linejoin: round;
  d: path("M4 6H17C18.6569 6 20 7.34315 20 9V19C20 20.6569 18.6569 22 17 22H7C5.34315 22 4 20.6569 4 19V6ZM4 6V5");
}

</style>
