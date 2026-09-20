<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="ig6bpsbwo"/><ellipse class="tboscobjx"/><path class="cpd1msbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:toyota" /></template>
<style>
.cpd1msbbe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M36.98 13.802c1.652 1.071 2.533 2.324 2.533 3.604c0 3.635-6.946 6.581-15.513 6.581s-15.513-2.946-15.513-6.58c0-1.284.883-2.538 2.542-3.611");
}

.ig6bpsbwo {
  cx: 24px;
  cy: 24px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 20.5px;
  ry: 13.175px;
}

.tboscobjx {
  cx: 24px;
  cy: 24.872px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4.958px;
  ry: 12.303px;
}

</style>
