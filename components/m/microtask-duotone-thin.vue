<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x6e_qy8ax"/><path class="xvl0zubxy"/><path class="ze6_11znx"/><path class="fizmkteml"/><path class="g8vjt7b7p"/><path class="zey5ebc0a"/><path class="r7dhdp-mq"/><path class="umr6jbb1c"/><path class="j7phtvv5f"/><path class="ceatt7y_b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:microtask-duotone-thin" /></template>
<style>
.ceatt7y_b {
  d: path("M18 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.fizmkteml {
  fill: currentColor;
  d: path("M4 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.g8vjt7b7p {
  fill: currentColor;
  d: path("M18 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j7phtvv5f {
  d: path("M4 19a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.r7dhdp-mq {
  d: path("M4 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.umr6jbb1c {
  d: path("M18 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.x6e_qy8ax {
  fill: currentColor;
  d: path("M7 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.xvl0zubxy {
  fill: currentColor;
  d: path("M4 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ze6_11znx {
  fill: currentColor;
  d: path("M18 5a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zey5ebc0a {
  d: path("M7 12a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

</style>
