<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mucq5ebko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:versus-sharp" /></template>
<style>
.mucq5ebko {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 7l3.75 10L11 7m8.75 1.5L19 7h-4.75v2.4c0 3.1 5.5 1.9 5.5 5.1c0 1.6-1.25 2.5-2.85 2.5h-2.1l-.8-1.6");
}

</style>
