<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="x5n6k1b3y"/><path class="dh0mn2bvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:star-2-line-duotone" /></template>
<style>
.dh0mn2bvs {
  d: path("M17.6569 6.34277L15.9599 8.03983M8.04029 15.9594L6.34323 17.6565M6.34302 6.34295L8.04007 8.04001M15.9597 15.9596L17.6567 17.6567");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x5n6k1b3y {
  d: path("M12 20V17.6M12 6.4V4M20 12H17.6M6.4 12H4");
}

</style>
