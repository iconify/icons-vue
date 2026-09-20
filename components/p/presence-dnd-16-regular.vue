<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l1k09e0_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-dnd-16-regular" /></template>
<style>
.l1k09e0_e {
  fill: currentColor;
  d: path("M5.25 7a1 1 0 0 0 0 2h5.5a1 1 0 1 0 0-2zM0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8m8-6a6 6 0 1 0 0 12A6 6 0 0 0 8 2");
}

</style>
