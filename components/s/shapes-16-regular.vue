<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gyvp0kb2i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shapes-16-regular" /></template>
<style>
.gyvp0kb2i {
  fill: currentColor;
  d: path("M5.5 2A3.5 3.5 0 0 0 5 8.965v1.008A4.5 4.5 0 1 1 9.973 5H8.965A3.5 3.5 0 0 0 5.5 2m3 4A2.5 2.5 0 0 0 6 8.5v4A2.5 2.5 0 0 0 8.5 15h4a2.5 2.5 0 0 0 2.5-2.5v-4A2.5 2.5 0 0 0 12.5 6zM7 8.5A1.5 1.5 0 0 1 8.5 7h4A1.5 1.5 0 0 1 14 8.5v4a1.5 1.5 0 0 1-1.5 1.5h-4A1.5 1.5 0 0 1 7 12.5z");
}

</style>
