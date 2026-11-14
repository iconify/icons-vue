<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v_-mc7bkx"/><path class="fuzri4hge"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:plasma-ball" /></template>
<style>
.fuzri4hge {
  d: path("M9.5 17L8 21.5h8L14.5 17m-4-7a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm.25-1l-2-.25l-2-4M13.25 9l2-.25l2-4");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v_-mc7bkx {
  d: path("M4.5 10a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0Z");
}

</style>
