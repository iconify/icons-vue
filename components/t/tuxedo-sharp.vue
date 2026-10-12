<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="h9256c73q"/><path class="w7ov40brf"/><path class="hc7_vbkcy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tuxedo-sharp" /></template>
<style>
.h9256c73q {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 3.25h7l1.27.79l1.46.92l1.27.79l.1 1.5l.8 12l.1 1.5H2.75l.1-1.5l.8-12l.1-1.5l1.27-.79l1.46-.92l1.27-.79z");
}

.hc7_vbkcy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 10.75h.01M12 14h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.w7ov40brf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.62 5.67l-.99-.84l-.38-.33v3l.38-.33l.99-.84l.76-.66l.99-.84l.38-.33v3l-.38-.33l-.99-.84zM7 3.5c.6 4.25 1.5 7.75 3 11m7-11c-.6 4.25-1.5 7.75-3 11");
}

</style>
