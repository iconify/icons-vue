<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dgxeydb5e"/><path class="ksyzu5xew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ulogger" /></template>
<style>
.dgxeydb5e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5a13.09 13.09 0 0 0-13.09 13.09c0 10.25 10 22.61 12.61 25.63a.8.8 0 0 0 1.21 0c2.55-3 12.36-15.38 12.36-25.63A13.09 13.09 0 0 0 24 4.5");
}

.ksyzu5xew {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.52 11.65V19A4.48 4.48 0 0 0 24 23.52h0A4.48 4.48 0 0 0 28.48 19v-7.35m0 7.39v4.48m-8.96-4.48v10.22");
}

</style>
