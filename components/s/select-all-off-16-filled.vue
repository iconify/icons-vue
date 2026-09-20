<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u96sa-b2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:select-all-off-16-filled" /></template>
<style>
.u96sa-b2b {
  fill: currentColor;
  d: path("M2 4.5A2.5 2.5 0 0 1 4.5 2h5A2.5 2.5 0 0 1 12 4.5v5A2.5 2.5 0 0 1 9.5 12h-5A2.5 2.5 0 0 1 2 9.5zM7 14a2.5 2.5 0 0 1-2-1h4.5A3.5 3.5 0 0 0 13 9.5V4c.607.456 1 1.182 1 2v3.5A4.5 4.5 0 0 1 9.5 14z");
}

</style>
