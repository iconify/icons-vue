<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="as_k35b3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:thermos-sharp" /></template>
<style>
.as_k35b3q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.75 2.75H14l.12.74l.26 1.52l.12.74h-7l.12-.74l.26-1.52l.12-.74zM7 8.75h8v12.5H7zM15 11h3.25v7H15");
}

</style>
