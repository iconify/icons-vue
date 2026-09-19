<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="v_2sqbdom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:saucillatorforandroid" /></template>
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

.v_2sqbdom {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M2.55 22.52c.56-.29 1.18-1.19 3.11 2.74s5.09 3.88 7.59 0s4.25-4.18 6.59 0s5.45 4.13 7.55 0s4.59-4 6.86 0s5.45 4.32 7.55 0s3.66-2.67 3.66-2.67");
}

</style>
