<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="onilj4tim"/><path class="qibyr3bao"/><path class="io72nworo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:organic-leaf-sharp" /></template>
<style>
.io72nworo {
  d: path("m9.4 11.65l1.75 1.75l2.75-3.25M8 16l-1.25 1.25");
}

.onilj4tim {
  d: path("m12.71 3.31l.63.5l.7.56l.9-.13l.79-.12l.9-.13l.33.84l.29.75l.34.83l.83.34l.75.29l.84.34l-.13.89l-.12.79l-.13.9l.56.7l.5.63l.56.71l-.56.71l-.5.63l-.56.7l.13.9l.12.79l.13.9l-.84.33l-.75.29l-.83.34l-.34.83l-.29.75l-.33.84l-.9-.13l-.79-.12l-.9-.13l-.7.56l-.63.5l-.71.56l-.71-.56l-.63-.5l-.7-.56l-.9.13l-.79.12l-.89.13l-.34-.84l-.29-.75l-.34-.83l-.83-.34l-.75-.29l-.84-.33l.13-.9l.12-.79l.13-.9l-.56-.7l-.5-.63l-.56-.71l.56-.71l.5-.63l.56-.7l-.13-.9l-.12-.79l-.13-.9l.84-.33l.75-.29l.83-.34l.34-.83l.29-.75l.33-.84l.9.13l.79.12l.9.13l.7-.56l.63-.5l.71-.56z");
}

.qibyr3bao {
  d: path("M8 16q8.37.12 8.25-8.25Q7.88 7.63 8 16Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
