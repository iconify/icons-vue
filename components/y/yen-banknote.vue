<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="g719w11lx"/><path class="p_oyfdb3o"/><path class="c3l22j6pw"/><path class="u0mchcxby"/><path class="nq997ibit"/><circle class="ijhd6_brd"/><path class="g0169xokb"/><path class="vam9glbhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:yen-banknote" /></template>
<style>
.c3l22j6pw {
  fill: var(--svg-color--94989b, #94989b);
  d: path("M24 46.5h16v9H24z");
}

.g0169xokb {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M24 8.5h16v38H24z");
}

.g719w11lx {
  fill: var(--svg-color--89664c, #89664c);
  d: path("M0 46.5h64v9H0z");
}

.ijhd6_brd {
  cx: 45px;
  cy: 27.5px;
  r: 8px;
  fill: var(--svg-color--89664c, #89664c);
}

.nq997ibit {
  fill: var(--svg-color--d3976e, #d3976e);
  d: path("M7 15.5h50v24H7z");
}

.p_oyfdb3o {
  fill: var(--svg-color--d3976e, #d3976e);
  d: path("M0 8.5h64v38H0z");
}

.u0mchcxby {
  fill: var(--svg-color--89664c, #89664c);
  d: path("M4 12.5h56v30H4z");
}

.vam9glbhs {
  fill: var(--svg-color--fff, #fff);
  d: path("m22 21.2l-1.2-1.7l-4.8 4.6l-4.8-4.6l-1.2 1.7l4.5 4.3h-2.3v2.2H15V30h-2.8v2.2H15v3.3h2v-3.3h2.8V30H17v-2.3h2.8v-2.2h-2.3z");
}

</style>
