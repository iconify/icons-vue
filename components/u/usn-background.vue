<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="n3pvjc7av"/><path clip-rule="evenodd" class="x4bo9abcq"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:usn-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.n3pvjc7av {
  fill: var(--svg-color--fff, #fff);
  d: path("M20 4H4v16h16z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.x4bo9abcq {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 4a8 8 0 1 1 0 16a8 8 0 0 1 0-16M9.47 8.243a.71.71 0 0 1 .778.245l3.373 4.508V8.211h1.39v2.006h1.62v1.337h-1.62v.892h1.62v1.337h-1.62v1.286c0 .29-.195.547-.482.636a.71.71 0 0 1-.777-.245l-3.373-4.508v4.837h-1.39v-2.006H7.37v-1.337h1.62v-.892H7.37v-1.337h1.62V8.879c0-.29.195-.547.482-.636");
}

</style>
