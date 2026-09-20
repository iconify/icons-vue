<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="itjdq9b6x"/><path class="l3_h__-ht"/><path class="bdd4jvrql"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vee-background" /></template>
<style>
.bdd4jvrql {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.47 9.256A49 49 0 0 1 4.196 4.49c-.15 0-.245.15-.17.28l7.8 14.638a.19.19 0 0 0 .335 0l1.832-3.43a39.2 39.2 0 0 1-6.518-6.722z");
}

.ft5dv1b6b {
  fill: none;
}

.itjdq9b6x {
  fill: var(--svg-color--718c98, #718c98);
  d: path("M24 0H0v24h24z");
}

.l3_h__-ht {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.247 4.49a2.714 2.714 0 0 0-2.753 2.754c0 1.557 1.206 2.753 2.753 2.753S20 8.801 20 7.244S18.794 4.49 17.247 4.49m-8.79.096l5.756 10.787a.19.19 0 0 1 0 .19l-2.052 3.845a.19.19 0 0 1-.265.073a.2.2 0 0 1-.07-.073L4.03 4.771a.185.185 0 0 1 .17-.28h4.11c.04 0 .116.035.15.095z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
