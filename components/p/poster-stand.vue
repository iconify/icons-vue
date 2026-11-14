<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r6xwxwblj"/><path class="afxdifitn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:poster-stand" /></template>
<style>
.afxdifitn {
  d: path("M12.75 6a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0ZM8.5 13L11 9.5l2 2l1-1l1.5 2.5");
}

.r6xwxwblj {
  d: path("M6.5 2.5h11v13h-11Zm5.5 13V19m-4.5 2.5a4.5 2.5 0 0 1 9 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
