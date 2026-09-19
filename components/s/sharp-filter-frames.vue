<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwljlgjyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-filter-frames" /></template>
<style>
.zwljlgjyp {
  fill: currentColor;
  d: path("M22 4h-6l-4-4l-4 4H2v18h20zm-2 16H4V6h4.52l3.52-3.5L15.52 6H20zM18 8H6v10h12");
}

</style>
