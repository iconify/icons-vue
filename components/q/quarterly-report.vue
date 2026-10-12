<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="h81zrmtfz"/><path class="nl9nuxcnn"/><path class="hcr7wigqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:quarterly-report" /></template>
<style>
.h81zrmtfz {
  width: 15.5px;
  height: 18.5px;
  x: 4.25px;
  y: 2.75px;
  rx: 2.5px;
}

.hcr7wigqs {
  d: path("M12.75 13.25v-3.5a3.5 3.5 0 0 1 3.5 3.5Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nl9nuxcnn {
  d: path("M8.5 6.25h7M12 9.75A4.25 4.25 0 1 0 16.25 14");
}

</style>
