<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zryrv5lrf"/><rect transform="rotate(-45 19.707 19.717)" class="irwvxm_al"/><rect transform="rotate(-45 28.9 28.9)" class="t_p_4ibbd"/><path class="yrv2msb8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:melonds" /></template>
<style>
.irwvxm_al {
  width: 21px;
  height: 10px;
  x: 9.21px;
  y: 14.71px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

.t_p_4ibbd {
  width: 21px;
  height: 10px;
  x: 18.4px;
  y: 23.9px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2px;
}

.yrv2msb8a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.339 32.642l2.828-2.829l2.829 2.829l-2.829 2.828zm7.47-7.474l2.828-2.829l2.829 2.829l-2.829 2.828zm-14.701-3.69l6.364-6.364l2.828 2.828l-6.364 6.364z");
}

.zryrv5lrf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43 27.67L27.67 43a5.18 5.18 0 0 1-7.34 0L5 27.67a5.18 5.18 0 0 1 0-7.34L20.33 5a5.18 5.18 0 0 1 7.34 0L43 20.33a5.18 5.18 0 0 1 0 7.34");
}

</style>
