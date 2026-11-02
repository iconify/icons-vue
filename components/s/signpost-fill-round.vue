<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eop8onyec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:signpost-fill-round" /></template>
<style>
.eop8onyec {
  fill: currentColor;
  d: path("M13 5h2c1.317 0 2.748.335 3.707 1.293l1 1a2.414 2.414 0 0 1 0 3.414l-1 1C17.748 12.665 16.317 13 15 13h-2v8a1 1 0 0 1-2 0v-8H7a4 4 0 0 1 0-8h4V3a1 1 0 0 1 2 0Z");
}

</style>
