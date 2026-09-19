<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cu1l0b71n"/><path class="am9bwv_hn"/><path class="a6711ebon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:obdeleven" /></template>
<style>
.a6711ebon {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.055 21.15c0 2.85 2.225 4.528 4.154 4.528c2.476 0 2.912-2.599 2.912-4.529s-1.641-3.494-3.571-3.494s-3.495 1.564-3.495 3.494");
}

.am9bwv_hn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 40.958c13.548 0 19-9.236 19-15.785V10.539c0-.467-.26-.896-.674-1.112l-3.19-1.66a1.25 1.25 0 0 0-1.478.239l-2.477 2.555S29.267 7.04 24 7.04s-11.18 3.52-11.18 3.52l-2.478-2.555a1.25 1.25 0 0 0-1.479-.24L5.674 9.427A1.25 1.25 0 0 0 5 10.54v14.634c0 6.549 5.452 15.785 19 15.785");
}

.cu1l0b71n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.945 21.15c0 2.85-2.225 4.528-4.154 4.528c-2.476 0-2.912-2.599-2.912-4.529s1.642-3.494 3.571-3.494s3.495 1.564 3.495 3.494");
}

</style>
