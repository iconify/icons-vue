<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ll0g54h-q"/><path class="k8mekacej"/><circle class="l3mm4ybli"/><path class="ifsl5ebmx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:njuskalo" /></template>
<style>
.ifsl5ebmx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.03 29.084v-6.216a3.767 3.767 0 0 0-3.767-3.767h0a3.767 3.767 0 0 0-3.767 3.767m0 6.216v-9.982");
}

.k8mekacej {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.754 19.102v11.3c0 2.08-1.67 3.767-3.732 3.767h0a3.7 3.7 0 0 1-2.638-1.103");
}

.l3mm4ybli {
  cx: 30.754px;
  cy: 14.581px;
  r: 0.75px;
  fill: currentColor;
}

.ll0g54h-q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29c-2.2 0-4 1.8-4 4v29c0 2.2 1.8 4 4 4h29c2.2 0 4-1.8 4-4v-29c0-2.2-1.8-4-4-4");
}

</style>
