<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwzylw6-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:medical-cross-sharp" /></template>
<style>
.bwzylw6-z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m14 8.536l4.794-2.768l2 3.464L16 12l4.794 2.768l-2 3.464L14 15.464V21h-4v-5.536l-4.794 2.768l-2-3.464L8 12L3.206 9.232l2-3.464L10 8.536V3h4z");
}

</style>
