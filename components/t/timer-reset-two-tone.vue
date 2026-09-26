<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w1xvjqqre"/><path class="uoq1y5w9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:timer-reset-two-tone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uoq1y5w9g {
  d: path("M9 2L15 2M12 2L12 6M12 14L12 10M17.6569 8.3431L19 7");
}

.w1xvjqqre {
  stroke-opacity: 0.4;
  d: path("M10.2749 21.8118C10.8414 21.9369 11.4199 22 12 22C16.4183 22 20 18.4183 20 14C20 9.5817 16.4183 6 12 6C7.5817 6 4 9.5817 4 14C4 16.2072 4.9119 18.3163 6.5199 19.8283M4.0001 20.9408L6.79 20.5422C7.0634 20.5032 7.2533 20.2499 7.2143 19.9765L6.8157 17.1867");
}

</style>
