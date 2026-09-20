<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGgzGuAe5P)" class="gurcqebsk"/><path clip-rule="evenodd" class="t28_o0bgu"/><path clip-rule="evenodd" class="xxgzcacrr"/><path clip-rule="evenodd" class="xxyru7evl"/><defs><linearGradient id="SVGgzGuAe5P" x1="4.451" x2="21" y1="18.034" y2="5.848" gradientUnits="userSpaceOnUse"><stop class="nw2tps4vd"/><stop offset=".261" class="s_xbug--j"/><stop offset=".747" class="jeqn2m-_u"/><stop offset="1" class="ni-7rob8f"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:rpl" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.gurcqebsk {
  d: path("M12 20.34a8.399 8.399 0 1 0 0-16.797a8.399 8.399 0 0 0 0 16.797");
}

.jeqn2m-_u {
  stop-color: var(--svg-color--ff9976, #ff9976);
}

.ni-7rob8f {
  stop-color: var(--svg-color--ff6350, #ff6350);
}

.nw2tps4vd {
  stop-color: var(--svg-color--fb9533, #fb9533);
}

.s_xbug--j {
  stop-color: var(--svg-color--feba67, #feba67);
}

.t28_o0bgu {
  fill: var(--svg-color--ff7534, #ff7534);
  fill-rule: evenodd;
  d: path("M12 20.459A8.457 8.457 0 0 0 20.458 12A8.458 8.458 0 1 0 12 20.459m0-.517A7.941 7.941 0 1 0 12 4.06a7.941 7.941 0 0 0 0 15.882");
}

.xxgzcacrr {
  fill: var(--svg-color--ffd58d, #ffd58d);
  fill-rule: evenodd;
  d: path("M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18m0-.53A8.47 8.47 0 0 0 20.47 12A8.47 8.47 0 0 0 12 3.53A8.47 8.47 0 0 0 3.53 12A8.47 8.47 0 0 0 12 20.47");
}

.xxyru7evl {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("m9.658 11.169l-.864 1.034l1.214.455c.017.459.127.65.18.689l-.463.427l.463.473l.455-.473c.252.093.523.126.79.096l.427 1.241l1.07-.974l.268-1.192c2.473-2.249 2.75-4.043 2.58-4.66c-2.19-.156-4.15 1.646-4.855 2.567zm.052 3.512l-3.669 3.385l-.387-.42l3.669-3.385zm-1.176.079l-3.01 2.752l-.387-.422l3.011-2.753zm1.088 1.053l-3.037 2.792l-.386-.421l3.036-2.791zm3.277-4.075a.707.707 0 1 0 0-1.414a.707.707 0 0 0 0 1.414");
}

</style>
