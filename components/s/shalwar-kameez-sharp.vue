<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="r-x_e9bjv"/><path class="ak1wjomja"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:shalwar-kameez-sharp" /></template>
<style>
.ak1wjomja {
  d: path("M9.75 3L12 5.25L14.25 3M8.5 15.5H16l.09.49l.82 4.77l.09.49h-3.75l-.17-.47l-.91-2.56l-.17-.47l-.17.47l-.91 2.56l-.17.47H7l.09-.49l.82-4.77l.09-.49z");
}

.r-x_e9bjv {
  d: path("M9.75 2.75H15l.65.37l2.7 1.51L19 5l.21.72l1.33 4.56l.21.72l-.73.16l-.79.18l-.73.16l-.37-.65l-1.26-2.2L16.5 8v7.5h-9V8l-.37.65l-1.26 2.2l-.37.65l-.73-.16l-.79-.18l-.73-.16l.21-.72l1.33-4.56L5 5l.65-.37l2.7-1.51l.65-.37z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
