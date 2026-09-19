<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rawto5c1m"/><path class="ca51ky2cu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qcpr" /></template>
<style>
.ca51ky2cu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.205 20.99q2.7 2.17 4.3 2.46c.37 3.38 2.61 3.28 3.68 1.26q.98-1.48 1.58.17l2.55.07q3.01 2.88 4.59 2.89l7.24.08c0 1.59 3.87 1.64 3.87 0l9.24-.04m-33.28-8.22q.33.46.27 1.12");
}

.rawto5c1m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.865 21.74c5.37-3.91 11.73-2.6 20.55-2.48c2.77 1.29 3.82 7.99 1.22 10.79q-1.64 1.09-2.94 1.09l-17.15-.18c-2.03-.07-3.57-.94-3.99-2.61q-.23-.57-1.05-.57h-1.93c-1.17 1.79-2.38 3.07-6.78 2.11c-4.1-.26-5.59-6.19-4.65-8.39q1.02-2.26 1.85-.32q1.85-2.66 3.05-2.7q2.46-2.44 2.93-.73q1.33.05 2.88-.87q1.28-.32 1.58 4.51z");
}

</style>
