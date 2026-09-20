<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path clip-rule="evenodd" class="gen_gkbcy"/><path clip-rule="evenodd" class="lxne21bid"/><path clip-rule="evenodd" class="av2fnpbej"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:uft-background" /></template>
<style>
.av2fnpbej {
  fill: var(--svg-color--003cb2, #003cb2);
  fill-rule: evenodd;
  d: path("M12.492 9.413h3.584l-2.965 5.478c-1.085 1.983.173 2.989 1.44 2.989h-3.086l-.002.003h-5.11a1.89 1.89 0 0 0 1.418-.935l.037-.064l3.78-6.968a1.21 1.21 0 0 1 .917-.504z");
}

.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.gen_gkbcy {
  fill: var(--svg-color--2bbdf7, #2bbdf7);
  fill-rule: evenodd;
  d: path("M16.14 9.412s.737-.015 3.282 0c.322.018.578.311.578.647a.64.64 0 0 1-.151.414l-1.03 1.834l-.026.046l-2.55 4.548a1.89 1.89 0 0 1-1.61.981h-.08l-7.545-.04h-.84v-.015a1.91 1.91 0 0 0 1.448-1.084h.006l3.697-6.621a1.25 1.25 0 0 1 1.121-.71l-.034.001l.002-.001z");
}

.lxne21bid {
  fill: var(--svg-color--2b6def, #2b6def);
  fill-rule: evenodd;
  d: path("M10.234 6.123h6.66c.322.02.577.295.577.631c0 .135-.04.26-.11.363l-3.709 6.652h.017l-.611 1.094c-1 .922-.71 2.096.158 2.654l.054.033c.217.13 0 .13.612.332h-8c-.31-.006-.591-.115-.882-.282c-.937-.536-1.276-1.756-.757-2.725L8.387 7.15a1.93 1.93 0 0 1 1.847-1.027");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
