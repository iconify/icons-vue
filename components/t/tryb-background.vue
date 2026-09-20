<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="sq9m4d0be"/><path class="vlmt20bnw"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tryb-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sq9m4d0be {
  fill: var(--svg-color--20316b, #20316b);
  d: path("M24 0H0v24h24z");
}

.vlmt20bnw {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.664 10.843c.006-.238 0-.867 0-.867l-5.775-1.532v1.778l4 1.04c-.33 4.113-2.257 6.476-5.778 6.96V4.502L7.333 4v16l.95-.048c3.509-.177 7.63-1.795 8.31-8.2c.031-.292.063-.595.07-.909m-1.784-3.03l.453-1.59l-4.444-1.334v1.778z");
}

</style>
