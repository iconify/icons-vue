<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG9yZA6avr)" class="r4i437pya"/><path class="p_tz7hipq"/><path class="tu238ybgr"/><path class="n0_j-0bvm"/></g><defs><linearGradient id="SVG9yZA6avr" x1="18.249" x2="18.809" y1="4.161" y2="4.638" gradientUnits="userSpaceOnUse"><stop class="zy0mlwtrq"/><stop offset="1" class="o1n0x8w1v"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:you-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.n0_j-0bvm {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.809 8.828a.389.389 0 1 0 0-.777a.389.389 0 0 0 0 .777m.914-3.034a.389.389 0 1 0 0-.777a.389.389 0 0 0 0 .777m4.44 0a.389.389 0 1 0 0-.777a.389.389 0 0 0 0 .777m4.359-1.017a.389.389 0 1 0 0-.777a.389.389 0 0 0 0 .777");
}

.o1n0x8w1v {
  stop-color: var(--svg-color--4300d0, #4300d0);
}

.p_tz7hipq {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.089 4h6.285v3.428H7.946v6.594c0 .972 1.714 3.006 4 3.12s4-2.04 4-3.12V5.714H14.23v-.571h2.286v8.88c0 1.525-1.977 3.69-4.571 3.69s-4.572-2.285-4.572-3.69V6.856h3.429V4.571H5.66v9.657c0 1.588 1.714 5.2 6.286 5.2c4.57 0 6.285-3.229 6.285-5.2V4.251h.571v9.977c0 2.211-1.954 5.84-6.856 5.771s-6.857-3.657-6.857-5.771z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.tu238ybgr {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.66 4h-5.143v3.428h2.286v6.234c0 .663-.937 2.383-2.857 2.337s-2.857-1.554-2.857-2.337v-5h-.571v5c0 1.417 1.525 2.897 3.428 2.909c1.903.011 3.428-1.646 3.428-2.909V6.857H13.09V4.571h4v9.091a4.8 4.8 0 0 1-5.052 4.623c-3.77 0-5.234-3.103-5.234-4.623V5.714H9.66v-.571H6.232v8.52c0 2.114 1.668 5.216 5.805 5.193s5.623-3.285 5.623-5.194z");
}

.zy0mlwtrq {
  stop-color: var(--svg-color--a81ed5, #a81ed5);
}

</style>
