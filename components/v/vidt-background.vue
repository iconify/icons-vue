<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="lklw7abwg"/><path clip-rule="evenodd" class="x9qwjmq7l"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vidt-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.lklw7abwg {
  fill: var(--svg-color--00ccda, #00ccda);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.x9qwjmq7l {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M6 4c.493 0 1.002.338 1.002 1.44v11.162c-.004.084.047.227.278.126c.23-.101 1.55-.782 2.109-1.116c.04-.02.111-.099.111-.25V7.898c0-.185 0-.653.582-1.028c.427-.277 1.066-.11 1.316.06l6.942 4.027c.228.139.678.425.66 1.058c-.019.634-.518.951-.761 1.075L6.524 19.9c-.212.095-.81.202-1.113-.09c-.346-.334-.403-.69-.41-.805V5.44c-.02-.451.1-1.44 1-1.44m5.75 10.485a.25.25 0 0 0 .126-.034l3.756-2.203a.252.252 0 0 0-.002-.433l-3.756-2.202a.248.248 0 0 0-.373.215v4.405a.25.25 0 0 0 .25.252");
}

</style>
