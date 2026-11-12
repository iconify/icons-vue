<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="iul4n1zkb"/><path class="pgqcfbbga"/><path class="wf89k6buf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:refresh-square-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iul4n1zkb {
  stroke-linejoin: round;
  d: path("M7.37769 12.5556L7.37769 11.6296C7.37769 9.07276 9.46679 7 12.0438 7C13.4046 7 14.6294 7.57797 15.4824 8.5M6.00012 11L7.37769 12.5556L9.00012 11");
}

.pgqcfbbga {
  stroke-linejoin: round;
  d: path("M16.6188 11.4445V12.3704C16.6188 14.9273 14.5217 17 11.9349 17C10.5778 17 9.3555 16.4296 8.50006 15.5181M18.0001 12.9991L16.6188 11.4445L15.0001 12.9991");
}

.wf89k6buf {
  d: path("M2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
