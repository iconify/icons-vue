<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="df4em2bwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:radio-bulk-round" /></template>
<style>
.df4em2bwd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 12a9 9 0 0 1 9-9a9 9 0 0 1 9 9a9 9 0 0 1-9 9a9 9 0 0 1-9-9");
}

</style>
