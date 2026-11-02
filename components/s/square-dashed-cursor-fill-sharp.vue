<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1b1zo4wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-cursor-fill-sharp" /></template>
<style>
.z1b1zo4wk {
  fill: currentColor;
  d: path("M2 3a1 1 0 0 1 1-1h3a1 1 0 0 1 0 2H4v2a1 1 0 0 1-2 0Zm12-1a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Zm7 0a1 1 0 0 1 1 1v3a1 1 0 0 1-2 0V4h-2a1 1 0 0 1 0-2ZM9.316 8.051l12 4a1 1 0 0 1-.073 1.919l-2.287.572l1.751 1.751a1 1 0 0 1 0 1.414l-3 3a1 1 0 0 1-1.414 0l-1.751-1.751l-.572 2.287a1 1 0 0 1-1.919.073l-4-12a1.001 1.001 0 0 1 1.265-1.265M2 10a1 1 0 0 1 2 0v4a1 1 0 0 1-2 0Zm1 12a1 1 0 0 1-1-1v-3a1 1 0 0 1 2 0v2h2a1 1 0 0 1 0 2Z");
}

</style>
