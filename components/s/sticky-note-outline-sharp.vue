<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvja534ew"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sticky-note-outline-sharp" /></template>
<style>
.hvja534ew {
  fill: currentColor;
  d: path("M15.577 20H4V4h16v11.577zM15 19v-4h4V5H5v14zm-3.5-3.5h1v-6h3v-1h-7v1h3zM5 19V5z");
}

</style>
