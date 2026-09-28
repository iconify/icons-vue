<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="c42n_vo5g"/><path class="x1xecm2io"/><path class="r4rw-imsf"/><path class="w8slmsefx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:package-alert-sharp-duotone" /></template>
<style>
.c42n_vo5g {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.4362 1.1002L22.4362 5.9479C22.781 6.115 23 6.4645 23 6.8477L23 12C23 12.5523 22.5523 13 22 13L16 13L13 13L13 22C13 22.5523 12.5523 23 12 23C11.8508 23 11.7015 22.9666 11.5638 22.8998L1.5638 18.0521C1.219 17.885 1 17.5355 1 17.1523L1 6.8477C1 6.4645 1.219 6.115 1.5638 5.9479L11.5638 1.1002C11.8393 0.9666 12.1607 0.9666 12.4362 1.1002Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r4rw-imsf {
  d: path("M19 15L19 19");
}

.w8slmsefx {
  fill: currentColor;
  d: path("M20 22C20 22.5523 19.5523 23 19 23C18.4477 23 18 22.5523 18 22C18 21.4477 18.4477 21 19 21C19.5523 21 20 21.4477 20 22Z");
  stroke: none;
}

.x1xecm2io {
  fill: currentColor;
  d: path("M7.0068 3.3093L11.5638 1.1002C11.8393 0.9666 12.1607 0.9666 12.4362 1.1002L22.4362 5.9479C22.781 6.115 23 6.4645 23 6.8477L23 7.4574L19.2093 9.4105ZM4.7362 4.41L17.0067 10.5453L12.458 12.8889C12.1706 13.037 11.8294 13.037 11.542 12.8889L1 7.4574L1 6.8477C1 6.4645 1.219 6.115 1.5638 5.9479L4.7362 4.41Z");
  stroke: none;
}

</style>
