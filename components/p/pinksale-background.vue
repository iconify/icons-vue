<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="tk5tw9w5l"/><path class="gnq76b4lb"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pinksale-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gnq76b4lb {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.467 7.978L18 6.444l-.467 1.534L16 8.444l1.533.467l.467 1.533l.467-1.533L20 8.444zM7.11 8.555c0-.182.138-.333.311-.333h2.49c.172 0 .31.151.31.333s-.137.334-.31.334h-2.49c-.173 0-.31-.151-.31-.334m5.778 0c0-.182.138-.333.311-.333h2.489c.173 0 .311.151.311.333s-.138.334-.311.334H13.2c-.173 0-.311-.151-.311-.334M8 10.213c0-.364.298-.658.667-.658s.666.294.666.658v2.24a.667.667 0 0 1-1.333 0zm5.778 0c0-.364.298-.658.666-.658c.37 0 .667.294.667.658v2.24a.666.666 0 0 1-1.333 0zm-7.111 2.454a1.333 1.333 0 1 1-2.667 0a1.333 1.333 0 0 1 2.667 0M17.777 14a1.333 1.333 0 1 0 .001-2.666a1.333 1.333 0 0 0 0 2.666m-3.2 1.929a.48.48 0 0 1-.044.609c-.4.373-1.493 1.017-3.057 1.017c-1.556 0-2.57-.644-2.92-1.044a.47.47 0 0 1 0-.609a.36.36 0 0 1 .42-.092a.4.4 0 0 1 .122.092c.186.213.986.791 2.377.791c1.392 0 2.312-.578 2.56-.813a.356.356 0 0 1 .543.049");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tk5tw9w5l {
  fill: var(--svg-color--f95192, #f95192);
  d: path("M24 0H0v24h24z");
}

</style>
