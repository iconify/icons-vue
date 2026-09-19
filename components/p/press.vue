<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jn63cbcie"/><path class="zv219ab7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:press" /></template>
<style>
.jn63cbcie {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.487 42.5v-37H19.245v37M42.5 5.5h-9.013");
}

.zv219ab7c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.245 5.5h-2.929a10.816 10.816 0 0 0 0 21.632h2.93");
}

</style>
