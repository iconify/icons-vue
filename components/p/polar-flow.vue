<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="n4pm8_gbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:polar-flow" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n4pm8_gbc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.8 21.458h18.478c2.688 0 2.688-4.443 0-4.443H9.248m-.023-.008c2.725-5.47 8.38-8.936 14.576-8.936c8.965 0 16.232 7.144 16.232 15.955h0c0 8.812-7.267 15.956-16.232 15.956h0c-8.964 0-16.232-7.144-16.232-15.956h0c0-.861.071-1.722.213-2.572");
}

</style>
