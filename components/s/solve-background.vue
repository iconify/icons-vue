<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="nol8v5bld"/><path clip-rule="evenodd" class="c35id1v_j"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:solve-background" /></template>
<style>
.c35id1v_j {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M19.393 12.003a7.396 7.396 0 0 1-11.895 5.874a1.11 1.11 0 0 0-1.374-1.38A7.397 7.397 0 0 1 16.49 6.129a1.108 1.108 0 0 0 1.38 1.381a7.36 7.36 0 0 1 1.522 4.493m-2.57-6.397a1.111 1.111 0 1 1 1.572 1.572A8.012 8.012 0 0 1 7.177 18.395a1.112 1.112 0 1 1-1.572-1.572A8.012 8.012 0 0 1 16.823 5.606m-4.826 9.726a3.322 3.322 0 1 0 0-6.645a3.322 3.322 0 0 0 0 6.645m0 2.465a5.794 5.794 0 0 0 0-11.587a5.788 5.788 0 1 0 0 11.575zm1.782-5.794a1.781 1.781 0 1 1-3.563 0a1.781 1.781 0 0 1 3.563 0");
}

.ft5dv1b6b {
  fill: none;
}

.nol8v5bld {
  fill: var(--svg-color--43266b, #43266b);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
