<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p0lunj6wu"/><path class="yh78dp0ap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-search" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p0lunj6wu {
  d: path("M6 3H18C19.6569 3 21 4.3432 21 6V18C21 19.6569 19.6569 21 18 21H6C4.3431 21 3 19.6569 3 18V6C3 4.3432 4.3431 3 6 3Z");
}

.yh78dp0ap {
  d: path("M13.4141 13.4142L16.2425 16.2426M14.3569 11.0572C14.3569 12.8796 12.8795 14.357 11.0571 14.357C9.2346 14.357 7.7573 12.8796 7.7573 11.0572C7.7573 9.2347 9.2346 7.7574 11.0571 7.7574C12.8795 7.7574 14.3569 9.2347 14.3569 11.0572Z");
}

</style>
