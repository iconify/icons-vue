<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="t4b659o-m"/><path class="n67lb0kuw"/><circle class="wkxw5hbfm"/><path class="o7049ur1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:switcher-smart-home" /></template>
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

.n67lb0kuw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 12.5c-3.75 0-7.269 1.833-9.42 4.904a2 2 0 1 0 3.275 2.293C19.26 17.691 21.552 16.5 24 16.5s4.74 1.191 6.145 3.197a2 2 0 1 0 3.275-2.293A11.5 11.5 0 0 0 24 12.5");
}

.o7049ur1b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.424 16.25a3 3 0 0 0 5.195-3m-37.239 0a3 3 0 0 0 5.196 3");
}

.t4b659o-m {
  cx: 24px;
  cy: 24px;
  r: 15.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wkxw5hbfm {
  cx: 24px;
  cy: 24px;
  r: 3px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
