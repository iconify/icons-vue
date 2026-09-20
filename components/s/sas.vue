<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ot_6h26bd"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sas" /></template>
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

.ot_6h26bd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.5 28.67c.565.954 1.422 1.31 2.701 1.31h1.77c1.649 0 3.22-1.336 3.51-2.984l.003-.013c.29-1.647-.81-2.983-2.458-2.983h-1.953c-1.65 0-2.75-1.337-2.46-2.987c.292-1.653 1.868-2.993 3.521-2.993h1.761c1.28 0 2.136.356 2.701 1.31m12.808 9.34c.565.954 1.422 1.31 2.701 1.31h1.77c1.648 0 3.22-1.336 3.51-2.984l.003-.013c.29-1.647-.81-2.983-2.458-2.983h-1.953c-1.65 0-2.75-1.337-2.46-2.987c.292-1.653 1.868-2.993 3.52-2.993H36.8c1.28 0 2.136.356 2.701 1.31M26.76 26.018h-5.299m-2.506 3.962l7.565-11.96l.358 11.96");
}

</style>
