<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j5khexkgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:patient-20-regular" /></template>
<style>
.j5khexkgu {
  fill: currentColor;
  d: path("M10 4a2 2 0 1 0 0 4a2 2 0 0 0 0-4M9 6a1 1 0 1 1 2 0a1 1 0 0 1-2 0m-2.5 8.5a.5.5 0 0 0 0 1h7a.5.5 0 0 0 0-1zM4 4a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2zm10-1H6a1 1 0 0 0-1 1v8h2v-2a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v2h2V4a1 1 0 0 0-1-1m-2 7H8v2h4zm-7 3v3a1 1 0 0 0 1 1h8a1 1 0 0 0 1-1v-3z");
}

</style>
