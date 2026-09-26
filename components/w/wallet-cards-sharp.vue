<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ykze3k15m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wallet-cards-sharp" /></template>
<style>
.ykze3k15m {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 4L22 4L22 20L2 20L2 4ZM2 8L22 8M2 12L6 12L6 13C6 14.1046 6.8954 15 8 15C9.1046 15 10 14.1046 10 13L10 12L22 12");
}

</style>
