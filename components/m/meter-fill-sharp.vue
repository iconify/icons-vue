<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jf0maxuoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:meter-fill-sharp" /></template>
<style>
.jf0maxuoz {
  fill: currentColor;
  d: path("M15 3a1 1 0 0 1 2 0h4a1 1 0 0 1 1 1v17a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1h4a1 1 0 0 1 2 0ZM9 6H7v5h2Zm2 0v5h2V6Zm6 0h-2v5h2ZM8 16a1 1 0 0 0 0 2h8a1 1 0 0 0 0-2Z");
}

</style>
