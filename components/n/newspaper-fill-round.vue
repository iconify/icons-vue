<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-rzgbc3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:newspaper-fill-round" /></template>
<style>
.z-rzgbc3p {
  fill: currentColor;
  d: path("M8 3h9a5 5 0 0 1 5 5v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21H8Zm10 4h-6a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2M6 7.099v13.802A5.01 5.01 0 0 1 2 16v-4a5.01 5.01 0 0 1 4-4.901M12 11a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2Zm6 4h-6a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2");
}

</style>
