<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<ellipse class="x9p-g_bjf"/><path class="h9bugibpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mitidapp" /></template>
<style>
.h9bugibpy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.185 26.048c-5.315.027-9.707 3.239-9.685 9.349h19.37c.015-5.947-4.37-9.376-9.685-9.349m12.668-13.445v22.794h6.514C40.077 35.415 43.53 30.254 43.5 24s-3.24-11.422-10.133-11.396z");
}

.x9p-g_bjf {
  cx: 14.185px;
  cy: 17.762px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 5.112px;
  ry: 5.159px;
}

</style>
