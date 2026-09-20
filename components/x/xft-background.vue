<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="yjsvu-gld"/><path class="oo9peyifn"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xft-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.oo9peyifn {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.992 12.003a4.991 4.991 0 0 1-8.804 3.219q-.305.17-.618.414a3.8 3.8 0 0 0-.999 1.472c-.084.194-.15.384-.2.559A7.985 7.985 0 0 0 18.35 7.157a3.1 3.1 0 0 1-.753 1.457a3.05 3.05 0 0 1-1.363.744c.497.792.76 1.709.759 2.644M7.62 14.397a4.99 4.99 0 0 1 7.925-5.914l.07-.01a2.4 2.4 0 0 0 1.278-.569c.29-.284.474-.783.564-1.362l.045-.335A7.985 7.985 0 0 0 5.613 16.795l.025-.07a4.76 4.76 0 0 1 1.308-1.872c.22-.18.449-.33.668-.459z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.yjsvu-gld {
  fill: var(--svg-color--410083, #410083);
  d: path("M24 0H0v24h24z");
}

</style>
