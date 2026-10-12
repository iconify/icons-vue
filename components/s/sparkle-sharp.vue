<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w_y7iedua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sparkle-sharp" /></template>
<style>
.w_y7iedua {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.5 6q.78 5.72 6.5 6.5q-5.72.78-6.5 6.5q-.78-5.72-6.5-6.5q5.72-.78 6.5-6.5ZM5.75 3l.33 2.42l2.42.33l-2.42.33l-.33 2.42l-.33-2.42L3 5.75l2.42-.33zm12.5 12.5l.33 2.42l2.42.33l-2.42.33l-.33 2.42l-.33-2.42l-2.42-.33l2.42-.33z");
}

</style>
