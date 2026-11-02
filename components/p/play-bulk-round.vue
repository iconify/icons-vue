<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp6f-bgms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:play-bulk-round" /></template>
<style>
.mp6f-bgms {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m11.12 3.608l8 5a4 4 0 0 1 0 6.784l-8 5A4.001 4.001 0 0 1 5 17V7a4 4 0 0 1 6.12-3.392");
}

</style>
