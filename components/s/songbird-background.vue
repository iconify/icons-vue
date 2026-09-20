<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="eucedkani"/><path class="psebrjb_a"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:songbird-background" /></template>
<style>
.eucedkani {
  fill: var(--svg-color--e62058, #e62058);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.psebrjb_a {
  fill: var(--svg-color--fff, #fff);
  d: path("m6.4 20l3.628-6.6l-.66 5.7zm3.502-3.176l.45-3.927l4.808.631zm3.458-7.869l1.966 4.325l-4.842-.635zm1.027 1.622l2.434-1.217l-1.293 3.729zm-4.102 1.893L7.57 4l5.638 4.722zm6.141-1.167l.594-1.714l.58 2.795z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
