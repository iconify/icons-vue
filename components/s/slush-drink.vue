<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xj5iijben"/><path class="dzozkebzt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:slush-drink" /></template>
<style>
.dzozkebzt {
  d: path("M12 5.5v-3h3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xj5iijben {
  d: path("M5 10.5a7 5 0 0 1 14 0Zm1 0L7.5 21h9L18 10.5");
}

</style>
