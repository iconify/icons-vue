<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o18kvfb3s"/><path class="aca8r7bsh"/><circle class="zlw5vobhz"/><circle class="eyzdobcop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:reffurence" /></template>
<style>
.aca8r7bsh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.1 15.053c2.16-2.469 4.711-9.242 4.711-9.242c3.548 4.193 4.088 6.582 2.62 11.525");
}

.eyzdobcop {
  cx: 39.854px;
  cy: 25.922px;
  r: 1.776px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.o18kvfb3s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.203 23.877c2.052-1.075 2.443-1.964 2.443-3.9S5.21 12.414 9.431 6.12c3.089 4.027 8.249 9.109 8.249 9.109c1.544-.625 15.99-.9 15.99 12.549c0 1.564-.86 3.44-.86 3.44c2.853.196 4.73 1.564 7.622 1.29c-1.485 4.496-7.154 9.735-14.073 7.78c-2.072.704-2.393 2.525-2.393 2.525");
}

.zlw5vobhz {
  cx: 25.146px;
  cy: 26.726px;
  r: 2.849px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
