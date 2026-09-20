<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="oxpyp4blm"/><path class="gw8hlp7jt"/><path class="qc03nfwmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:poe-ai-chat" /></template>
<style>
.gw8hlp7jt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.118 9.3a2.33 2.33 0 0 1 2.331 2.331v.43a3.72 3.72 0 0 0 3.72 3.72a2.33 2.33 0 0 1 2.331 2.331v7.158a2.33 2.33 0 0 1-2.33 2.331a3.72 3.72 0 0 0-3.72 3.72v.43a2.33 2.33 0 0 1-2.332 2.331h-18.72l-3.393 4.112c-.827 1.002-2.454.417-2.454-.882v-5.99a3.72 3.72 0 0 0-3.72-3.72A2.33 2.33 0 0 1 4.5 25.27v-7.158a2.33 2.33 0 0 1 2.33-2.331a3.72 3.72 0 0 0 3.72-3.72v-.43a2.33 2.33 0 0 1 2.332-2.33z");
}

.oxpyp4blm {
  width: 27.145px;
  height: 13.997px;
  x: 10.428px;
  y: 14.741px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 3.077px;
  ry: 3.077px;
}

.qc03nfwmv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.697 20.07a2.477 2.477 0 0 1 4.954 0v2.826a2.477 2.477 0 0 1-4.954 0zm11.652 0a2.477 2.477 0 0 1 4.954 0v2.826a2.477 2.477 0 0 1-4.954 0z");
}

</style>
