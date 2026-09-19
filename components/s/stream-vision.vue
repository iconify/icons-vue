<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sp6-nrqzl"/><path class="ddlcvx9av"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stream-vision" /></template>
<style>
.ddlcvx9av {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.192 32.5v-8.157m0-9.639V9.5c0-3.079 3.333-5.004 6-3.465l8.66 5h-7.671a8.488 8.488 0 1 0 0 16.977h9");
}

.sp6-nrqzl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.18 19.461h9a8.488 8.488 0 1 1 0 16.977L8.193 36.5v2c0 3.079 3.333 5.004 6 3.465l9.57-5.526m7.963-4.597l7.582-4.377c2.667-1.54 2.667-5.39 0-6.93l-12.991-7.5");
}

</style>
