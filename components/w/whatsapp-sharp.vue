<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hguwsyb5j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:whatsapp-sharp" /></template>
<style>
.hguwsyb5j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M11 9H9v1a5 5 0 0 0 5 5h1v-2M3 21l1-5a8.944 8.944 0 1 1 4 4Z");
}

</style>
