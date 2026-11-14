<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dy47h08eq"/><path class="a60l7ub2v"/><path class="codh-u3cs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:terrain-contour" /></template>
<style>
.a60l7ub2v {
  d: path("M12.5 6c3.5 0 5.75 1.75 5.75 5c0 3.5-1.75 6.5-5.25 6.5c-2 0-2.75-2-5-3c-1.5-.75-2-2-2-3.5c0-3 2.75-5 6.5-5Z");
}

.codh-u3cs {
  d: path("M10.75 11a2.25 1.75 0 1 0 4.5 0a2.25 1.75 0 1 0-4.5 0Z");
}

.dy47h08eq {
  d: path("M12 2.5c5.5 0 9.5 3 9.5 8c0 5.5-3 10.5-8.5 10.5c-3.5 0-4.5-3-7.5-4c-2.5-1-3-3.5-3-6c0-5 4-8.5 9.5-8.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
