<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="iul4n1zkb"/><path class="pgqcfbbga"/><path class="ko6o-6b9b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:refresh-circle-broken" /></template>
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

.ko6o-6b9b {
  d: path("M7 3.33782C8.47087 2.48697 10.1786 2 12 2C17.5228 2 22 6.47715 22 12C22 17.5228 17.5228 22 12 22C6.47715 22 2 17.5228 2 12C2 10.1786 2.48697 8.47087 3.33782 7");
}

.pgqcfbbga {
  stroke-linejoin: round;
  d: path("M16.6188 11.4445V12.3704C16.6188 14.9273 14.5217 17 11.9349 17C10.5778 17 9.3555 16.4296 8.50006 15.5181M18.0001 12.9991L16.6188 11.4445L15.0001 12.9991");
}

</style>
