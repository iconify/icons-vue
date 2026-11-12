<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="y6055741k"/><path class="a46ke6beu"/><path class="vtyy1gbqu"/><path class="ocv7r6bbp"/><circle class="doy9q4b5f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:refresh-circle-line-duotone" /></template>
<style>
.a46ke6beu {
  stroke-linejoin: round;
  d: path("M9.00012 11L7.37769 12.5556L6.00012 11M7.37769 12.5556L7.37769 11.6296");
}

.doy9q4b5f {
  cx: 12px;
  cy: 12px;
  r: 10px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ocv7r6bbp {
  stroke-linejoin: round;
  d: path("M15.0001 12.9991L16.6188 11.4445L18.0001 12.9991M16.6188 11.4445V12.3704");
}

.vtyy1gbqu {
  d: path("M16.6188 12.3704C16.6188 14.9272 14.5217 17 11.9349 17C10.5778 17 9.3555 16.4296 8.50006 15.5181");
}

.y6055741k {
  d: path("M7.37769 11.6296C7.37769 9.07276 9.46679 7 12.0438 7C13.4046 7 14.6294 7.57797 15.4824 8.5");
}

</style>
