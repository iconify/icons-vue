<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qrzks8m2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mars-sharp" /></template>
<style>
.qrzks8m2e {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15 15C15 18.3137 12.3137 21 9 21C5.6863 21 3 18.3137 3 15C3 11.6863 5.6863 9 9 9C12.3137 9 15 11.6863 15 15ZM14.5 3L21 3L21 9.5M13.2426 10.7574L20.8243 3.1757");
}

</style>
