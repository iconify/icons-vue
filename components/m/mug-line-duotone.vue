<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="njf5snbwf"/><path class="k5vu_1awm"/><path class="w4m4eeb0m"/><path class="fd7_frbmd"/><path class="b8muav1zi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mug-line-duotone" /></template>
<style>
.b8muav1zi {
  d: path("M17 13H18C20.2091 13 22 11.2091 22 9C22 6.79086 20.2091 5 18 5H16.9493");
}

.fd7_frbmd {
  d: path("M22 21L2 21");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k5vu_1awm {
  d: path("M9 18H11C13.8284 18 15.2426 18 16.1213 17.1213C17 16.2426 17 14.8284 17 12V7C17 5.11438 17 4.17157 16.4142 3.58579C15.8284 3 14.8856 3 13 3H7C5.11438 3 4.17157 3 3.58579 3.58579C3 4.17157 3 5.11438 3 7V12C3 14.8284 3 16.2426 3.87868 17.1213C4.75736 18 6.17157 18 9 18Z");
}

.njf5snbwf {
  d: path("M17.0002 13H3.00174");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.w4m4eeb0m {
  d: path("M17 13H18C20.2091 13 22 11.2091 22 9C22 6.79086 20.2091 5 18 5H17");
}

</style>
