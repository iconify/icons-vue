<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aevlv3ncw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ski-pole" /></template>
<style>
.aevlv3ncw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m9.27 3.08l.99.19q.98.2.78 1.18l-.49 2.45q-.2.98-1.18.78l-.98-.19q-.98-.2-.78-1.18l.48-2.45q.2-.98 1.18-.78m8 0l.99.19q.98.2.78 1.18l-.49 2.45q-.2.98-1.18.78l-.98-.19q-.98-.2-.78-1.18l.48-2.45q.2-.98 1.18-.78M8.88 7.59L6.24 20.83M16.88 7.59l-2.64 13.24m-9.13-3.29l3.43.69m4.57-.69l3.43.69");
}

</style>
