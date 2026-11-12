<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m970tga6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-transpose-fill-sharp" /></template>
<style>
.m970tga6v {
  fill: currentColor;
  d: path("M21 2a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H11a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1ZM7 10a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1V11a1 1 0 0 1 1-1Zm8 5v1.586l4.293-4.293a.999.999 0 1 1 1.414 1.414L16.414 18H18a1 1 0 0 1 0 2h-4a1 1 0 0 1-1-1v-4a1 1 0 0 1 2 0");
}

</style>
