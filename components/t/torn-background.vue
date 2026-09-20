<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="iuqdgtbnm"/><path clip-rule="evenodd" class="th02ai7uc"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:torn-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.iuqdgtbnm {
  fill: var(--svg-color--92ffbe, #92ffbe);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.th02ai7uc {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M7.468 8.038c1.004-1.372 3.932-3.823 7.61-2.662c3.68 1.161 4.815 4.551 4.922 6.102c-.224-1.153-1.365-3.567-4.134-4.003c1.501 1.095 4.122 4.227 2.595 7.995s-4.671 4.588-6.052 4.527c1.117-.088 3.489-1.02 4.041-4.04c-.765 1.076-3.002 3.17-5.829 2.944c-3.534-.285-6.174-2.68-6.62-6.01c.182 1.056 1.25 3.253 4.061 3.594c-1.13-.697-3.31-2.976-2.986-6.517c.407-4.425 4.53-5.907 6.358-5.968c-1.256.199-3.807 1.285-3.966 4.038M12 14.823a2.823 2.823 0 1 0 0-5.646a2.823 2.823 0 0 0 0 5.646");
}

</style>
