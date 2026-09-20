<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q52nfw-vz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:remote-16-filled" /></template>
<style>
.q52nfw-vz {
  fill: currentColor;
  d: path("M13.796 3.264a.75.75 0 1 0-1.092-1.028l-4 4.25a.75.75 0 0 0 0 1.028l4 4.25a.75.75 0 1 0 1.092-1.028L10.28 7zm-10.5.972a.75.75 0 1 0-1.092 1.028L5.72 9l-3.516 3.736a.75.75 0 1 0 1.092 1.028l4-4.25a.75.75 0 0 0 0-1.028z");
}

</style>
