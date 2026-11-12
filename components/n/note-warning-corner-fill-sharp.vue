<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nut7ld4hj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-warning-corner-fill-sharp" /></template>
<style>
.nut7ld4hj {
  fill: currentColor;
  d: path("M4 3h16a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H9v11a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1m14 11v4a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0m-1 6h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2");
}

</style>
