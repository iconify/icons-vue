<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="amj95w11v"/><path class="q8myj8b6e"/><path class="qd3kuwb_m"/><path class="jfp9stxsi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:penguin-marine-sharp" /></template>
<style>
.amj95w11v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75H8.1v7L6 13.5l-.949 1.542l1.599-.492l1.45-.6v1c0 1.25 1.75 2.25 3.9 2.25s3.9-1 3.9-2.25v-1l1.45.6l1.599.492L18 13.5l-2.1-3.75v-7z");
}

.jfp9stxsi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 20.25h15");
}

.q8myj8b6e {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9.75h-1.75v5.2h3.5v-5.2z");
}

.qd3kuwb_m {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.85 5.5h.01m2.29 0h.01M12 7.75h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
