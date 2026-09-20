<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi46_txum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:sticky-note-2-sharp" /></template>
<style>
.wi46_txum {
  fill: currentColor;
  d: path("M19 14h-5v5zM3 21V3h18v12l-6 6zm4-7h5v-2H7zm0-4h10V8H7z");
}

</style>
