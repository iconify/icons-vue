<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bskm_j5ol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rename-a-16-filled" /></template>
<style>
.bskm_j5ol {
  fill: currentColor;
  d: path("M12 1a.5.5 0 0 1 0 1h-1v12h1a.5.5 0 0 1 0 1H9a.5.5 0 0 1 0-1h1V2H9a.5.5 0 0 1 0-1zM6.19 8H4.81l.69-1.532zM9 13H3.5A2.5 2.5 0 0 1 1 10.5v-5A2.5 2.5 0 0 1 3.5 3H9zM5.5 4.75a.5.5 0 0 0-.456.295l-2.25 5a.5.5 0 0 0 .912.41L4.36 9h2.28l.654 1.455a.5.5 0 0 0 .912-.41l-2.25-5A.5.5 0 0 0 5.5 4.75m7-1.75A2.5 2.5 0 0 1 15 5.5v5a2.5 2.5 0 0 1-2.5 2.5H12V3z");
}

</style>
