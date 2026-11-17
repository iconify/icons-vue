<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vrfly44cm"/><path class="k-rtqsb4b"/><path class="ehqys9b8p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:route-3-sharp-fill" /></template>
<style>
.ehqys9b8p {
  d: path("M6 5H5.5C3.567 5 2 6.567 2 8.5C2 10.433 3.567 12 5.5 12H15.5C17.433 12 19 13.567 19 15.5C19 17.433 17.433 19 15.5 19H8");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k-rtqsb4b {
  fill: currentColor;
  d: path("M5.475 1.149C5.769 0.967 6.137 0.951 6.447 1.105L12.447 4.105C12.786 4.275 13 4.621 13 5C13 5.379 12.786 5.725 12.447 5.895L6.447 8.895C6.137 9.049 5.769 9.033 5.475 8.851C5.18 8.668 5 8.347 5 8V2C5 1.653 5.18 1.332 5.475 1.149Z");
  stroke: none;
}

.vrfly44cm {
  fill: currentColor;
  d: path("M5 15C7.209 15 9 16.791 9 19C9 21.209 7.209 23 5 23C2.791 23 1 21.209 1 19C1 16.791 2.791 15 5 15ZM19 1C21.209 1 23 2.791 23 5C23 7.209 21.209 9 19 9C16.791 9 15 7.209 15 5C15 2.791 16.791 1 19 1Z");
  stroke: none;
}

</style>
