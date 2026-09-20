<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xzgnwdb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:patient-20-filled" /></template>
<style>
.xzgnwdb8o {
  fill: currentColor;
  d: path("M10 4a2 2 0 1 0 0 4a2 2 0 0 0 0-4M6.5 14.5a.5.5 0 0 0 0 1h7a.5.5 0 0 0 0-1zM4 4a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2zm10-1H6a1 1 0 0 0-1 1v8h2v-2a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v2h2V4a1 1 0 0 0-1-1M5 13v3a1 1 0 0 0 1 1h8a1 1 0 0 0 1-1v-3z");
}

</style>
