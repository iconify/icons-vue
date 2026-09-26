<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nkbidnsgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-off-sharp" /></template>
<style>
.nkbidnsgu {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M21 21L3 21L3 3M3 9L9 9M3 15L15 15M12 12L12 21M7.6569 3L21 3L21 16.3431M13.6569 9L21 9M1.7071 1.7071L22.2929 22.2929");
}

</style>
