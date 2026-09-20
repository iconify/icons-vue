<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="lnfz52bju"/><path clip-rule="evenodd" class="p20_is3tv"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tor-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lnfz52bju {
  fill: var(--svg-color--be7c40, #be7c40);
  d: path("M24 0H0v24h24z");
}

.p20_is3tv {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M7.202 6.414a1.25 1.25 0 1 0-.7.06v2.45l4.913-3.28l-.755 5.628l-6.157 3.449l5.928 2.2l-1.345.899a1.25 1.25 0 1 0 .35.53l2.284-1.675l-5.773-2.099l4.958-2.804l5.928 3.919l-.92-5.958l1.16.59a1.249 1.249 0 1 0 .335-.5l-2.314-1.18l.904 5.833l-4.733-3.204l.91-6.947l-4.978 3.499v-1.41zm.14-1.164a.59.59 0 1 1-1.18 0a.59.59 0 0 1 1.18 0m10.905 6.087a.59.59 0 1 0 0-1.18a.59.59 0 0 0 0 1.18m-9.406 7.407a.59.59 0 1 1-1.18 0a.59.59 0 0 1 1.18 0");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
