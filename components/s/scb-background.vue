<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="e6a6lwxhv"/><path clip-rule="evenodd" class="fi_oa04xy"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:scb-background" /></template>
<style>
.e6a6lwxhv {
  fill: var(--svg-color--fc0, #fc0);
  d: path("M24 0H0v24h24z");
}

.fi_oa04xy {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M6.546 9.39h3.58a.85.85 0 0 1 .83.87c0 .48-.371.87-.83.87h-.734v.695h-.87V9.912H7.43c-.264 0-.22.24-.16.33c.198.21.598.72.598 1.09a.467.467 0 0 1-.438.493H5.392v-.695H6.64c.258 0 .16-.181.077-.261l-.494-.661c-.261-.574.108-.786.323-.817m2.846.522h.459c.128 0 .236.119.236.261s-.104.261-.236.261h-.46zm3.63-.521h-1.349l-.716 2.434h.845l.094-.348h.953l.104.348h.787zm-.33 1.565h-.65l.268-.974h.09zm2.09-1.565a1.217 1.217 0 1 0 0 2.434h1.044v-.695h-1.043a.522.522 0 0 1 0-1.044h1.043v-.695zm3.48 0v.695H16.87v.348h1.043v.348H16.87v.348h2.087v.695h-2.783V9.391zM6.233 12.591l-.525.62a.522.522 0 1 0-.007.378l.56.574a1.3 1.3 0 0 1-.984.446A1.25 1.25 0 0 1 4 13.39c0-.671.57-1.217 1.277-1.217c.382 0 .723.16.956.417m10.984-.417h.87l.522.696l.521-.696H20l-1.044 1.391v1.044h-.695v-1.044zM8.87 13.39a1.217 1.217 0 1 1-2.435 0a1.217 1.217 0 0 1 2.435 0m-.696 0a.521.521 0 1 1-1.043 0a.521.521 0 0 1 1.043 0m8.174 1.218a1.217 1.217 0 1 0 0-2.435a1.217 1.217 0 0 0 0 2.435m0-.696a.521.521 0 1 0 0-1.043a.521.521 0 0 0 0 1.043m-6.783.696l-.695-2.435h.695l.348 1.043l.348-1.043h.696l.347 1.043l.404-1.043h2.508a.57.57 0 0 1 .302 1.057a.717.717 0 0 1-.278 1.378h-1.892v-1.74h-.14l-.556 1.74h-.695l-.383-.867l-.313.867zm3.652-1.74h.626a.175.175 0 0 1 .174.174a.174.174 0 0 1-.174.174h-.626zm0 .696h.61a.261.261 0 0 1 0 .522h-.61z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
