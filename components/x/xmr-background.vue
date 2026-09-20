<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="gsa22ubes"/><path class="oanymqb0o"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:xmr-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gsa22ubes {
  fill: var(--svg-color--f60, #f60);
  d: path("M24 0H0v24h24z");
}

.oanymqb0o {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 4a7.99 7.99 0 0 1 7.593 10.5H17V7.811l-5.007 5.217L7 7.818V14.5H4.406A7.9 7.9 0 0 1 4 12.007A8 8 0 0 1 12 4m.022 11.397l3.478-3.478V16h3.332c-1.479 2.441-3.94 4.001-6.832 4c-2.884 0-5.42-1.699-6.832-4H8.5v-4.081z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
