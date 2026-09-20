<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGylbS9bNQ)" class="r4i437pya"/><path class="f9uvuwdhy"/><path clip-rule="evenodd" class="xh78r8buz"/></g><defs><linearGradient id="SVGylbS9bNQ" x1="17.882" x2="6.117" y1="6.118" y2="17.648" gradientUnits="userSpaceOnUse"><stop class="eiaaj5b6m"/><stop offset=".53" class="dl2ggdbks"/><stop offset="1" class="ylekb4bkl"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ncr-background" /></template>
<style>
.dl2ggdbks {
  stop-color: var(--svg-color--f4b86d, #f4b86d);
}

.eiaaj5b6m {
  stop-color: var(--svg-color--f58f05, #f58f05);
}

.f9uvuwdhy {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.412 16.236h1.646l-4.465-8H8.94z");
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

.xh78r8buz {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M17.657 6.343A8 8 0 1 0 6.343 17.657A8 8 0 0 0 17.657 6.343m-.598.057A7.62 7.62 0 0 0 12 4.47A7.62 7.62 0 0 0 6.941 6.4l.353.353a7.02 7.02 0 0 1 9.421-.01zm1.986 5.13a7.03 7.03 0 0 0-1.755-4.207l.31-.344a7.95 7.95 0 0 1 1.93 4.55zm-1.774 5.162A7.03 7.03 0 0 0 19.059 12h.47c0 1.788-.734 3.704-1.929 5.021zm-9.986.565A7.03 7.03 0 0 0 12 19.059a7.05 7.05 0 0 0 4.715-1.802l.344.343A7.55 7.55 0 0 1 12 19.53a7.62 7.62 0 0 1-5.059-1.93zM4.94 12c0 1.793.669 3.435 1.77 4.678l-.31.343a8 8 0 0 1-1.93-5.02zm1.812-4.706a7.04 7.04 0 0 0-1.798 4.236H4.47c.117-1.7.847-3.389 1.93-4.589zm1.482 9.412V7.765h2.626l4.433 8.083V7.765h.47v8.941H13.14L8.706 8.623v8.083z");
}

.ylekb4bkl {
  stop-color: var(--svg-color--ea911d, #ea911d);
}

</style>
