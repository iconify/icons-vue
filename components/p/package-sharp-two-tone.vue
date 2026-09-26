<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="je9q5tbre"/><path class="fajy6kjai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:package-sharp-two-tone" /></template>
<style>
.fajy6kjai {
  d: path("M2 6.8477L12 12M12 12L22 6.8477M12 12L12 22M7 4.4239L17 9.4239M12 2L22 6.8477L22 17.1523L12 22L2 17.1523L2 6.8477L12 2Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.je9q5tbre {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.4362 1.1002L22.4362 5.9479C22.781 6.115 23 6.4645 23 6.8477L23 17.1523C23 17.5355 22.781 17.885 22.4362 18.0521L12.4362 22.8998C12.1607 23.0334 11.8393 23.0334 11.5638 22.8998L1.5638 18.0521C1.219 17.885 1 17.5355 1 17.1523L1 6.8477C1 6.4645 1.219 6.115 1.5638 5.9479L11.5638 1.1002C11.8393 0.9666 12.1607 0.9666 12.4362 1.1002Z");
  stroke: none;
}

</style>
