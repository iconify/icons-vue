<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q9ucc8xlp"/><circle class="ss8spzbmy"/><path class="tgjn83f7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:microsoft-company-portal" /></template>
<style>
.q9ucc8xlp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.223 32.383H6.541a1.025 1.025 0 0 1-1.027-1.027V7.735c0-.57.458-1.027 1.027-1.027h34.918c.57 0 1.027.458 1.027 1.027v23.621c0 .57-.458 1.027-1.027 1.027H26.256");
}

.ss8spzbmy {
  cx: 18.394px;
  cy: 20.831px;
  r: 6.162px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.tgjn83f7e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.064 41.292h20.415c.996-17.147-21.246-17.879-20.415 0m9.559-34.584v8.007m12.083-8.007v25.675m12.78-12.838H24.428m-18.914 0H12.3m17.475 6.309h12.711");
}

</style>
