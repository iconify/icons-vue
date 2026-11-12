<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vw4esubrn"/><path class="zoepyyq4j"/><path class="z3hbucb_l"/><path class="id9cc5l6h"/><path class="rt8kpfwzv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wheel-angle-line-duotone" /></template>
<style>
.id9cc5l6h {
  d: path("M7.5 22L16.5 22");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rt8kpfwzv {
  d: path("M9 12C9 15.3137 8.32843 18 7.5 18C6.67157 18 6 15.3137 6 12C6 8.68629 6.67157 6 7.5 6C8.32843 6 9 8.68629 9 12ZM9 12H8");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.vw4esubrn {
  d: path("M16.5 22C18.9853 22 21 17.5228 21 12C21 6.47715 18.9853 2 16.5 2");
}

.z3hbucb_l {
  d: path("M7.5 2L16.5 2");
}

.zoepyyq4j {
  d: path("M12 12C12 17.5228 9.98528 22 7.5 22C5.01472 22 3 17.5228 3 12C3 6.47715 5.01472 2 7.5 2C9.98528 2 12 6.47715 12 12Z");
}

</style>
