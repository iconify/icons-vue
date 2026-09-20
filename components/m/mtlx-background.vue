<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="t2n24tbpw"/><path clip-rule="evenodd" class="wpyh1_bli"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mtlx-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.t2n24tbpw {
  fill: var(--svg-color--3e34a7, #3e34a7);
  d: path("M24 0H0v24h24z");
}

.wpyh1_bli {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M19.059 5.176H20v12.706h-.941zM4 5.176h.941v12.706H4zm2.824 1.412h-.942v9.882h.942zm10.353 0h.94v10.353h-.94zm-8.471.941h-.941v10.353h.94zm6.588-.022h.941V17.86h-.94zm-4.706 1.434h-.94v8h.94zm2.824 0h.94v8h-.94zm-.941 1.412h-.942v8.47h.942z");
}

</style>
