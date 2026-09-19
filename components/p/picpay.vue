<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hy-z9kbve"/><path class="m736cyb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:picpay" /></template>
<style>
.hy-z9kbve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 12.299v17.768h11.569a11.868 11.868 0 0 0 0-23.736h-5.601M5.5 41.669V30.067M31.758 6.331H42.5v10.742H31.758z");
}

.m736cyb5n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.339 9.912h3.581v3.581h-3.581z");
}

</style>
