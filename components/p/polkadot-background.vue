<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="c8b1vubah"/><path class="s-g9sdb2a"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:polkadot-background" /></template>
<style>
.c8b1vubah {
  fill: var(--svg-color--e6007a, #e6007a);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.s-g9sdb2a {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.82 5.647c0 .908-1.266 1.647-2.824 1.647s-2.824-.739-2.824-1.647S10.444 4 11.996 4c1.553 0 2.823.739 2.823 1.647m0 12.706c0 .908-1.266 1.647-2.824 1.647s-2.824-.739-2.824-1.647s1.272-1.647 2.824-1.647c1.553 0 2.823.739 2.823 1.647M7.925 9.716c.8-1.378.805-2.87.019-3.321c-.791-.457-2.071.296-2.87 1.675c-.801 1.378-.801 2.87-.02 3.322c.79.452 2.07-.298 2.87-1.676m11.002 2.887c.79.447.786 1.91-.01 3.265c-.8 1.355-2.084 2.09-2.87 1.643c-.795-.447-.79-1.91.004-3.267c.8-1.355 2.085-2.088 2.876-1.641M7.949 17.52c.79-.447.786-1.91-.014-3.266c-.795-1.355-2.08-2.09-2.87-1.642c-.795.452-.791 1.91.01 3.265c.794 1.356 2.079 2.095 2.87 1.647zm10.979-9.444c.8 1.378.8 2.865.014 3.317c-.786.457-2.07-.291-2.871-1.675c-.79-1.379-.8-2.865-.014-3.318c.79-.457 2.07.292 2.87 1.676");
}

</style>
