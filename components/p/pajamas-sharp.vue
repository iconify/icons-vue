<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="fi4giqd8r"/><path class="bk13tybii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pajamas-sharp" /></template>
<style>
.bk13tybii {
  d: path("M9.25 3.5L12 6.75l2.75-3.25M12 6.75v14M18.85 9a2.75 2.75 0 1 0 0 4.5a2.6 2.6 0 0 1 0-4.5Z");
}

.fi4giqd8r {
  d: path("M9.75 3.25h5.75l1.1.58l2.05 1.09l1.1.58l.13 1.24l1.24 12.02l.13 1.24l-1.22.26l-1.06.23q-1.22.26-2.47.26h-9q-1.25 0-2.47-.26l-1.06-.23L2.75 20l.13-1.24L4.12 6.74l.13-1.24l1.1-.58L7.4 3.83l1.1-.58z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
