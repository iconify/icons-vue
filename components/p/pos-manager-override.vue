<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uuw0n88zj"/><path class="s8kr769vt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pos-manager-override" /></template>
<style>
.s8kr769vt {
  d: path("M6 6.5h6.5V13H6ZM8 13v6.5l1.25 1.25l1.25-1.25v-1.25h.314M12 16.536V16.5h-1.5V13M9.25 9.75h.01M14.5 18l2.5 2.5l4.5-5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uuw0n88zj {
  d: path("M11.5 6.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

</style>
