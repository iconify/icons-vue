<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wuurlufyl"/><path clip-rule="evenodd" class="eom8ljbas"/><path class="qpqelktix"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:vault-duotone" /></template>
<style>
.eom8ljbas {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 6L15.5 6C16.8807 6 18 7.1193 18 8.5L18 15.5C18 16.8807 16.8807 18 15.5 18L8.5 18C7.1193 18 6 16.8807 6 15.5L6 8.5C6 7.1193 7.1193 6 8.5 6ZM14 11C14 10.4477 13.5523 10 13 10C12.4477 10 12 10.4477 12 11L12 13C12 13.5523 12.4477 14 13 14C13.5523 14 14 13.5523 14 13L14 11Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qpqelktix {
  d: path("M5 10L7 10M5 14L7 14");
}

.wuurlufyl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 2L18 2C20.2092 2 22 3.7908 22 6L22 18C22 20.2092 20.2092 22 18 22L6 22C3.7908 22 2 20.2092 2 18L2 6C2 3.7908 3.7908 2 6 2Z");
  stroke: none;
}

</style>
