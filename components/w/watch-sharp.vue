<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kex830mrk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:watch-sharp" /></template>
<style>
.kex830mrk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 12a5 5 0 1 0 10 0a5 5 0 0 0-10 0m2-4V3h6v5m-6 8v5h6v-5m-3-6v2h2");
}

</style>
