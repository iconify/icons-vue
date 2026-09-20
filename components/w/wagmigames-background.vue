<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="fqdr14b4p"/><path clip-rule="evenodd" class="ubh98c8di"/><path class="hndutobcy"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wagmigames-background" /></template>
<style>
.fqdr14b4p {
  fill: var(--svg-color--00d8ff, #00d8ff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.hndutobcy {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.891 10.117H6.823l2.523 5.647h.771l1.897-4.306l1.854 4.306h.842l2.466-5.647H16.17L14.287 14.4l-1.864-4.282h-.8L9.708 14.4l-1.821-4.282zM6.823 8.706v.47h3.657l.3-.253h6.396v-.217z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ubh98c8di {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16m0-.941a7.06 7.06 0 1 0 0-14.12a7.06 7.06 0 0 0 0 14.12");
}

</style>
