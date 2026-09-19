<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgt9mib3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-keyboard-control-key" /></template>
<style>
.qgt9mib3p {
  fill: currentColor;
  d: path("M5.71 12.71c.39.39 1.02.39 1.41 0L12 7.83l4.88 4.88a.996.996 0 1 0 1.41-1.41L12.7 5.71a.996.996 0 0 0-1.41 0L5.7 11.3c-.38.38-.38 1.02.01 1.41");
}

</style>
