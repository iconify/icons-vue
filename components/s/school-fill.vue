<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q4vzkacok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:school-fill" /></template>
<style>
.q4vzkacok {
  fill: currentColor;
  d: path("M19 22h-4v-4a3 3 0 1 0-6 0v4H5a3 3 0 0 1-3-3v-6a1 1 0 0 1 .445-.832L5 10.465V7.618l-.553.276a1 1 0 1 1-.894-1.788l8-4a1 1 0 0 1 .894 0l8 4a1 1 0 1 1-.894 1.788L19 7.618v2.847l2.555 1.703A1 1 0 0 1 22 13v6a3 3 0 0 1-3 3M9.236 8.832a3 3 0 1 0 5.527 2.335a3 3 0 0 0-5.527-2.335");
}

</style>
