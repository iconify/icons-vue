<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f7wfav4qm"/><path class="vh7anfb6w"/><path class="f93u32esc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:sofa-3-linear" /></template>
<style>
.f7wfav4qm {
  d: path("M20 18H4C2.89543 18 2 17.1046 2 16C2 14.8954 2.89543 14 4 14H20C21.1046 14 22 14.8954 22 16C22 17.1046 21.1046 18 20 18Z");
}

.f93u32esc {
  d: path("M20 20V18M4 20V18");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vh7anfb6w {
  d: path("M4.49993 14L4.42528 13.7014C3.33845 9.35409 2.79504 7.18043 3.86584 5.67821C3.93339 5.58345 4.00504 5.49169 4.08059 5.40317C5.27824 4 7.5188 4 11.9999 4C16.4811 4 18.7216 4 19.9193 5.40317C19.9948 5.49169 20.0665 5.58345 20.134 5.67821C21.2048 7.18043 20.6614 9.35409 19.5746 13.7014L19.4999 14");
}

</style>
