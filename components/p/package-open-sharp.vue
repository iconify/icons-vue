<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekvzroblj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:package-open-sharp" /></template>
<style>
.ekvzroblj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 10.25h14.5v11H4.75v-1.5Zm-.2-.46l-1.6-3.58l-.2-.46h6l.13.48l.99 3.54l.13.48H4.75zm14.9 0l1.6-3.58l.2-.46h-6l-.13.48l-.99 3.54l-.13.48h5.25zM9.5 14h5");
}

</style>
