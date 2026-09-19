<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qt96htvnz"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:retrica" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.qt96htvnz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 14.837a9.16 9.16 0 0 1 9.163 9.161V24a9.16 9.16 0 0 1-9.161 9.163H24a9.16 9.16 0 0 1-9.163-9.161V24a9.16 9.16 0 0 1 9.161-9.163zm15.476 24.639h-6.313v-6.314h6.313zm-3.157 0v-6.314m-3.156 3.157h6.313");
}

</style>
