<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="zymwp5nox"/><rect class="x0v6p-wzr"/><path class="n9t-_u3uh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vizio" /></template>
<style>
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

.n9t-_u3uh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.1 19.75h5.632l-5.632 8.5h5.632");
}

.x0v6p-wzr {
  width: 5.631px;
  height: 8.5px;
  x: 31.411px;
  y: 19.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 2.816px;
  ry: 2.816px;
}

.zymwp5nox {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.797 19.75v8.5m10.248-8.5v8.5m-12.456-8.5l-2.816 8.5l-2.815-8.5");
}

</style>
