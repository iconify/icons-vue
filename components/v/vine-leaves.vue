<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3do08l5e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:vine-leaves" /></template>
<style>
.b3do08l5e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5L13 6l-2.5 5.5L13 17l-1 4.5M13 6c2-2.5 6-2.5 7.5.5C18 8.75 15 8.5 13 6Zm-2.5 5.5C8.5 9 5 9 3.5 12c2.5 2.25 5 2 7-.5ZM13 17c2-2.5 6-2.5 7.5.5c-2.5 2.25-5.5 2-7.5-.5Z");
}

</style>
