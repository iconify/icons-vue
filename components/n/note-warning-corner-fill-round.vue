<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ee2e1bb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-warning-corner-fill-round" /></template>
<style>
.ee2e1bb3y {
  fill: currentColor;
  d: path("M12 9a3 3 0 0 0-3 3v8a1 1 0 0 1-1 1a5 5 0 0 1-3.536-1.464A4.98 4.98 0 0 1 3 16V8a5 5 0 0 1 5-5h8c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 21 8a1 1 0 0 1-1 1Zm6 9a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0Zm-1 2h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2");
}

</style>
