<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vm4bfd3ki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:medal-24-filled" /></template>
<style>
.vm4bfd3ki {
  fill: currentColor;
  d: path("M12 14a4 4 0 1 1 0 8a4 4 0 0 1 0-8m5.8-11.912a3.25 3.25 0 0 1 1.786 1.132l.702.878a3.25 3.25 0 0 1 .166 3.83l-4.31 6.459a5.5 5.5 0 0 0-3.914-1.882l.393-.589l4.942-7.413a2.58 2.58 0 0 0 .236-2.415m-11.605 0a2.58 2.58 0 0 0 .237 2.414l5.336 8.003a5.5 5.5 0 0 0-3.913 1.88L3.55 7.93a3.25 3.25 0 0 1 .164-3.831l.7-.876A3.25 3.25 0 0 1 6.195 2.09M15.423 2a1.074 1.074 0 0 1 .893 1.67L14.764 6h-5.53L7.68 3.67A1.075 1.075 0 0 1 8.575 2z");
}

</style>
