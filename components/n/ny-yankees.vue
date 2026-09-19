<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a5w_88egi"/><path class="sxmpy9x_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ny-yankees" /></template>
<style>
.a5w_88egi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.986 39.875s8.921-15.112-.29-29.166l28.258 31.06s-8.237-21.51 2.35-29.842");
}

.sxmpy9x_m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.315 42.5L24 25.827S28.456 12.648 32.617 5.5M24 25.827S19.544 12.648 15.383 5.5");
}

</style>
