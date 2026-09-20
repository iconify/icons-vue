<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="f9k78ozqc"/><path clip-rule="evenodd" class="fn59gt10y"/><path clip-rule="evenodd" class="kh0e5ludg"/><path class="kttqk_ifm"/><path clip-rule="evenodd" class="nwd5cqgcy"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:portx-background" /></template>
<style>
.f9k78ozqc {
  fill: var(--svg-color--2ff6d3, #2ff6d3);
  d: path("M24 0H0v24h24z");
}

.fn59gt10y {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M6.139 17.2c.709 1.333 1.509 1.813 2.128 1.813c.618 0 1.418-.48 2.128-1.813c.682-1.28 1.136-3.115 1.136-5.2c0-2.08-.454-3.92-1.136-5.2c-.71-1.333-1.51-1.813-2.128-1.813s-1.419.48-2.128 1.813C5.456 8.08 5.003 9.915 5.003 12c0 2.08.453 3.92 1.136 5.2M4 12c0 4.416 1.91 8 4.267 8s4.266-3.584 4.266-8s-1.91-8-4.266-8C5.909 4 4 7.584 4 12");
}

.ft5dv1b6b {
  fill: none;
}

.kh0e5ludg {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M9.872 17.2c.71 1.333 1.51 1.813 2.128 1.813s1.419-.48 2.128-1.813c.683-1.28 1.136-3.115 1.136-5.2c0-2.08-.453-3.92-1.136-5.2c-.71-1.333-1.51-1.813-2.128-1.813s-1.418.48-2.128 1.813C9.19 8.08 8.736 9.915 8.736 12c0 2.08.453 3.92 1.136 5.2M7.733 12c0 4.416 1.91 8 4.267 8s4.267-3.584 4.267-8S14.357 4 12 4s-4.267 3.584-4.267 8");
}

.kttqk_ifm {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.533 15.733a3.733 3.733 0 1 1 0-7.466a3.733 3.733 0 0 1 0 7.466");
}

.nwd5cqgcy {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M13.606 17.2c.709 1.333 1.509 1.813 2.127 1.813c.62 0 1.42-.48 2.128-1.813c.683-1.28 1.136-3.115 1.136-5.2c0-2.08-.453-3.92-1.136-5.2c-.709-1.333-1.509-1.813-2.128-1.813c-.618 0-1.418.48-2.128 1.813c-.682 1.28-1.136 3.115-1.136 5.2c0 2.08.454 3.92 1.136 5.2m-2.14-5.2c0 4.416 1.91 8 4.268 8S20 16.416 20 12s-1.91-8-4.267-8s-4.266 3.584-4.266 8");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
