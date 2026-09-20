<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="mfs0t3ixa"/><path class="oez7modxj"/><path class="zb5ew2slh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mir" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mfs0t3ixa {
  fill: var(--svg-color--01d8dd, #01d8dd);
  fill-rule: evenodd;
  d: path("m3.833 5.905l5.84-2.455c.854-.34 2.93-.815 4.405 0c1.475.817 1.441 1.732 1.24 2.088l5.172 1.148l-2.121 1.13l-4.535-1.13l-1.615.637l3.392 1.865l-2.79 1.514zm5.256-.296l2.007-.827c.252-.091.829-.219 1.126 0c.37.271.162.612-.175.827c-.269.172-1.078.54-1.45.703z");
}

.oez7modxj {
  fill: var(--svg-color--00a3fe, #00a3fe);
  d: path("M3.273 6.852v9.305l2.182 1.122v-5.51l1.552 3.614l2.266-1.998v5.926L12.546 21v-9.456l-3.07-1.442l-2.078 1.589l-1.942-3.695z");
}

.zb5ew2slh {
  fill: var(--svg-color--0061fe, #0061fe);
  d: path("m20.727 7.67l-7.636 3.78v2.271l2.727-1.317v4.753l-2.727 1.336v2.252l7.636-4.027v-2.233l-2.182 1.278V11.01l2.182-1.145z");
}

</style>
