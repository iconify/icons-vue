<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="ri2m-q_tv"/><path class="r3uulhbhd"/><path class="n-fiqpbfy"/><path class="kw1bmjbqj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:progressive-delivery-outline-bold" /></template>
<style>
.kw1bmjbqj {
  d: path("M16 8v7");
}

.n-fiqpbfy {
  d: path("M12 10v5");
}

.r3uulhbhd {
  d: path("M8 12v3");
}

.ri2m-q_tv {
  d: path("M4 3v18M4 6h16M4 18h16m0 -15v18");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
