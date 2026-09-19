<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2wj9jbhp"/><path class="n20fo5b5c"/><circle class="wn33yqb7d"/><path class="dsnr0dllm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pi-1" /></template>
<style>
.dsnr0dllm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.993 22.014v8.781");
}

.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.n20fo5b5c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.257 30.795V17.541h4.34c2.453 0 4.441 1.993 4.441 4.451s-1.988 4.451-4.441 4.451h-4.34");
}

.wn33yqb7d {
  cx: 29.993px;
  cy: 17.955px;
  r: 0.75px;
  fill: currentColor;
}

</style>
