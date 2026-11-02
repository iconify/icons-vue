<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dvibibz6h"/><path class="vfitpdb6h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sheep-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dvibibz6h {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 12.268a3.1 3.1 0 0 1-2.201-.875c-1.36-1.308-1.46-3.521.005-4.792c-.41-1.896.998-3.606 2.871-3.836a3.1 3.1 0 0 1 2.217.569c1.659-1.78 4.556-1.78 6.216 0a3.1 3.1 0 0 1 2.217-.569c1.873.23 3.281 1.94 2.871 3.836c1.465 1.271 1.365 3.484.005 4.792a3.1 3.1 0 0 1-2.201.875V17c0 1.554-.49 3.007-1.794 3.939C15.008 21.794 13.435 22 12 22s-3.008-.206-4.206-1.061C6.49 20.007 6 18.554 6 17Z");
}

.vfitpdb6h {
  d: path("M10 12h.01a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2m4 0h.01a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2m-9.684 3.949a1.001 1.001 0 0 1-.632-1.898l3-1a1.001 1.001 0 0 1 .632 1.898Zm16-1.898a1.001 1.001 0 0 1-.632 1.898l-3-1a1.001 1.001 0 0 1 .632-1.898ZM12 17h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

</style>
