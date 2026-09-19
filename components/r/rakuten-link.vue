<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bhku_-bpe"/><circle class="cqty7ubeh"/><path class="s938i_brp"/><path class="m1mmjf99z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rakuten-link" /></template>
<style>
.bhku_-bpe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.573 29.043v7.764m0-1.65l3.493-3.494m-2.426 2.426l2.814 2.718m-6.04 0v-3.203a1.947 1.947 0 0 0-1.94-1.94h0a1.947 1.947 0 0 0-1.942 1.94v3.203m0-3.203v-1.941");
}

.cqty7ubeh {
  cx: 21.142px;
  cy: 29.334px;
  r: 0.75px;
  fill: currentColor;
}

.m1mmjf99z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.836 39.153c31.413 6.639 33.708-22.53 18.693-30.286C17.58.112-7.06 16.538 10.597 35.634c-.307 2.565-1.65 4.232-2.971 5.917c3.378-.02 5.778-1.229 8.21-2.398");
}

.s938i_brp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.142 31.663v5.144m-5.748-7.764v7.764h3.882m13.591-26.218c1.524 1.806 3.534 4.427 1.032 7.52a22.68 22.68 0 0 1-20.347 8.698c-3.507-.264-3.45-3.85-3.686-5.64l6.045-1.253l1.142 2.728c6.06.176 10.113-2.563 11.833-4.976l-1.07-3.023z");
}

</style>
