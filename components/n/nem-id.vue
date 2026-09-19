<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cnxwcob9w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nem-id" /></template>
<style>
.cnxwcob9w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.972 23.514a6.264 6.264 0 1 1 .84 3.131m-.84-3.131H5.796c-1.279 0-2.296.706-2.296 1.697v5.54m6.488-7.237V30.7");
}

</style>
