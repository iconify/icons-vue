<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n176x-mju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-meeting-room" /></template>
<style>
.n176x-mju {
  fill: currentColor;
  d: path("M19 19V4h-4V3H5v16H3v2h12V6h2v15h4v-2zm-6 0H7V5h6zm-3-8h2v2h-2z");
}

</style>
