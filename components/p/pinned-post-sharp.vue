<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-4hdc_ko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pinned-post-sharp" /></template>
<style>
.w-4hdc_ko {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 8.75h12.5v12.5H2.75zM6.25 13h5m-5 4h5.5m2.87-11.38l3.76 3.76l.42.42l.07-.6l.21-1.63l.07-.6l.43-.42l1.09-1.1l.43-.42l-.42-.42l-1.29-1.29l-.42-.42l-.42.43l-1.1 1.09l-.42.43l-.6.07l-1.63.21l-.6.07zM16.5 7.5l-3 3");
}

</style>
