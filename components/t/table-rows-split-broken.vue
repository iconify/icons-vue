<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dcow-7one"/><path class="l2rphre0b"/><path class="mgsmsibos"/><path class="xa5lkibuy"/><path class="s5mp_40sj"/><path class="dxu3yjbpm"/><path class="ene5oxz4n"/><path class="b1sely7dw"/><path class="m2niebc2z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:table-rows-split-broken" /></template>
<style>
.b1sely7dw {
  d: path("M8.67554 1.99084L8.67554 8.01877");
}

.dcow-7one {
  d: path("M15.342 22.0231L15.342 13.0231");
}

.dxu3yjbpm {
  d: path("M14.009 13.0231C17.7803 13.0231 19.6659 13.0231 20.8375 14.1946C22.009 15.3662 22.009 17.2518 22.009 21.0231L22.009 22.0231");
}

.ene5oxz4n {
  d: path("M15.342 2.02454L15.342 8.01874");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l2rphre0b {
  d: path("M8.67554 22.0231L8.67554 13.0231");
}

.m2niebc2z {
  d: path("M2.01807 2.03126C2.05438 4.503 2.23928 5.90561 3.18077 6.8471C4.35234 8.01868 6.23796 8.01868 10.0092 8.01868L14.0092 8.01868C17.7804 8.01868 19.666 8.01868 20.8376 6.8471C21.78 5.90473 21.9644 4.50038 22.0004 2.02433");
}

.mgsmsibos {
  d: path("M2.01782 19.0231L22.0004 19.0231");
}

.s5mp_40sj {
  d: path("M10.009 13.0231C6.2378 13.0231 4.35218 13.0231 3.18061 14.1946C2.00903 15.3662 2.00903 17.2518 2.00903 21.0231L2.00903 22.0231");
}

.xa5lkibuy {
  d: path("M2.01782 10.5231L3.6817 10.5231M20.3592 10.5231L22.0231 10.5231M7.01172 10.5231L10.3578 10.5231M13.6691 10.5231L17.0152 10.5231");
}

</style>
