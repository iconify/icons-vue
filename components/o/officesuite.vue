<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yoy-wpmuw"/><path class="tgb2drb9m"/><path class="iaxlega_u"/><path class="gnl4b3bad"/><path class="r-xl6tbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:officesuite" /></template>
<style>
.gnl4b3bad {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.669 5.662l5.277 9.143H42.5l-5.277-9.143zM26.639 24l-5.308 9.195l5.277 9.143l5.308-9.196z");
}

.iaxlega_u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.669 5.662l-5.308 9.196L26.639 24l5.307-9.195zm5.277 9.143L26.639 24h10.554l5.307-9.195z");
}

.r-xl6tbxy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.916 33.142l-5.308 9.196h10.555l5.307-9.196zM26.639 24l5.277 9.142H42.47L37.193 24z");
}

.tgb2drb9m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.084 24l-5.307 9.195h10.554L26.639 24zm-5.277-9.142L16.084 24h10.555l-5.278-9.142z");
}

.yoy-wpmuw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.807 14.858L5.5 24.053l5.277 9.142L16.084 24z");
}

</style>
