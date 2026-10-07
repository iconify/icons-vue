<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kgnmv9d8m"/><path class="q7esdfb9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:signature-duotone" /></template>
<style>
.kgnmv9d8m {
  stroke-opacity: 0.4;
  d: path("M8.5 18L22 18");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q7esdfb9m {
  d: path("M2 21C3.1938 18.9186 4.7128 16.0493 5.9929 13.2135M5.99294 13.2135C8.20397 8.31533 9.7023 3.51693 7.5814 3.05055C3.63084 2.18185 2.58008 12.7908 5.99294 13.2135ZM5.99294 13.2135C6.19638 13.2387 6.41568 13.2277 6.65116 13.1759C10.8372 12.2554 11.3023 8.57347 11.7674 10.4144C12.2326 12.2554 13.1628 14.0964 14.5581 13.6361C15.9535 13.1759 16.4186 10.8747 17.3488 12.2554C18.2791 13.6361 20.6047 13.6361 22 13.6361");
}

</style>
