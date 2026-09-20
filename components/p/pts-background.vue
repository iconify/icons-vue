<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGr0WoRdZc)" class="r4i437pya"/><path class="q686ikbjv"/></g><defs><linearGradient id="SVGr0WoRdZc" x1="4.277" x2="21.151" y1="18.208" y2="14.795" gradientUnits="userSpaceOnUse"><stop class="dlupnn6qn"/><stop offset=".54" class="sll0kmo4p"/><stop offset=".8" class="ct0o6k2bn"/><stop offset="1" class="fk3a3gb7j"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pts-background" /></template>
<style>
.ct0o6k2bn {
  stop-color: var(--svg-color--9246e2, #9246e2);
}

.dlupnn6qn {
  stop-color: var(--svg-color--fd8c30, #fd8c30);
}

.fk3a3gb7j {
  stop-color: var(--svg-color--6966ff, #6966ff);
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q686ikbjv {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.2 4.656A6.08 6.08 0 0 0 7.84 6.88c-.363.544-.587 1.243-1.92 5.984a99 99 0 0 1-1.734 5.776c-.122.224-.208.507-.181.624c.037.197.15.213 1.333.197c1.643-.015 2-.085 2.373-.463c.486-.497.662-.96 1.376-3.654c.992-3.749 1.617-5.706 1.958-6.16c.635-.864 1.845-.917 3.328-.917c1.248 0 1.28-.144.448 2.773c-.368 1.28-1.542 2.102-3.21 2.24c-.428.032-.844.107-.918.17c-.187.155-.176 1.153.016 1.537c.538 1.05 1.866 1.253 2.965 1.28c1.877.053 3.27-.87 4.219-2.88c.65-1.37.842-2.064 1.226-4.368c.192-1.141.502-2.56.694-3.147c.085-.256.144-.533.181-.773c.048-.304-.197-.565-.507-.565h-3.696s-4.08-.006-4.597.122z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.sll0kmo4p {
  stop-color: var(--svg-color--c720b6, #c720b6);
}

</style>
