<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3emepbld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:virtual-network-24-regular" /></template>
<style>
.b3emepbld {
  fill: currentColor;
  d: path("M4.67 7.273a.75.75 0 0 1 1.16.954L2.72 12l3.11 3.774a.75.75 0 0 1-1.16.953l-3.5-4.25a.75.75 0 0 1 0-.954zm13.603-.102a.75.75 0 0 1 1.056.102l3.5 4.25a.75.75 0 0 1 0 .954l-3.5 4.25a.75.75 0 0 1-1.158-.953L21.279 12l-3.108-3.773a.75.75 0 0 1 .102-1.056M7.5 10.75a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m4.5 0a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m4.5 0a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5");
}

</style>
