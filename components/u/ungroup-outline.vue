<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pmo7cdbgc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ungroup-outline" /></template>
<style>
.pmo7cdbgc {
  fill: currentColor;
  d: path("m8.7 16.7l-1.4-1.4l4.3-4.3H8V9h7v7h-2v-3.6zM19 12V5h-7V3h9v9zM5 21q-.825 0-1.412-.587T3 19V3h2v16h16v2z");
}

</style>
