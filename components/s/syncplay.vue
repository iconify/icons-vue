<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="vneiq63ue"/><path class="jue9gtbwu"/><path class="j2-02ab-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:syncplay" /></template>
<style>
.j2-02ab-a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.707 30.036c4.941-3.625 6.297-11.026 5.022-15.713M28.508 27.104l-4.38 2.53l-4.382 2.529V22.045l4.381 2.53Z");
}

.jue9gtbwu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.947 22.603S44.352 20.621 42.263 5.86a37.7 37.7 0 0 0-23.246 5.864C7.612 19.122 5.954 26.35 5.52 32.818c-.418 6.237 5.792 8.962 12.303 9.242c14.505 1.477 24.002-4.758 24.246-16.853c0 0-4.088 5.652-10.132 6.66");
}

.vneiq63ue {
  cx: 23.073px;
  cy: 27.226px;
  r: 10.006px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
