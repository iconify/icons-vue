<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n3rx67pmh"/><path class="y6xgxuzrp"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:monitor-off-duotone" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.n3rx67pmh {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 17H13V19H16C16.5523 19 17 19.4477 17 20C17 20.5523 16.5523 21 16 21H8C7.44772 21 7 20.5523 7 20C7 19.4477 7.44772 19 8 19H11V17H5C2.7909 17 1 15.2091 1 13V7C1 5.4283 1.92159 4.00029 3.35449 3.35449L17 17Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.y6xgxuzrp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.6569 3H19C21.2091 3 23 4.7909 23 7V13C23 14.1736 22.4846 15.2879 21.5904 16.0479C21.1935 16.3853 20.604 16.3614 20.2357 15.9931L8.9497 4.7071C8.6637 4.4211 8.5782 3.991 8.733 3.6173C8.8878 3.2436 9.2524 3 9.6569 3Z");
  stroke: none;
}

</style>
