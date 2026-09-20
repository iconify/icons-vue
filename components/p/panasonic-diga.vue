<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xwotbdn_u"/><path class="zy_an-bmu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:panasonic-diga" /></template>
<style>
.xwotbdn_u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 31.426c17.863 0 38.213-1.91 39-8.052c0-2.621-5.101-7.128-30.334-6.781z");
}

.zy_an-bmu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.633 21.751c.013 1.05-4.431 1.953-9.926 2.019s-9.96-.732-9.973-1.78c-.012-1.05 4.432-1.954 9.926-2.02h.001c5.495-.065 9.96.732 9.972 1.781");
}

</style>
