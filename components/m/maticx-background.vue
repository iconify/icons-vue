<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="l3vvsuk2q"/><path class="sxykr0-gp"/><path class="ekttyhbtu"/><path class="erttf2rnr"/><path class="qfk-z9bad"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:maticx-background" /></template>
<style>
.ekttyhbtu {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.755 7.956L11.973 5.2L8.178 7.422l.915.391l2.84-1.702l3.022 1.773l-3.889 2.36l3.734 2.151l.897-.435l-3.026-1.662l4.084-2.338z");
}

.erttf2rnr {
  fill: var(--svg-color--fff, #fff);
  d: path("m14.04 9.752l-.978.542l2.933 1.613v4.55l.894.476v-5.51l-2.85-1.676zm2.804 7.368l-.933-.498l-3.92 2.333l-3.169-1.844l4-2.289L7.978 12l-.769.587l3.87 2.213l-3.826 2.378L11.995 20z");
}

.ft5dv1b6b {
  fill: none;
}

.l3vvsuk2q {
  fill: var(--svg-color--762fed, #762fed);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.qfk-z9bad {
  fill: var(--svg-color--fff, #fff);
  d: path("m7.111 17.044l3.6-2.236l-.862-.47L7.11 15.95zm5.787-2.391v-1.036L9 11.457V7.973l-.933-.4v4.258zm-2.765 1.964l-.933.498l2.693 1.569v-1.111zm1.947.964v1.098l3.733-2.222v-4.346l-.915.444v3.422l-2.822 1.6zm-1.071-7.524l3.586-2.177l-.822-.516l-2.764 1.618z");
}

.sxykr0-gp {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.88 4.013v1.023l-4 2.337v4.466l-.769.587v-5.71zM12.066 4v1.031l4.823 2.791V6.711z");
}

</style>
