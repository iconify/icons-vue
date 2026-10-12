<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="b31pp6klw"/><path class="us2evabuy"/><rect class="cjja4ibpm"/><path class="aps9-1aot"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:space-food" /></template>
<style>
.aps9-1aot {
  d: path("M5.75 11.25h12.5M9 15.5h6m-6 2.75h4");
}

.b31pp6klw {
  width: 4px;
  height: 2.75px;
  x: 10px;
  y: 2.75px;
  rx: 1px;
}

.cjja4ibpm {
  width: 12.5px;
  height: 13.25px;
  x: 5.75px;
  y: 8px;
  rx: 2px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.us2evabuy {
  d: path("M12 5.5V8");
}

</style>
