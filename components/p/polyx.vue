<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGi0RHzbYw)" class="a7cbz5dmz"/><path fill="url(#SVG2U6Wsetx)" clip-rule="evenodd" class="u0iel_bvg"/><defs><linearGradient id="SVGi0RHzbYw" x1="108.825" x2="108.773" y1="2.651" y2="37.348" gradientUnits="userSpaceOnUse"><stop class="a8gxrxckj"/><stop offset=".93" class="c7qbrgb2c"/></linearGradient><linearGradient id="SVG2U6Wsetx" x1="12" x2="12" y1="3" y2="21" gradientUnits="userSpaceOnUse"><stop class="a8gxrxckj"/><stop offset="1" class="odogwsbkh"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:polyx" /></template>
<style>
.a7cbz5dmz {
  d: path("M12.969 12c1.038 0 2.207-.44 2.207-1.588c0-1.107-1.122-1.589-2.207-1.589H9.882V7.765h3.25c1.706 0 3.103.863 3.103 2.647s-1.466 2.647-3.102 2.647H10.94v3.706H9.882V12z");
}

.a8gxrxckj {
  stop-color: var(--svg-color--ff2e72, #ff2e72);
}

.c7qbrgb2c {
  stop-color: var(--svg-color--4a125e, #4a125e);
}

.ft5dv1b6b {
  fill: none;
}

.odogwsbkh {
  stop-color: var(--svg-color--631661, #631661);
}

.u0iel_bvg {
  fill-rule: evenodd;
  d: path("M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18m0-1.059a7.942 7.942 0 1 0 0-15.883a7.942 7.942 0 0 0 0 15.883");
}

</style>
