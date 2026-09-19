<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="eqh_3kbrt"/><path class="qplsfzbym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:translate" /></template>
<style>
.eqh_3kbrt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
}

.qplsfzbym {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.692 44.432L17.308 3.568m5.121 33.069l-5.656-17.402L10.9 36.637m1.958-5.873h7.613m2.538-16.931h14.806m-9.266-2.54v8.924c0 1.931.298 4.268 1.779 5.515m-4.822 2.864q.294.045.592.043c3.356 0 5.841-4.324 7.654-10.594m-10.42 3.918c1.513-2.372 4.799-4.142 8.707-4.152c3.582-.01 6.514 2.642 6.514 6.016c0 3.136-2.549 4.952-6.413 5.682");
}

</style>
