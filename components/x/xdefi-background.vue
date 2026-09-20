<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="b087avb8t"/><path class="ljgajvbxt"/><path class="rcc7xibdi"/><path class="f_ghvbbql"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xdefi-background" /></template>
<style>
.b087avb8t {
  fill: var(--svg-color--4476f2, #4476f2);
  d: path("M24 0H0v24h24z");
}

.f_ghvbbql {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.794 14.87a6.4 6.4 0 0 1-1.73 1.552c-2.352 1.495-5.344 1.688-7.439 1.584l-.044.872q.526.025 1.018.025c5.908 0 8.295-2.65 8.962-3.596l-.769-.444m-.222-3.296c.39 0 .708-.313.708-.698a.704.704 0 0 0-.709-.698a.704.704 0 0 0-.709.698c0 .385.318.698.71.698");
}

.ft5dv1b6b {
  fill: none;
}

.ljgajvbxt {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.594 12.981c-1.238.757-2.894 1.147-4.572 1.064c-1.41-.068-2.568-.568-3.267-1.389c-.615-.734-.853-1.703-.692-2.818c.055-.37.167-.73.332-1.067l.024-.047a7.2 7.2 0 0 1 2.5-2.707a7.35 7.35 0 0 1 7.173-.394a7.2 7.2 0 0 1 2.791 2.416a7.05 7.05 0 0 1 .52 7.055a7.2 7.2 0 0 1-2.406 2.788a7.3 7.3 0 0 1-3.493 1.25l.077.868a8.2 8.2 0 0 0 3.922-1.4a8.05 8.05 0 0 0 2.703-3.13a7.91 7.91 0 0 0-.587-7.921a8.1 8.1 0 0 0-3.135-2.71a8.25 8.25 0 0 0-8.053.45A8.06 8.06 0 0 0 4.63 8.332l-.031.062a4.5 4.5 0 0 0-.411 1.325c-.193 1.359.105 2.568.884 3.499c.851 1.018 2.237 1.624 3.9 1.703c2.023.1 4.035-.443 5.463-1.442z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.rcc7xibdi {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.287 13.97c-.805.688-2.677 1.937-5.783 2.107c-3.476.19-4.926-.923-4.939-.935l-.28.341l.282-.335l-.567.67c.061.051 1.451 1.156 4.714 1.156c.267 0 .548 0 .84-.023c3.753-.206 5.816-1.818 6.534-2.507z");
}

</style>
