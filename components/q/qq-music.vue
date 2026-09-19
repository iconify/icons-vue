<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="q78_tbk2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:qq-music" /></template>
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

.q78_tbk2e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.235 8.5c-3.736 3.173-8.608 4.076-15.715.507l9.44 10.012c4.308 4.307 4.257 8.173 4.5 12.103c.266 4.296-1.537 6.736-4.067 7.805c-3.655 1.544-9.574-.164-11.681-3.526c-1.748-2.787-1.001-7.727 1.621-10.045c4.699-4.153 10.14-3.406 13.84 2.063");
}

</style>
