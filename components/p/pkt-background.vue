<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ohfqw6hef"/><path class="q_bfu4ukd"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pkt-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ohfqw6hef {
  fill: var(--svg-color--171837, #171837);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q_bfu4ukd {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.539 12.93c-.254 0-.655-.207-.655-.453v-1.034H20v-1.117h-1.116V9.21h-.335l-.782 1.116h-1.216l-1.016 1.489V9.21h-1.116v2.456c-.205-.796-.79-1.321-1.675-1.321c-.283 0-.685.067-.93.2v-.219h-1.116v4.837h1.116v-1.361c.26.156.629.234.93.23c.886 0 1.47-.528 1.675-1.32v1.335h1.116v-1.593l1.06 1.593h1.321l-1.258-1.939l.484-.665h.625v1.239a1.376 1.376 0 0 0 1.403 1.365H20v-1.116zm-6.884.05c-.45 0-.781-.336-.781-.793c0-.454.33-.79.78-.79c.451 0 .782.336.782.79a.77.77 0 0 1-.781.792M5.86 10.325H4.372v1.489H5.86zm-.744-1.488H4v1.116h1.116zm2.233 0H6.233v1.116h1.116zm-1.489.372h-.372v.372h.372zm4.093 1.488v2.888a.834.834 0 0 1-.833.833H6.233v-3.72z");
}

</style>
