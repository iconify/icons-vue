<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ngpjaibql"/><path class="n2ly8be4j"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rdt-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.n2ly8be4j {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.019 4.941L8.616 8.353l3.403 3.407l3.402-3.407zM7.402 9.826L4 13.238l3.402 3.407l3.403-3.407zm5.793 3.412l3.403-3.412L20 13.238l-3.402 3.407zm-5.444 5.821l4.31-4.32l4.306 4.32z");
}

.ngpjaibql {
  fill: var(--svg-color--6601ff, #6601ff);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
