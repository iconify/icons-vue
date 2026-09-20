<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gih-sn7fu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:smartwatch-dot-20-filled" /></template>
<style>
.gih-sn7fu {
  fill: currentColor;
  d: path("M13.507 2.685A2 2 0 0 0 12 2H8a2 2 0 0 0-2 2v.17c.313-.11.65-.17 1-.17h6.035c.069-.476.232-.921.472-1.315M13.036 5H7a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2v-2a1 1 0 0 0 1-1V9a1 1 0 0 0-1-1v-.337A3.5 3.5 0 0 1 13.036 5M7 16c-.35 0-.687-.06-1-.17V16a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2v-.17c-.313.11-.65.17-1 .17zM19 4.5a2.5 2.5 0 1 0-5 0a2.5 2.5 0 0 0 5 0");
}

</style>
