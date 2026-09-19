<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="tcaoxxgtd"/><path class="cdn60dbmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:segway-ninebot" /></template>
<style>
.cdn60dbmr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.73 17.026h13.68c3.76 0 4.25 3.016 3.465 6.002L27.381 40.13c-.523 1.983-1.991 3.37-4.543 3.37c-1.75 0-3.24-1.3-3.839-2.944s-.108-3.396.484-4.723l4.248-10.275h-6.916m8.969-4.249H11.022");
}

.tcaoxxgtd {
  cx: 32.476px;
  cy: 9.002px;
  r: 4.502px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
