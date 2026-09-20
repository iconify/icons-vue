<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="hiv0i0c-h"/><path class="lxc7xo6rp"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:shimmer-evm-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.hiv0i0c-h {
  fill: var(--svg-color--00e0ca, #00e0ca);
  d: path("M24 0H0v24h24z");
}

.lxc7xo6rp {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.766 6.157c-2.64-2.822-6.98-2.883-9.693-.135c-2.712 2.747-2.77 7.263-.13 10.086l1.736-1.759c-1.703-1.831-1.662-4.752.094-6.531a4.324 4.324 0 0 1 6.277.078zM6.234 17.843c2.64 2.822 6.98 2.883 9.693.135c2.712-2.747 2.77-7.263.13-10.086l-1.735 1.759c1.702 1.831 1.661 4.752-.095 6.531a4.324 4.324 0 0 1-6.276-.078z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
