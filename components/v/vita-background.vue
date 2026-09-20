<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="rquefzi_f"/><path class="fcbzyab-a"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vita-background" /></template>
<style>
.fcbzyab-a {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.46 9.85c1.149-2.326.236-3.46-.626-4.043a2.5 2.5 0 0 0-1.36-.396c-1.99-.014-3.294 1.756-5.516 1.756c-2.099 0-3.59-1.718-5.516-1.756a2.36 2.36 0 0 0-1.675.687c-1.149.932-.791 2.876-.316 3.751c1.436 2.904 4.415 8.74 7.507 8.74s6.354-6.42 7.502-8.74");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rquefzi_f {
  fill: var(--svg-color--ffdd35, #ffdd35);
  d: path("M24 0H0v24h24z");
}

</style>
