<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGgFbuYv0i)" class="r4i437pya"/><path class="hh824ccqv"/><path class="ljapo8bwb"/><path class="ojyaid4ez"/></g><defs><linearGradient id="SVGgFbuYv0i" x1="15.835" x2="15.28" y1="7.051" y2="10.971" gradientUnits="userSpaceOnUse"><stop class="eloosfbwh"/><stop offset="1" class="gemvhx06g"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mnw-background" /></template>
<style>
.eloosfbwh {
  stop-color: var(--svg-color--5083a9, #5083a9);
}

.ft5dv1b6b {
  fill: none;
}

.gemvhx06g {
  stop-color: var(--svg-color--12132c, #12132c);
}

.hh824ccqv {
  fill: var(--svg-color--fff, #fff);
  d: path("m6.72 7.089l-2.697 9.99c-.174.65.669 1.092 1.12.584l3.605-4.047l2.212 2.503a1.402 1.402 0 0 0 2.09 0l2.211-2.498l3.595 4.023c.457.508 1.294.066 1.12-.584l-2.691-9.957a1.347 1.347 0 0 0-2.302-.527L12 9.95L9.026 6.57a1.346 1.346 0 0 0-2.301.518z");
}

.ljapo8bwb {
  fill: var(--svg-color--fff, #fff);
  d: path("m6.72 7.089l-1.774 6.574a2 2 0 0 1 2.706-1.035c.47.22.837.64 1.096.988l2.212 2.494a1.4 1.4 0 0 0 2.09 0l2.211-2.494l2.894-3.29a4.112 4.112 0 0 1-6.16-.376L9.021 6.57a1.346 1.346 0 0 0-2.301.518");
}

.ojyaid4ez {
  fill: var(--svg-color--fff, #fff);
  d: path("m15.261 13.615l3.596 4.024c.456.508 1.294.066 1.12-.584l-1.822-6.73zm-10.315.043l-.923 3.416c-.174.65.669 1.092 1.12.583l3.605-4.046c-.29-.448-.7-.802-1.186-1.022a2 2 0 0 0-2.184.421a2 2 0 0 0-.437.648z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
