<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="zl6nm9i3c"/><path clip-rule="evenodd" class="to_ctbc4a"/><path clip-rule="evenodd" class="as86pn8ww"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:nap-background" /></template>
<style>
.as86pn8ww {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M17.657 6.343A8 8 0 1 0 6.343 17.657A8 8 0 0 0 17.657 6.343m-3.315.006a6.12 6.12 0 1 0-4.689 11.307a6.12 6.12 0 0 0 4.689-11.307");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.to_ctbc4a {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m13.775 17.366l-.132.042a5.65 5.65 0 1 1 .132-.042m-3.03-8.66H8.706v.466h.216l.254.276v4.906s0 .47-.47.47v.47h1.411v-.47s-.47-.024-.47-.47V9.958l4.922 5.337h.254V9.648s0-.471.471-.471v-.47h-1.412v.47s.47 0 .47.47v3.027z");
}

.zl6nm9i3c {
  fill: var(--svg-color--03a7e4, #03a7e4);
  d: path("M24 0H0v24h24z");
}

</style>
