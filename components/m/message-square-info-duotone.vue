<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uwjrx0j1q"/><path class="mq3or7biw"/><path clip-rule="evenodd" class="of010968h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-info-duotone" /></template>
<style>
.mq3or7biw {
  d: path("M12 13L12 11");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.of010968h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 7C13 7.5523 12.5523 8 12 8C11.4477 8 11 7.5523 11 7C11 6.4477 11.4477 6 12 6C12.5523 6 13 6.4477 13 7Z");
  stroke: none;
}

.uwjrx0j1q {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 13.5L2 6C2 3.7908 3.7908 2 6 2L18 2C20.2092 2 22 3.7908 22 6L22 14C22 16.2092 20.2092 18 18 18L7.4142 18L3.7071 21.7071C3.5196 21.8946 3.2652 22 3 22C2.4477 22 2 21.5523 2 21Z");
  stroke: none;
}

</style>
