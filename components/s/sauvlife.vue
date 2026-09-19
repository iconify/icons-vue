<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xdh7i-agy"/><path class="bxl39gbip"/><path class="zg4ukhb6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sauvlife" /></template>
<style>
.bxl39gbip {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m33.017 26.327l-4.385-4.374c-1.722-1.75 1.155-4.268 3.5-1.3");
}

.xdh7i-agy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m30.96 29.421l-5.81-6.017c-2.002-2.471 1.083-4.077 3.023-1.983");
}

.zg4ukhb6u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m36.516 25.21l-4.041-4.133c-1.695-2.183 1.67-2.706 2.644-1.84l6.205 5.972c5.088-11.25-7.397-23.681-17.22-15.426C8.84-.645-8.813 24.171 24.275 40.897q1.985-1.102 4.195-2.843l-2.57-.956c-2.771-1.137.099-3.689 2.272-3.554c3.293.289 1.733-.947.65-1.993l-4.457-4.44c-1.705-1.902 0-3.363 1.218-3.11");
}

</style>
