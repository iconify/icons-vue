<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="t4t_kemhp"/><path class="u5gdmgemm"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xdc-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t4t_kemhp {
  fill: var(--svg-color--b8b5b1, #b8b5b1);
  d: path("M19.98 11.225C18.14.59 4.25 2.65 4 11.225l1.31.675s-.425.25-1.31.83c1.61 10.44 15.275 8.92 16-.015q-.67-.412-1.345-.815zm-6.85 3.72l-1.305-2.25l-1.31 2.25l-1.01-.075l1.895-3.185l-1.7-2.74l1.025-.09l1.2 2.035l1.21-1.95l.95.02l-1.57 2.71l1.75 3.24l-1.13.035z");
}

.u5gdmgemm {
  fill: var(--svg-color--254c82, #254c82);
  d: path("M19.325 10.8c-2.495-9.45-13.91-6.9-14.69 0l1.95 1.1l-1.95 1.24c1.7 9.095 14.02 7.34 14.69-.02c-1.235-.78-1.98-1.24-1.98-1.24s1.68-.9 1.98-1.08m-6.19 4.16l-1.31-2.25l-1.33 2.25l-1.01-.07l1.9-3.185l-1.7-2.745l1.025-.085l1.2 2.035l1.205-1.95l.955.02l-1.57 2.705l1.77 3.24l-1.13.035z");
}

</style>
