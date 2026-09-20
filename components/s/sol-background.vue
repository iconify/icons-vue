<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG1uQ4ueER)" class="r4i437pya"/><path class="cwsm5qbes"/></g><defs><linearGradient id="SVG1uQ4ueER" x1="4" x2="20.384" y1="15.841" y2="15.192" gradientUnits="userSpaceOnUse"><stop class="xnhgfvelh"/><stop offset="1" class="e95k-_nlt"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sol-background" /></template>
<style>
.cwsm5qbes {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.7 8.357a.55.55 0 0 1-.365.145H4.515c-.455 0-.685-.52-.37-.825l2.105-2.03c.1-.095.23-.15.365-.15h12.87c.46 0 .685.525.365.83zm0 10.006c-.1.09-.23.14-.365.14H4.515c-.455 0-.685-.515-.37-.82l2.105-2.035c.1-.095.23-.145.365-.145h12.87c.46 0 .685.52.365.825zm0-7.72a.55.55 0 0 0-.365-.14H4.515c-.455 0-.685.515-.37.82l2.105 2.035c.1.09.23.145.365.145h12.87c.46 0 .685-.52.365-.825z");
}

.e95k-_nlt {
  stop-color: var(--svg-color--47f8c3, #47f8c3);
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.xnhgfvelh {
  stop-color: var(--svg-color--599db0, #599db0);
}

</style>
