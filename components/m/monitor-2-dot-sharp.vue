<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pwhpj2omy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:monitor-2-dot-sharp" /></template>
<style>
.pwhpj2omy {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 3L2 3L2 17L22 17L22 12M12 17L12 21M7 21L17 21M22 6C22 7.6569 20.6569 9 19 9C17.3431 9 16 7.6569 16 6C16 4.3431 17.3431 3 19 3C20.6569 3 22 4.3431 22 6Z");
}

</style>
