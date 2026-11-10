<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="mjcao5btk"/><path class="u-m5f9ihc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:towel-rack-two-tone" /></template>
<style>
.mjcao5btk {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 2C18.4189 2 20.4361 3.72 20.8994 6H22C22.5523 6 23 6.45 23 7C23 7.55 22.5523 8 22 8H21V19C21 20.66 19.6569 22 18 22H11C9.3432 22 8 20.66 8 19V16H6C4.3432 16 3 14.66 3 13V8H2C1.4477 8 1 7.55 1 7C1 6.45 1.4477 6 2 6H3V5.5C3 3.57 4.567 2 6.5 2H16Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u-m5f9ihc {
  d: path("M2 7H9M20 7H22M20 7C20 4.79 18.2091 3 16 3H6.5M20 7V13V17M9 15H6C4.8954 15 4 14.1 4 13V5.5C4 4.12 5.1193 3 6.5 3M9 15V13V5.5C9 4.12 7.8807 3 6.5 3M9 15V17M9 17V19C9 20.1 9.8954 21 11 21H18C19.1046 21 20 20.1 20 19V17M9 17H20");
}

</style>
