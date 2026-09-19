<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z1u8efb0o"/><path class="s0nw53bsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:matipay" /></template>
<style>
.s0nw53bsu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.375 27.5l8 8l16-16");
}

.z1u8efb0o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.125 30.75v6.75c0 3.324-2.676 6-6 6h-13.5c-3.324 0-6-2.676-6-6v-27c0-3.324 2.676-6 6-6h13.5c3.324 0 6 2.676 6 6v12.25");
}

</style>
