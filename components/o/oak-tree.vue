<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7zcw7okq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:oak-tree" /></template>
<style>
.c7zcw7okq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.097 13.305q1.016 2.794 3.949 2.445H9.69l-.438 5.692q-.005.074.003.147q.009.074.032.144t.059.135t.085.12t.106.102q.058.045.124.079q.066.033.137.053t.144.026q.074.005.147-.003q.074-.009.144-.032t.135-.059t.12-.085q.056-.048.102-.106t.079-.124t.053-.137t.026-.144l.447-5.808h1.61l.447 5.808q.006.073.026.144t.053.137t.079.124t.102.106t.12.085q.065.036.135.059t.144.032q.073.008.147.003q.073-.006.144-.026t.137-.053t.124-.079t.106-.102t.085-.12q.036-.065.059-.135t.032-.144q.008-.073.003-.147l-.438-5.692h3.644q2.933.349 3.949-2.445q.921-2.533-1.026-4.098q.564-2.214-1.153-3.931q-1.702-1.703-3.893-1.163Q14.483 2.186 12 2.186T8.169 4.113q-2.191-.54-3.893 1.163q-1.717 1.717-1.153 3.931q-1.947 1.565-1.026 4.098");
}

</style>
