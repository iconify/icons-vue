<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogf3a-1dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-duocolor" /></template>
<style>
.ogf3a-1dh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m9 8l-4 4c-.369.369-.369 1 0 1h4a1 1 0 0 1 1 1v6c0 .369.631.369 1 0l8-8c.369-.369.369-1 0-1h-4a1 1 0 0 1-1-1V4c0-.369-.631-.369-1 0z");
}

</style>
