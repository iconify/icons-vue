<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k2rfe35tv"/><ellipse class="fs7_ifbbz"/><path class="xqdtvabzr"/><circle class="esk8bffuy"/><circle class="yntr8obsz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:weico" /></template>
<style>
.esk8bffuy {
  cx: 17.419px;
  cy: 32.496px;
  r: 1.632px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fs7_ifbbz {
  cx: 20.26px;
  cy: 30.289px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 12.136px;
  ry: 7.735px;
}

.k2rfe35tv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.803 18.075c1.716-4.292-.34-9.006-7.11-4.896S-1.26 30.649 8.05 37.237c9.31 6.59 30.768 3.99 30.768-8.402c0-4.655-5.38-5.682-5.38-5.682s4.064-11.364-9.634-5.078");
}

.xqdtvabzr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.61 31.238c0-2.796-1.807-5.062-6.015-5.062c-3.416 0-6.015 2.765-6.015 5.56s2.78 4.564 6.015 4.564c2.796 0 6.014-2.266 6.014-5.062M38.09 18.677q.066-.36.066-.753a5.325 5.325 0 0 0-5.333-5.322c-.088 0-.164 0-.251.01m10.59 7.973c.218-.85.338-1.745.338-2.661c0-5.89-4.777-10.678-10.677-10.678c-.24 0-.491.011-.72.022");
}

.yntr8obsz {
  cx: 21.068px;
  cy: 30.365px;
  r: 0.75px;
  fill: currentColor;
}

</style>
