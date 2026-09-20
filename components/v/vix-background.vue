<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="t9ikhqoud"/><path class="llw5nvbhf"/><path class="bclfvybod"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vix-background" /></template>
<style>
.bclfvybod {
  fill: var(--svg-color--fff, #fff);
  d: path("m14 19.25l6-14.47c-2.835-.34-4.79 2.13-5.835 4.685L10 19.25z");
}

.ft5dv1b6b {
  fill: none;
}

.llw5nvbhf {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.5 19.25L4 4.78c2.835-.34 4.79 2.13 5.835 4.685L14 19.25z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t9ikhqoud {
  fill: var(--svg-color--bde6f3, #bde6f3);
  d: path("M24 0H0v24h24z");
}

</style>
