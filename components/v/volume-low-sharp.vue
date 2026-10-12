<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="he03gbblk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:volume-low-sharp" /></template>
<style>
.he03gbblk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 9.5V8h3.7l4.4-3.7l1.569-1.406L13.35 5v14l.069 2.106L11.85 19.7L7.45 16h-3.7v-1.5Zm12.25.75L17.715 12L16 13.75");
}

</style>
