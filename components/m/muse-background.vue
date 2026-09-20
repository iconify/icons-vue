<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ynisyqo4p"/><path class="pv99xxw5y"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:muse-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.pv99xxw5y {
  fill: var(--svg-color--fff, #fff);
  d: path("m7.067 4.533l5.733 5.632c1.925-1.93 3.867-3.626 5.723-5.621a.84.84 0 0 1 .938-.208a.87.87 0 0 1 .539.805V8.32c-2.272 2.363-4.443 4.565-6.677 6.928a.716.716 0 0 1-1.046 0l-2.944-3.216v6.97c0 .406-.4.731-.8.731H6.4c-.4 0-.8-.336-.8-.746v-.854h-.875A.74.74 0 0 1 4 17.387v-2.24c0-.411.325-.747.725-.747H5.6v-2.133h-.875A.74.74 0 0 1 4 11.52V9.28c0-.41.325-.747.725-.747H5.6V5.141a.83.83 0 0 1 .539-.8a.7.7 0 0 1 .33-.074c.224 0 .438.096.598.266m9.456 9.424l2.122-2.005a.79.79 0 0 1 .87-.15a.77.77 0 0 1 .485.731v6.4c0 .438-.357.8-.805.8h-2.123a.8.8 0 0 1-.57-.232a.8.8 0 0 1-.235-.568V14.54c.01-.23.09-.427.256-.582");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.ynisyqo4p {
  fill: var(--svg-color--24ddd8, #24ddd8);
  d: path("M24 0H0v24h24z");
}

</style>
