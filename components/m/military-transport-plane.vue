<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pb86g0b2t"/><path class="eqfteqqia"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:military-transport-plane" /></template>
<style>
.eqfteqqia {
  d: path("m8 9l1.5-2.5h3l1 2.5m4.25 5l1.029 2.084l2.3.334l-1.665 1.623l.393 2.291l-2.057-1.082l-2.057 1.082l.393-2.291l-1.665-1.623l2.3-.334Z");
}

.pb86g0b2t {
  d: path("M15.254 12.737L14 13.5H5.25q-.111 0-.221-.011t-.218-.032t-.214-.054t-.208-.074q-.102-.043-.2-.095q-.097-.052-.189-.113t-.177-.132t-.164-.148t-.148-.164q-.07-.085-.132-.177q-.061-.092-.113-.189q-.052-.098-.095-.2q-.042-.102-.074-.208t-.054-.214t-.032-.218T3 11.25t.011-.221t.032-.218q.022-.108.054-.214t.074-.208q.043-.102.095-.2q.052-.097.113-.189t.132-.177q.07-.086.148-.164t.164-.148T4 9.379q.092-.061.189-.113q.098-.052.2-.095q.102-.042.208-.074t.214-.054t.218-.032T5.25 9h9.25L18 3h2.5l-.75 7l-.652.397");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
