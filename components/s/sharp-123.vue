<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eetr2xbnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-123" /></template>
<style>
.eetr2xbnj {
  fill: currentColor;
  d: path("M7 15H5.5v-4.5H4V9h3zm6.5-1.5h-3v-1h3V9H9v1.5h3v1H9V15h4.5zm6 1.5V9H15v1.5h3v1h-2v1h2v1h-3V15z");
}

</style>
