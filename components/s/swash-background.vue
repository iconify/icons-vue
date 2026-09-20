<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="p3rm82mjj"/><path clip-rule="evenodd" class="s5yg9ibdd"/><path class="o20do-91m"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:swash-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.o20do-91m {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.478 9.24a3.186 3.186 0 0 1 3.185-3.187h4.46v.85h-4.46a2.336 2.336 0 0 0 0 4.672h.85v.85h-.85a3.186 3.186 0 0 1-3.185-3.186m11.044 5.521a3.186 3.186 0 0 1-3.186 3.186h-4.46v-.85h4.46a2.337 2.337 0 0 0 0-4.672h-.85v-.85h.85a3.186 3.186 0 0 1 3.186 3.186");
}

.p3rm82mjj {
  fill: var(--svg-color--3ce35f, #3ce35f);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.s5yg9ibdd {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M15.61 5.982a.496.496 0 1 0 0 .992a.496.496 0 0 0 0-.992m-2.477.496a2.478 2.478 0 1 1 4.956 0a2.478 2.478 0 0 1-4.956 0M12 11.504a.496.496 0 1 0 0 .992a.496.496 0 0 0 0-.992m-1.752-1.256a2.478 2.478 0 1 1 3.504 3.504a2.478 2.478 0 0 1-3.504-3.504M8.39 17.026a.496.496 0 1 0 0 .992a.496.496 0 0 0 0-.992M6.637 15.77a2.478 2.478 0 1 1 3.504 3.504a2.478 2.478 0 0 1-3.504-3.504");
}

</style>
