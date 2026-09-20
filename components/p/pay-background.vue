<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="xgweoubff"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pay-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.xgweoubff {
  fill: var(--svg-color--fff, #fff);
  d: path("M19.938 11.784a.8.8 0 0 0-.153-.217c-1.382-1.559-4.212-4.62-4.212-4.62l-3.571 3.884l-3.615-3.848s-2.851 3.09-4.248 4.663c-.182.173-.182.498-.022.686c.728.816 4.292 4.713 4.292 4.713l3.593-3.89l3.564 3.897l4.306-4.727s.095-.094.11-.152a.53.53 0 0 0-.044-.39m-13.82.432c-.11-.144-.073-.36.036-.483c.458-.513 2.277-2.454 2.277-2.454l2.545 2.67l-2.545 2.765s-1.557-1.653-2.306-2.505zm11.637.087a1.7 1.7 0 0 1-.189.26l-1.97 2.122L13.048 12l2.502-2.721s1.448 1.48 2.11 2.273c.05.073.116.145.145.224c.066.173.022.361-.05.527");
}

</style>
