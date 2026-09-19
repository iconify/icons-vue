<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="cpk0fnbgt"/><path class="srfj-ibbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zetteria" /></template>
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

.srfj-ibbp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.467 13.102c11.628 6.714 33.124 4.88 38.68 3.392c-7.3 7.3-31.306 14.273-40.554 14.273c7.347 7.347 27.79 8.484 40.367 1.223M16.915 6.628l1.09-.438m3.947-2.333l1.067-.315m8.091 1.823l1.067-.315m-6.245 3.143l.987-.353m8.109 2.03l1.034-.315");
}

</style>
