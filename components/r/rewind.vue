<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohyhnv5ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rewind" /></template>
<style>
.ohyhnv5ad {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m18.744 7.204l-6 3.5a1.5 1.5 0 0 0 0 2.592l6 3.5A1.5 1.5 0 0 0 21 15.5v-7a1.5 1.5 0 0 0-2.256-1.296m-9 0l-6 3.5a1.5 1.5 0 0 0 0 2.592l6 3.5A1.5 1.5 0 0 0 12 15.5v-7a1.5 1.5 0 0 0-2.256-1.296");
}

</style>
