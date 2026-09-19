<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nkrt0lkxm"/><circle class="wfh_4odcm"/><path class="pq7onzehi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:speaker" /></template>
<style>
.nkrt0lkxm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.5 39.564h-31a4 4 0 0 1-4-4V12.436a4 4 0 0 1 4-4h31a4 4 0 0 1 4 4v23.128a4 4 0 0 1-4 4");
}

.pq7onzehi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.006 34.993a15.5 15.5 0 0 1-3.133-4.5C8.93 28.453 8.45 26.267 8.45 24s.48-4.453 1.426-6.498a15.5 15.5 0 0 1 3.13-4.496l2.687 2.687a11.7 11.7 0 0 0-2.366 3.4c-.715 1.546-1.077 3.195-1.077 4.907s.362 3.361 1.075 4.902a11.7 11.7 0 0 0 2.369 3.406zm21.988 0l-2.687-2.685a11.7 11.7 0 0 0 2.367-3.402c.715-1.546 1.076-3.195 1.076-4.906s-.361-3.36-1.074-4.903a11.8 11.8 0 0 0-2.37-3.403l2.688-2.687a15.5 15.5 0 0 1 3.133 4.499c.944 2.043 1.424 4.229 1.424 6.494s-.48 4.451-1.426 6.497a15.5 15.5 0 0 1-3.13 4.496Z");
}

.wfh_4odcm {
  cx: 24px;
  cy: 24px;
  r: 5.809px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
