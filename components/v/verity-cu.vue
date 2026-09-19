<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k8-31abzk"/><circle class="b0h3qbbbk"/><path class="haqdf7lee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:verity-cu" /></template>
<style>
.b0h3qbbbk {
  cx: 36.436px;
  cy: 8.98px;
  r: 3.481px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.haqdf7lee {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.743 6.214L25.23 42.5h2.344l8.862-26.746m-17.252-9.54l11.492 26.925");
}

.k8-31abzk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.869 6.214h15.207m9.665 9.54h7.39");
}

</style>
