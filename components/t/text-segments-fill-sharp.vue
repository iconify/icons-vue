<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fm1m3dxwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-segments-fill-sharp" /></template>
<style>
.fm1m3dxwz {
  fill: currentColor;
  d: path("M10 4a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1Zm11 0a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1h-7a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1Zm-8 9a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1v-5a1 1 0 0 1 1-1Zm8 0a1 1 0 0 1 1 1v5a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-5a1 1 0 0 1 1-1Z");
}

</style>
