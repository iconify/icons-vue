<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="iiyvu4jfd"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ram-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iiyvu4jfd {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.64 14.824L20 9.48L17.14 6.6l-1.152 1.152L17.48 9.24l-2.94 2.932l-2.568-2.56l-1.276 1.272l3.948 3.94zm-5.28 0L4 9.48l2.64-2.664l1.152 1.152L6.28 9.48l2.94 2.932l1.064-1.06l1.28 1.272l-2.208 2.2zm2.592-1.744l-2.168 2.16l2.168 2.16l2.164-2.16z");
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
