<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="s18tri15o"/><path class="x4t_l5bcr"/><path class="m1_y7dy3u"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:shft-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m1_y7dy3u {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.42 8.926c.35 0 .637-.286.59-.631A5.05 5.05 0 0 0 12 4C9.213 4 6.948 6.202 6.948 8.926v3.671l2.315 2.283v.454A2.804 2.804 0 0 0 12 17.894a2.774 2.774 0 0 0 2.737-2.526v-3.032l-2.105-2.084V8.838a.63.63 0 0 0-.64-.623a.63.63 0 0 0-.623.64v1.89l2.315 2.316v2.042c-.017.896-.766 1.528-1.684 1.528s-1.663-.665-1.675-1.558h-.009v-.91l-2.105-2.037v-3.2c0-2.042 1.697-3.663 3.79-3.663a3.764 3.764 0 0 1 3.734 3.032c.059.345.337.631.686.631");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.s18tri15o {
  fill: var(--svg-color--662c5e, #662c5e);
  d: path("M24 0H0v24h24z");
}

.x4t_l5bcr {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.053 11.386v4.012C16.917 17.996 14.702 20 12 20s-4.918-2.034-5.052-4.631v-.072a.632.632 0 0 1 1.263 0v.215c.21 1.848 1.84 3.225 3.79 3.225s3.578-1.31 3.788-3.158v-3.692l-2.105-2.05v-.708c0-.905-.758-1.76-1.684-1.76s-1.684.855-1.684 1.76v2.004l2.316 2.303v1.693c0 .337-.282.66-.632.66s-.631-.32-.631-.66v-1.18l-2.106-2.117v-3.2C9.373 7.255 10.56 6.106 12 6.106a2.77 2.77 0 0 1 2.737 2.526v.476l2.315 2.274z");
}

</style>
