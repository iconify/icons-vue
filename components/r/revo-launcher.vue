<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><circle class="f-5wm485e"/><path class="urer90bcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:revo-launcher" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.f-5wm485e {
  cx: 24px;
  cy: 24px;
  r: 4px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.urer90bcp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.198 33.574h29.605m-24.622 4.844h19.638m-20.908-20.66V9.157h2.802c1.584 0 2.868 1.293 2.868 2.888s-1.284 2.889-2.868 2.889H12.91m2.802 0l2.802 2.822M32.95 12.06a2.14 2.14 0 0 1 2.139 2.14v1.419a2.14 2.14 0 0 1-2.14 2.14h0a2.14 2.14 0 0 1-2.139-2.14v-1.42a2.14 2.14 0 0 1 2.14-2.139m-8.966 4.614a2.137 2.137 0 0 1-3.998-1.065V14.21c0-1.187.957-2.15 2.139-2.15s2.14.963 2.14 2.15v.7h-4.28m5.404-2.854l2.14 5.698l2.139-5.698");
}

</style>
