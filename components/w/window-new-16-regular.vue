<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x6g_erw5c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:window-new-16-regular" /></template>
<style>
.x6g_erw5c {
  fill: currentColor;
  d: path("M11.5 2A2.5 2.5 0 0 1 14 4.5v5a2.5 2.5 0 0 1-2.044 2.456A2.5 2.5 0 0 1 9.5 14H6a4 4 0 0 1-4-4V6.5a2.5 2.5 0 0 1 2.043-2.457A2.5 2.5 0 0 1 6.5 2zM4 5.087A1.5 1.5 0 0 0 3 6.5V10a3 3 0 0 0 3 3h3.5a1.5 1.5 0 0 0 1.413-1H6.5A2.5 2.5 0 0 1 4 9.5zM6.5 3A1.5 1.5 0 0 0 5 4.5v5A1.5 1.5 0 0 0 6.5 11h5A1.5 1.5 0 0 0 13 9.5v-5A1.5 1.5 0 0 0 11.5 3zm4 2a.5.5 0 0 1 .5.5V8a.5.5 0 0 1-1 0V6.707L7.354 9.354a.5.5 0 1 1-.708-.708L9.293 6H8a.5.5 0 0 1 0-1z");
}

</style>
