<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="v98wtw7an"/><path class="vqih-ynua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pendant-light-sharp" /></template>
<style>
.v98wtw7an {
  d: path("M12 2.75v7m-3.75 0h7.5l4 6.5l.642 1.004l-1.192-.004H4.8l-1.192.004l.642-1.004Z");
}

.vqih-ynua {
  d: path("M9.75 17.25a2.25 2.25 0 0 0 4.5 0Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
