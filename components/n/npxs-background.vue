<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="c8gpclpub"/><path clip-rule="evenodd" class="z_0mg9bhe"/><path class="vkycznbcp"/><path clip-rule="evenodd" class="iwydvdb1u"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:npxs-background" /></template>
<style>
.c8gpclpub {
  fill: var(--svg-color--fcd309, #fcd309);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.iwydvdb1u {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M11.857 8.953L14.904 12l-3.047 3.047L8.797 12zM10.076 12l1.78 1.773L13.627 12l-1.772-1.773z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vkycznbcp {
  fill: var(--svg-color--fff, #fff);
  d: path("m9.437 12l2.42-2.41l2.41 2.41l-2.41 2.41z");
}

.z_0mg9bhe {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12.638 12L20 19.362l-.639.638L12 12.637L4.638 20L4 19.361L11.363 12L4 4.638L4.638 4L12 11.363L19.362 4l.638.638z");
}

</style>
