<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="p3z_iunwt"/><path class="g0v-9nbsk"/><path class="q-qndji8q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:server-plus-sharp-two-tone" /></template>
<style>
.g0v-9nbsk {
  d: path("M2 2L18 2L18 10L2 10L2 2ZM13 22L2 22L2 14L13 14M19 15L19 23M15 19L23 19");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p3z_iunwt {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 1L18 1C18.5523 1 19 1.4477 19 2L19 10C19 10.5523 18.5523 11 18 11L2 11C1.4477 11 1 10.5523 1 10L1 2C1 1.4477 1.4477 1 2 1ZM2 13L13 13L13 23L2 23C1.4477 23 1 22.5523 1 22L1 14C1 13.4477 1.4477 13 2 13Z");
  stroke: none;
}

.q-qndji8q {
  fill: currentColor;
  d: path("M7 6C7 6.5523 6.5523 7 6 7C5.4477 7 5 6.5523 5 6C5 5.4477 5.4477 5 6 5C6.5523 5 7 5.4477 7 6ZM11 6C11 6.5523 10.5523 7 10 7C9.4477 7 9 6.5523 9 6C9 5.4477 9.4477 5 10 5C10.5523 5 11 5.4477 11 6ZM7 18C7 18.5523 6.5523 19 6 19C5.4477 19 5 18.5523 5 18C5 17.4477 5.4477 17 6 17C6.5523 17 7 17.4477 7 18ZM11 18C11 18.5523 10.5523 19 10 19C9.4477 19 9 18.5523 9 18C9 17.4477 9.4477 17 10 17C10.5523 17 11 17.4477 11 18Z");
  stroke: none;
}

</style>
