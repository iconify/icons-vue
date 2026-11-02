<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k5vmspb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pause-fill-sharp" /></template>
<style>
.k5vmspb9d {
  fill: currentColor;
  d: path("M9 2a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm11 0a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1h-5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Z");
}

</style>
