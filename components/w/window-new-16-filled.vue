<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="utwq2haav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:window-new-16-filled" /></template>
<style>
.utwq2haav {
  fill: currentColor;
  d: path("M11.5 2A2.5 2.5 0 0 1 14 4.5v5a2.5 2.5 0 0 1-2.044 2.456A2.5 2.5 0 0 1 9.5 14H6a4 4 0 0 1-4-4V6.5a2.5 2.5 0 0 1 2.043-2.457A2.5 2.5 0 0 1 6.5 2zM4 5.087A1.5 1.5 0 0 0 3 6.5V10a3 3 0 0 0 3 3h3.5a1.5 1.5 0 0 0 1.413-1H6.5A2.5 2.5 0 0 1 4 9.5zM8 5a.5.5 0 0 0 0 1h1.293L6.646 8.646a.5.5 0 1 0 .708.708L10 6.707V8a.5.5 0 0 0 1 0V5.5a.5.5 0 0 0-.5-.5z");
}

</style>
