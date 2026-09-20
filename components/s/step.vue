<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="z96bhubmx"/><path class="d954c73us"/><path class="bmgs636es"/><path class="l-cba7bqv"/><path class="z09xqtg5m"/><path class="n60fop78d"/><path class="a_twbckkw"/><path class="doxsapbbk"/><path class="aon8-nbgy"/><path class="blej3_b8l"/><path class="ljzz5g4nj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:step" /></template>
<style>
.a_twbckkw {
  fill: var(--svg-color--ff965e, #ff965e);
  d: path("m6.5 11.949l8 4.63L12 18l-8-4.498z");
}

.aon8-nbgy {
  fill: var(--svg-color--06d6a0, #06d6a0);
  d: path("M17.502 8.885L20 7.518v8.998l-2.498 1.388z");
}

.blej3_b8l {
  fill: var(--svg-color--ffd166, #ffd166);
  d: path("m14.498 13.593l3.002-1.697v6.01l-3.003 1.676z");
}

.bmgs636es {
  fill: var(--svg-color--00f8b7, #00f8b7);
  d: path("M12.004 3L20 7.499l-2.5 1.624l-8-4.706z");
}

.d954c73us {
  fill: var(--svg-color--118ab2, #118ab2);
  d: path("m4 7.509l8.003-4.5v8.999L4 16.508z");
}

.doxsapbbk {
  fill: var(--svg-color--d94c00, #d94c00);
  d: path("M12 18v3l-8-4.503v-3z");
}

.ft5dv1b6b {
  fill: none;
}

.l-cba7bqv {
  fill: var(--svg-color--09bd8e, #09bd8e);
  d: path("M17.5 8.87v3.044l-8-4.537V4.411z");
}

.ljzz5g4nj {
  fill: var(--svg-color--f3722c, #f3722c);
  d: path("m12 17.997l2.497-1.422v3.023L12 20.997z");
}

.n60fop78d {
  fill: var(--svg-color--ffbb1d, #ffbb1d);
  d: path("M14.498 13.593v3.027L6.5 11.95V9.06z");
}

.z09xqtg5m {
  fill: var(--svg-color--ffe3a3, #ffe3a3);
  d: path("m9.498 7.378l8.001 4.524l-3 1.692l-7.997-4.528z");
}

.z96bhubmx {
  fill: var(--svg-color--64c557, #64c557);
  fill-rule: evenodd;
  d: path("M19.994 16.498v-8.99l-7.995-4.5v8.994L4.005 16.5l7.997 4.5l7.987-4.495l.005.003v-.005l.003-.002z");
}

</style>
