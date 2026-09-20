<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u_6wbgnon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:stack-20-filled" /></template>
<style>
.u_6wbgnon {
  fill: currentColor;
  d: path("M4 3a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2zm.268 11A2 2 0 0 0 6 15h6a4 4 0 0 0 4-4V7a2 2 0 0 0-1-1.732V11a3 3 0 0 1-3 3zm2 2A2 2 0 0 0 8 17h4a6 6 0 0 0 6-6V9a2 2 0 0 0-1-1.732V11a5 5 0 0 1-5 5z");
}

</style>
