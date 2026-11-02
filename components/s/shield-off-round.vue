<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q2vctekuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shield-off-round" /></template>
<style>
.q2vctekuj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 3h6a4 4 0 0 1 4 4v3c0 .958.2 1.16 0 2m-2 5c-1.441 1.847-3.721 2.987-6 4c-4.5-2-8-5.5-8-11V7c0-1.105.276-2.276 1-3M3 2l19 19");
}

</style>
