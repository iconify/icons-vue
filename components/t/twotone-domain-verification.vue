<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o6xq-5b8x"/><path class="iud3xt7yz"/><path class="m_gsnq25f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-domain-verification" /></template>
<style>
.iud3xt7yz {
  fill: currentColor;
  d: path("m16.6 10.88l-1.42-1.42l-4.24 4.25l-2.12-2.13L7.4 13l3.54 3.54z");
}

.m_gsnq25f {
  fill: currentColor;
  d: path("M19 4H5a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h14c1.1 0 2-.9 2-2V6a2 2 0 0 0-2-2m0 14H5V8h14z");
}

.o6xq-5b8x {
  fill: currentColor;
  d: path("M5 18h14V8H5zm3.82-6.42l2.12 2.12l4.24-4.24l1.41 1.41l-5.66 5.66L7.4 13z");
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
