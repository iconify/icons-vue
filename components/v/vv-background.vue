<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGjJ82lbUW)" class="r4i437pya"/><path class="lb7eap-ka"/></g><defs><linearGradient id="SVGjJ82lbUW" x1="17.735" x2="7.035" y1="7.477" y2="14.634" gradientUnits="userSpaceOnUse"><stop class="erj-oubkr"/><stop offset="1" class="aj2p6rrfx"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:vv-background" /></template>
<style>
.aj2p6rrfx {
  stop-color: var(--svg-color--76d7ff, #76d7ff);
}

.erj-oubkr {
  stop-color: var(--svg-color--49a1ff, #49a1ff);
}

.ft5dv1b6b {
  fill: none;
}

.lb7eap-ka {
  fill: var(--svg-color--fff, #fff);
  d: path("m13.67 15.213l-.189.31a.7.7 0 0 1-.094.104a.033.033 0 0 1-.042 0a.3.3 0 0 1-.085-.084l-1.016-1.694l3.717-6.146a.7.7 0 0 0 .075-.226a.34.34 0 0 0-.047-.22c-.07-.114-.22-.184-.353-.198H5.365a1.6 1.6 0 0 0-.597.084c-.024.01-.029 0-.015-.014q.353-.563.711-1.106c.08-.113.17-.254.268-.357c.247-.263.582-.424.941-.452c.071-.019.165-.038.283-.038h10.409a1.46 1.46 0 0 1 1.129.532a.3.3 0 0 1 .056.09c.01.032.029.065.047.094q.07.112.104.211c.089.279.072.58-.047.847l-.16.278zm-1.558-.908q.416.69.828 1.384c.07.122.174.23.31.268c.274.07.457-.141.575-.339L18.907 7.2c.085-.141.141-.301.165-.461q.006-.022.018 0l.076.131c.244.424.498.866.706 1.27a1.34 1.34 0 0 1-.066 1.267L14.6 18.074a1.47 1.47 0 0 1-1.19.749a1.35 1.35 0 0 1-1.064-.448a1 1 0 0 1-.131-.188l-.01-.01L7.21 9.939l-.024-.047c-.047-.075-.099-.155-.122-.244c-.005-.033.01-.047.038-.057h.018l.071-.014h2.052l.004-.001l.005.001c.95 1.581 1.906 3.153 2.861 4.73m3.567-6.931a.4.4 0 0 0-.17-.038h-2.964q-3.592.01-7.185.01a1.4 1.4 0 0 0-.989.376a1 1 0 0 0-.14.193l-.015.028l-.042.047a.4.4 0 0 0-.052.08a1.34 1.34 0 0 0 .075 1.257l.226.376L9.52 18.08a1.55 1.55 0 0 0 1.073.73l.104.004l.098.01h1.46l-4.542-7.417l-.88-1.458a1 1 0 0 1-.094-.226a.37.37 0 0 1 .236-.48l.047-.014h.014c.014 0 .023 0 .033-.01a.3.3 0 0 1 .094-.014L14.63 9.2l1.02-1.694a.24.24 0 0 0 .034-.118z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

</style>
