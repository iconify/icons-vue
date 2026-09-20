<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ec4b-7b7o"/><circle class="k6r21sbot"/><circle class="mmvz610wk"/><circle class="hlren2rto"/><circle class="ir3fy7vdo"/><path class="wgbjfj4ne"/><circle class="go0hbra0q"/><path class="oggzlmj9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:timee" /></template>
<style>
.ec4b-7b7o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.231 9.606Q19.101 9.5 20 9.5h8q.662 0 1.309.058m7.917 3.239A14.46 14.46 0 0 1 42.5 24v4c0 8.033-6.467 14.5-14.5 14.5h-8c-8.033 0-14.5-6.467-14.5-14.5v-4c0-4.375 1.918-8.286 4.963-10.94");
}

.go0hbra0q {
  cx: 30px;
  cy: 20.5px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.hlren2rto {
  cx: 18px;
  cy: 20.5px;
  r: 1.75px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ir3fy7vdo {
  cx: 24px;
  cy: 22px;
  r: 1px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.k6r21sbot {
  cx: 13.75px;
  cy: 10px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.mmvz610wk {
  cx: 33.75px;
  cy: 10px;
  r: 4.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.oggzlmj9m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.652 35.11c1.62-1.143 3.825-3.79 4.246-6.057c-.5.478-1.566 1.666-2.748 2.143");
}

.wgbjfj4ne {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.5 24.116c-.31-.179-.5-.759-.5-1.116");
}

</style>
