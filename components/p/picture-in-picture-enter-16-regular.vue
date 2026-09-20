<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wsrr4-b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:picture-in-picture-enter-16-regular" /></template>
<style>
.wsrr4-b2s {
  fill: currentColor;
  d: path("M3.5 2A2.5 2.5 0 0 0 1 4.5v5A2.5 2.5 0 0 0 3.5 12H7v-1H3.5A1.5 1.5 0 0 1 2 9.5v-5A1.5 1.5 0 0 1 3.5 3h8A1.5 1.5 0 0 1 13 4.5V8h1V4.5A2.5 2.5 0 0 0 11.5 2zm.854 2.646a.5.5 0 1 0-.708.708L5.293 7H4.5a.5.5 0 0 0 0 1h2a.5.5 0 0 0 .351-.144l.005-.005A.5.5 0 0 0 7 7.5v-2a.5.5 0 0 0-1 0v.793zM9 9a1 1 0 0 0-1 1v3a1 1 0 0 0 1 1h5a1 1 0 0 0 1-1v-3a1 1 0 0 0-1-1z");
}

</style>
