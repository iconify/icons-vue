<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="dib_i1bmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:search-visual-28-regular" /></template>
<style>
.dib_i1bmt {
  fill: currentColor;
  d: path("M3.75 16.5a.75.75 0 0 1 .75.75v4a2.25 2.25 0 0 0 2.25 2.25h4a.75.75 0 0 1 0 1.5h-4A3.75 3.75 0 0 1 3 21.25v-4a.75.75 0 0 1 .75-.75m20.5 0a.75.75 0 0 1 .75.75v4A3.75 3.75 0 0 1 21.25 25h-4a.75.75 0 0 1 0-1.5h4a2.25 2.25 0 0 0 2.25-2.25v-4a.75.75 0 0 1 .75-.75M14 10.5a3.5 3.5 0 1 1 0 7a3.5 3.5 0 0 1 0-7m0 1.5a2 2 0 1 0 0 4a2 2 0 0 0 0-4m-3.25-9a.75.75 0 0 1 0 1.5h-4A2.25 2.25 0 0 0 4.5 6.75v4a.75.75 0 0 1-1.5 0v-4A3.75 3.75 0 0 1 6.75 3zm10.5 0A3.75 3.75 0 0 1 25 6.75v4a.75.75 0 0 1-1.5 0v-4a2.25 2.25 0 0 0-2.25-2.25h-4a.75.75 0 0 1 0-1.5zM8.5 7.25a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5");
}

</style>
