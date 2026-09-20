<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path clip-rule="evenodd" class="dcwrkxbmi"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:noia-background" /></template>
<style>
.dcwrkxbmi {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 12s2.5-4.12 2.5-5.5a2.5 2.5 0 1 0-5 0C9.5 7.88 12 12 12 12m0 0s-4.12 2.5-5.5 2.5a2.5 2.5 0 1 1 0-5C7.88 9.5 12 12 12 12m0 0s4.12-2.5 5.5-2.5a2.5 2.5 0 1 1 0 5C16.12 14.5 12 12 12 12m0 0s2.5 4.12 2.5 5.5a2.5 2.5 0 1 1-5 0C9.5 16.12 12 12 12 12");
}

.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
