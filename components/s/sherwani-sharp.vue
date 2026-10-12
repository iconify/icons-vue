<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="x3tllxwrf"/><path class="l-zbc4bvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sherwani-sharp" /></template>
<style>
.l-zbc4bvm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 8h.01M12 11.25h.01M12 14.5h.01M12 17.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.x3tllxwrf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.75h5.75l.66.36l1.93 1.03l.66.36l.08.75l1.09 9.5l.08.75l-.75.07l-1 .11l-.75.07l-.06-.75l-.38-4.75q-.06-.75 0 0l.88 10.25l.06.75H6.25l.06-.75l.88-10.25q.06-.75 0 0L6.81 15l-.06.75l-.75-.07l-1-.11l-.75-.07l.08-.75l1.09-9.5l.08-.75l.66-.36l1.93-1.03l.66-.36zm-.25 2.5h5.5");
}

</style>
