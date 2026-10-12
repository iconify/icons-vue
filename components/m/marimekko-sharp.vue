<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvjhblw8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:marimekko-sharp" /></template>
<style>
.gvjhblw8d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 2.75h6v6.5h-6zm0 9h6v9.5h-6zm8.5-9h3.25v11h-3.25zm0 13.5h3.25v5h-3.25zM17 2.75h4.25v3.5H17zm0 6h4.25v12.5H17z");
}

</style>
