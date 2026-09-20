<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="o4u9kbcsk"/><path clip-rule="evenodd" class="ugqydacvp"/><path class="umuolzbme"/><path class="c4rmmgb9m"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xrt-background" /></template>
<style>
.c4rmmgb9m {
  fill: var(--svg-color--fff, #fff);
  d: path("m11.988 10.002l-3.495 5.992l3.495-1.768zm0 0l3.496 5.992l-3.496-1.768z");
}

.ft5dv1b6b {
  fill: none;
}

.o4u9kbcsk {
  fill: var(--svg-color--03a2e5, #03a2e5);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ugqydacvp {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12.25 5.932a.498.498 0 1 0-.566-.818a.5.5 0 0 0 .06.829L4.725 18.046a.497.497 0 0 0-.724.395a.5.5 0 1 0 .996.05h13.98a.5.5 0 0 0 .5.498a.499.499 0 1 0-.015-.996zm6.969 12.133l-7.23-12.057l-7.075 12.207l.016.025h14.117a.5.5 0 0 1 .172-.175");
}

.umuolzbme {
  fill: var(--svg-color--fff, #fff);
  d: path("m8.493 15.994l3.493-1.803l3.498 1.803z");
}

</style>
