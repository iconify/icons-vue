<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m3aq3xbnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-available-16-filled" /></template>
<style>
.m3aq3xbnf {
  fill: currentColor;
  d: path("M8 16A8 8 0 1 0 8 0a8 8 0 0 0 0 16m3.707-9.293l-4.003 4a1 1 0 0 1-1.415 0l-1.997-2a1 1 0 1 1 1.416-1.414l1.29 1.293l3.295-3.293a1 1 0 0 1 1.414 1.414");
}

</style>
