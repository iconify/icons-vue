<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sdg4b0b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:quote-single-right-bulk-round" /></template>
<style>
.sdg4b0b2s {
  fill: currentColor;
  d: path("M14 12v-2a2 2 0 1 0-2 2Zm2 1c0 1.33-.522 2.597-1.464 3.536A5 5 0 0 1 11 18a1 1 0 0 1 0-2c1.27 0 2.405-.804 2.83-2H12a4 4 0 1 1 4-4Z");
}

</style>
