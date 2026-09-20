<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kj96k6fch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:subtract-square-multiple-16-filled" /></template>
<style>
.kj96k6fch {
  fill: currentColor;
  d: path("M4 2a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2V4a2 2 0 0 0-2-2zm.5 4.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 1 1 0-1m8.5 4a2.5 2.5 0 0 1-2.5 2.5H3.268A2 2 0 0 0 5 14h5.5a3.5 3.5 0 0 0 3.5-3.5V5a2 2 0 0 0-1-1.732z");
}

</style>
