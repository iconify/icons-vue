<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGl5JFYtIv)" class="r4i437pya"/><path clip-rule="evenodd" class="iqp0-w00e"/><path class="w2xltqqke"/><path class="vti-ahbcz"/></g><defs><linearGradient id="SVGl5JFYtIv" x1="12" x2="12" y1="4.005" y2="19.995" gradientUnits="userSpaceOnUse"><stop class="xksggzbzb"/><stop offset=".36" class="ea06m1bwj"/><stop offset=".7" class="vmiqcbcrg"/><stop offset="1" class="uv62bbchg"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:tut-background" /></template>
<style>
.ea06m1bwj {
  stop-color: var(--svg-color--066579, #066579);
}

.ft5dv1b6b {
  fill: none;
}

.iqp0-w00e {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M11.994 19.995a7.995 7.995 0 1 0 0-15.99a7.995 7.995 0 0 0 0 15.99m2.998-7.994l-4.497-2.498v4.996z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.uv62bbchg {
  stop-color: var(--svg-color--11b7c5, #11b7c5);
}

.vmiqcbcrg {
  stop-color: var(--svg-color--039aab, #039aab);
}

.vti-ahbcz {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 12.04c.56-1.299 1.834-3.037 3.997-3.037c.335 0 1.3.1 2.498.5L14.992 12c.664-.5 1.998-1.849 1.998-3.248c0-1.499-.55-2.808-1.488-3.937A7.994 7.994 0 0 0 4 12.04");
}

.w2xltqqke {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.437 4.782c1.13 1.708 2.388 5.14-.445 7.22l-4.496 2.497c0 1.335.899 4.047 4.496 4.247c.455.025.895.02 1.304-.005a7.989 7.989 0 0 0-.859-13.96");
}

.xksggzbzb {
  stop-color: var(--svg-color--036276, #036276);
}

</style>
