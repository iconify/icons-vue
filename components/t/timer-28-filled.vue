<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="u6t97c_mi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:timer-28-filled" /></template>
<style>
.u6t97c_mi {
  fill: currentColor;
  d: path("M10.75 3a.75.75 0 0 0 0 1.5h6.5a.75.75 0 0 0 0-1.5zM4 16C4 10.477 8.477 6 14 6s10 4.477 10 10s-4.477 10-10 10S4 21.523 4 16m10.75-5.75a.75.75 0 0 0-1.5 0v6a.75.75 0 0 0 1.5 0zm6.47-4.03a.75.75 0 0 1 1.06 0l1.5 1.5a.75.75 0 0 1-1.06 1.06l-1.5-1.5a.75.75 0 0 1 0-1.06");
}

</style>
