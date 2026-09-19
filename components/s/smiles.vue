<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f402w085x"/><path class="w9naqb3ng"/><path class="ive_uzb7y"/><path class="j5-kzf53g"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smiles" /></template>
<style>
.f402w085x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.342 23.893A2.2 2.2 0 0 0 32.14 21.7h0a2.2 2.2 0 0 0-2.202 2.194h0v.713h4.404m1.826 2.417c.402.336.836.49 1.81.49h.495c.804 0 1.455-.65 1.455-1.453h0c0-.803-.651-1.454-1.455-1.454h-.988c-.804 0-1.456-.65-1.456-1.453h0c0-.803.652-1.454 1.456-1.454h.494c.974 0 1.409.154 1.81.49m-5.736 4.217a2.2 2.2 0 0 1-1.913 1.107c-.82 0-1.534-.446-1.914-1.107");
}

.ive_uzb7y {
  fill: currentColor;
  d: path("M25.813 19.012a.751.751 0 0 1-1.5 0a.751.751 0 0 1 1.5 0");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.j5-kzf53g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.063 21.7v5.814m-6.593-3.62c0-1.212.986-2.194 2.202-2.194h0c1.216 0 2.202.982 2.202 2.194v3.62M14.066 21.7v5.814m0-3.62c0-1.212.986-2.194 2.202-2.194h0c1.216 0 2.202.982 2.202 2.194v3.62");
}

.w9naqb3ng {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.938 23.894c0-1.212.986-2.194 2.202-2.194h0c1.216 0 2.202.982 2.202 2.194v.713h-4.404m-2.526-5.869v7.68c0 .605.493 1.096 1.101 1.096h.33m-20.387-.49c.402.336.836.49 1.811.49h.494c.804 0 1.456-.65 1.456-1.453h0c0-.803-.652-1.454-1.456-1.454h-.988c-.804 0-1.455-.65-1.455-1.453h0c0-.803.651-1.454 1.455-1.454h.494c.975 0 1.41.154 1.811.49");
}

</style>
