<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="pdfvls3er"/><path class="hjjoq6ait"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nxm-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hjjoq6ait {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.879 5.697a1.697 1.697 0 1 1-3.395 0a1.697 1.697 0 0 1 3.395 0m-2.652 2.938a1.27 1.27 0 0 0 1.803 0l1.61-1.624a1.534 1.534 0 0 1 2.182 0a1.56 1.56 0 0 1 0 2.196l-3.758 3.782a1.29 1.29 0 0 0 0 1.818l1.561 1.571a1.562 1.562 0 0 1-.5 2.534a1.53 1.53 0 0 1-1.682-.337l-3.67-3.695a1.27 1.27 0 0 0-1.804 0l-1.61 1.624a1.53 1.53 0 0 1-2.181 0a1.56 1.56 0 0 1 0-2.196l3.758-3.782a1.29 1.29 0 0 0 0-1.818L7.374 7.137a1.56 1.56 0 0 1 .5-2.534a1.53 1.53 0 0 1 1.682.338zM12 13.455a1.697 1.697 0 1 0 0-3.395a1.697 1.697 0 0 0 0 3.395m6.06 2.181a1.697 1.697 0 1 0 0-3.393a1.697 1.697 0 0 0 0 3.393m-6.545 2.667a1.697 1.697 0 1 1-3.395 0a1.697 1.697 0 0 1 3.395 0m-5.576-6.972a1.697 1.697 0 1 0 0-3.394a1.697 1.697 0 0 0 0 3.394");
}

.pdfvls3er {
  fill: var(--svg-color--0ab682, #0ab682);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
