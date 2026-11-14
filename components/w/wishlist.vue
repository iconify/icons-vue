<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z8j_1kcdn"/><path class="aeui5abjf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wishlist" /></template>
<style>
.aeui5abjf {
  d: path("m17.75 14l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z8j_1kcdn {
  d: path("M13.055 19.299C12.41 19.749 12 20 12 20S3 14.5 3 8.75C3 6.1 5.1 4 7.75 4C9.5 4 11.1 5 12 6.5C12.9 5 14.5 4 16.25 4C18.9 4 21 6.1 21 8.75c0 1.204-.395 2.397-1.018 3.531");
}

</style>
