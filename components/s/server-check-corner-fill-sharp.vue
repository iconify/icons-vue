<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ktqn4bbjp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-check-corner-fill-sharp" /></template>
<style>
.ktqn4bbjp {
  fill: currentColor;
  d: path("M21 3a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V4a1 1 0 0 1 1-1ZM7.01 6H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M10 14v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-6a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1m3.707 2.293l2.226 2.226l4.299-5.159a1 1 0 1 1 1.536 1.28l-5 6a1 1 0 0 1-1.475.067l-3-3a.999.999 0 1 1 1.414-1.414M7.01 16H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
