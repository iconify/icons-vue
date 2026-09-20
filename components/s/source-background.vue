<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGBNWnxccY)" class="r4i437pya"/><path class="k8rhw6bim"/></g><defs><linearGradient id="SVGBNWnxccY" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="dbvqxqbzl"/><stop offset="1" class="jg-xypbyg"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:source-background" /></template>
<style>
.dbvqxqbzl {
  stop-color: var(--svg-color--ed69ff, #ed69ff);
}

.ft5dv1b6b {
  fill: none;
}

.jg-xypbyg {
  stop-color: var(--svg-color--7b61f4, #7b61f4);
}

.k8rhw6bim {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.885 11.59c-.72-.635-2.16-2.115-2.16-2.94C9.725 7.62 10.805 7 12.5 7c.63 0 1.1.505 1.74 1.19l.44.46c.88.905 1.135 1.025 1.845 1.025S18 9.41 18 7.65C18 5.88 15.255 4 11.885 4C8.52 4 6 6.7 6 8.5c0 1.81 2.5 3.59 5.885 3.09m.23.82c.72.635 2.16 2.115 2.16 2.94c0 1.03-1.89 1.5-2.65 1.5s-1.425-.6-2.305-1.5c-.88-.905-1.135-1.025-1.845-1.025S6 14.59 6 16.35C6 18.12 8.745 20 12.115 20C15.48 20 18 17.3 18 15.5c0-1.81-2.5-3.59-5.885-3.09");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
