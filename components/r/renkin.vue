<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uyg01rgdh"/><circle class="xakrkvy8r"/><circle class="vqogbbbht"/><path class="hjfd2gb2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:renkin" /></template>
<style>
.hjfd2gb2j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.185 9.776c-1.414 1.415-3.192-1.51-.54-3.041c1.05-.607 2.97-.609 3.466 1.244c.821 3.066-5.11 7.36-5.11 7.36L42.5 5.5L32.66 19s4.294-5.932 7.36-5.11c1.853.496 1.851 2.414 1.245 3.465c-1.532 2.652-4.456.874-3.042-.54");
}

.uyg01rgdh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.43 22.388a18.5 18.5 0 0 1-10.611 18.379a18.5 18.5 0 0 1-20.9-3.685a18.5 18.5 0 0 1-3.685-20.9A18.5 18.5 0 0 1 25.613 5.57");
}

.vqogbbbht {
  cx: 24px;
  cy: 24px;
  r: 0.75px;
  fill: currentColor;
}

.xakrkvy8r {
  cx: 24px;
  cy: 24px;
  r: 10px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
