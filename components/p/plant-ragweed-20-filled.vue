<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y0s-q70-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:plant-ragweed-20-filled" /></template>
<style>
.y0s-q70-o {
  fill: currentColor;
  d: path("M7.5 4.5a2.5 2.5 0 1 1 4.94.548a2 2 0 0 1 .883 3.452A2 2 0 0 1 12 12h-1.5v4.293l3.146-3.147a.5.5 0 0 1 .708.708L10.5 17.707v.793a.5.5 0 0 1-1 0v-.793l-3.854-3.853a.5.5 0 0 1 .708-.708L9.5 16.293V12H8a2 2 0 0 1-1.323-3.5a2 2 0 0 1 .883-3.452Q7.5 4.783 7.5 4.5");
}

</style>
