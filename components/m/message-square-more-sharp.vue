<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="c-jrmt4kx"/><path clip-rule="evenodd" class="qwar3iq0x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-more-sharp" /></template>
<style>
.c-jrmt4kx {
  d: path("M3 3H21V17H7L3 21V3Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qwar3iq0x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.333 8.667C8.07 8.667 8.667 9.264 8.667 10C8.667 10.736 8.07 11.333 7.333 11.333C6.597 11.333 6 10.736 6 10C6 9.264 6.597 8.667 7.333 8.667ZM12 8.667C12.736 8.667 13.333 9.264 13.333 10C13.333 10.736 12.736 11.333 12 11.333C11.264 11.333 10.667 10.736 10.667 10C10.667 9.264 11.264 8.667 12 8.667ZM16.667 8.667C17.403 8.667 18 9.264 18 10C18 10.736 17.403 11.333 16.667 11.333C15.93 11.333 15.333 10.736 15.333 10C15.333 9.264 15.93 8.667 16.667 8.667Z");
  stroke: none;
}

</style>
