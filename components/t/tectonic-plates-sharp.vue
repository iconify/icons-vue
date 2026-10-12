<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ckxptwbdj"/><path class="op8wdh-xc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tectonic-plates-sharp" /></template>
<style>
.ckxptwbdj {
  d: path("M3.5 11.5H13l-.18.73l-1.14 4.54l-.18.73H2.75v-6z");
}

.op8wdh-xc {
  d: path("M13.25 13.5h8v6H11l.18-.73l1.14-4.54l.18-.73zm-9.75-7H9M7.25 4.75L9 6.5L7.25 8.25M20.5 6.5H15m1.75-1.75L15 6.5l1.75 1.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
