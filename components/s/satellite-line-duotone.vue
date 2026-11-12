<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pzqlz6blu"/><path class="ro7gb9b3j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:satellite-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pzqlz6blu {
  d: path("M16.1602 7.83991C18.6229 10.3025 20.4699 10.918 20.4699 10.918L14.3132 22M16.1602 7.83991C13.6976 5.37729 13.082 3.53009 13.082 3.53009L2 9.68689M16.1602 7.83991L5 19");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ro7gb9b3j {
  d: path("M20.4698 10.918C18.4297 12.9581 15.122 12.9581 13.0818 10.918C11.0417 8.87785 11.0417 5.57019 13.0818 3.53008C15.122 1.48997 18.4297 1.48997 20.4698 3.53008C22.5099 5.57019 22.5099 8.87785 20.4698 10.918Z");
}

</style>
