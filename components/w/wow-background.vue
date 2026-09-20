<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path class="bikbx6bvi"/><path clip-rule="evenodd" class="z4z1a3b0i"/><path class="zo1_fkbuf"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:wow-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.bikbx6bvi {
  fill: var(--svg-color--f3ba2f, #f3ba2f);
  d: path("M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.z4z1a3b0i {
  fill: var(--svg-color--000, #000);
  fill-rule: evenodd;
  d: path("M12 19a7 7 0 1 0 0-14a7 7 0 0 0 0 14m0 1a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.zo1_fkbuf {
  fill: var(--svg-color--000, #000);
  d: path("M10 10.5c.553 0 1-.56 1-1.25S10.554 8 10 8s-1 .56-1 1.25s.448 1.25 1 1.25m4 0c.553 0 1-.56 1-1.25S14.553 8 14 8s-1 .56-1 1.25s.448 1.25 1 1.25m-2 7c1.381 0 2.5-1.343 2.5-3s-1.119-3-2.5-3c-1.38 0-2.5 1.343-2.5 3s1.12 3 2.5 3");
}

</style>
