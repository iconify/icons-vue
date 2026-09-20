<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t70mcwbqq"/><path class="g2wj9jbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ulys" /></template>
<style>
.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

.t70mcwbqq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.67 20v8h4m5.384-8l-2.6 4l-2.6-4m2.6 8v-4m4.576 3.1c.5.6 1.1.9 2 .9h1.2c1.1 0 2-.9 2-2s-.9-2-2-2h-1.3c-1.1 0-2-.9-2-2s.9-2 2-2h1.2c.9 0 1.5.2 2 .9M11.77 20v5.3c0 1.5 1.2 2.7 2.6 2.7s2.7-1.2 2.7-2.7V20");
}

</style>
