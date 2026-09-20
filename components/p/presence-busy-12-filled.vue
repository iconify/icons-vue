<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="m0oajvfgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-busy-12-filled" /></template>
<style>
.m0oajvfgn {
  fill: currentColor;
  d: path("M12 6A6 6 0 1 1 0 6a6 6 0 0 1 12 0");
}

</style>
