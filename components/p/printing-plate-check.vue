<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lgyr4rbvl"/><path class="bnf4sobfq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:printing-plate-check" /></template>
<style>
.bnf4sobfq {
  d: path("M8 11a3 3 0 1 0 6 0a3 3 0 1 0-6 0m3-4.75v9.5M6.25 11h9.5m-1 7l2 2L21 15.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lgyr4rbvl {
  d: path("M14.272 21.5H6.621q-.148 0-.292-.029q-.145-.029-.282-.085t-.259-.139q-.123-.082-.227-.186l-1.622-1.622q-.104-.104-.186-.227t-.139-.259q-.056-.137-.085-.282t-.029-.292V5.621q0-.148.029-.292q.029-.145.085-.282t.139-.259q.082-.123.186-.227l1.622-1.622q.104-.104.227-.186t.259-.139q.137-.056.282-.085t.292-.029h10.758q.148 0 .292.029q.145.029.282.085t.259.139q.123.082.227.186l1.622 1.622q.104.104.186.227t.139.259q.056.137.085.282t.029.292v7.354");
}

</style>
