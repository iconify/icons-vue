<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="m3i708b1u"/><path clip-rule="evenodd" class="u5gupypbu"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:portal-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m3i708b1u {
  fill: var(--svg-color--3e71f8, #3e71f8);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.u5gupypbu {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M18.74 15.043a4.304 4.304 0 0 0 0-6.086s-4.492-4.638-5.103-4.9c-.029-.013-.027-.024-.025-.032c.004-.016.006-.025-.248-.025a.69.69 0 0 0-.688.689v1.793c0 .38.308.689.688.689h.746c1.585 0 2.87 1.092 2.87 2.677v4.304c0 1.585-1.285 2.677-2.87 2.677h-.746a.69.69 0 0 0-.688.689v1.793a.69.69 0 0 0 .96.633c.612-.264 5.103-4.9 5.103-4.9m-7.416-8.56V4.688a.688.688 0 0 0-.96-.633c-.612.264-5.103 4.9-5.103 4.9a4.304 4.304 0 0 0 0 6.087s4.49 4.637 5.102 4.9a.688.688 0 0 0 .961-.632v-1.793a.69.69 0 0 0-.688-.689H9.89c-1.585 0-2.87-1.092-2.87-2.677V9.848c0-1.584 1.285-2.677 2.87-2.677h.746c.38 0 .688-.308.688-.689");
}

</style>
