<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4p6zwb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:share-2-sharp" /></template>
<style>
.l4p6zwb9s {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12.5 5.0001L12.5 9.5001C7.5375 9.724 3.4917 13.5568 2.9999 18.4999C5.2767 15.9472 8.5347 14.4875 11.9552 14.4875C12.1369 14.4875 12.3185 14.4917 12.5 14.4999L12.5 18.9999L20.9999 12L12.5 5.0001Z");
}

</style>
