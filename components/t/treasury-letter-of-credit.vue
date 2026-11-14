<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t16q0vbge"/><path class="u9s36gcyj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:treasury-letter-of-credit" /></template>
<style>
.t16q0vbge {
  d: path("M7.4 19H2.5V5h19v14h-4.9M2.5 6.5l4.539 3.106m9.904.012L21.5 6.5");
}

.u9s36gcyj {
  d: path("m12 9.5l.927.897l1.277-.181l.223 1.271l1.139.604L15 13.25l.566 1.159l-1.139.604l-.223 1.271l-1.277-.181L12 17l-.927-.897l-1.277.181l-.223-1.271l-1.139-.604L9 13.25l-.566-1.159l1.139-.604l.223-1.271l1.277.181Zm0 3.75h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
