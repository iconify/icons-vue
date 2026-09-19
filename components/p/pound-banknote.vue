<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="cezisi8is"/><path class="cbt1zke3z"/><path class="c3l22j6pw"/><path class="fv4_zwb0m"/><path class="f-aksmbec"/><circle class="v5j-hvblv"/><path class="g0169xokb"/><path class="hj64ttb_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:pound-banknote" /></template>
<style>
.c3l22j6pw {
  fill: var(--svg-color--94989b, #94989b);
  d: path("M24 46.5h16v9H24z");
}

.cbt1zke3z {
  fill: var(--svg-color--c28fef, #c28fef);
  d: path("M0 8.5h64v38H0z");
}

.cezisi8is {
  fill: var(--svg-color--9450e0, #9450e0);
  d: path("M0 46.5h64v9H0z");
}

.f-aksmbec {
  fill: var(--svg-color--c28fef, #c28fef);
  d: path("M7 15.5h50v24H7z");
}

.fv4_zwb0m {
  fill: var(--svg-color--9450e0, #9450e0);
  d: path("M4 12.5h56v30H4z");
}

.g0169xokb {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M24 8.5h16v38H24z");
}

.hj64ttb_p {
  fill: var(--svg-color--fff, #fff);
  d: path("M16 30.4c0-.3 0-.6-.1-1h2.9V27h-4.1c-.1-.1-.1-.1-.1-.2c-.1-.2-.3-.4-.4-.5c-.6-.8-.9-1.2-.9-1.9c0-1.5 1.2-2.7 2.8-2.7c1.5 0 2.8 1.2 2.8 2.7H21c0-2.7-2.2-4.9-5-4.9s-5 2.2-5 4.9c0 1.1.5 1.9 1 2.6h-1v2.3h2.5c.2.5.2.8.2 1c0 1.8-1.8 2.9-2.8 3v2.2h10v-2.2h-6c.7-.8 1.1-1.8 1.1-2.9");
}

.v5j-hvblv {
  cx: 45px;
  cy: 27.5px;
  r: 8px;
  fill: var(--svg-color--9450e0, #9450e0);
}

</style>
