<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="puogjtdng"/><path class="i3pd7abnj"/><path class="b90vbpbke"/><path class="d74424b-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wallet-minus-sharp" /></template>
<style>
.b90vbpbke {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.9 13h.01");
}

.d74424b-z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 9.75h4.5");
}

.i3pd7abnj {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.75 10.25h4.5v5.5h-4.5a2.75 2.75 0 0 1 0-5.5Z");
}

.puogjtdng {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.75h18.5v14.5H2.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
