<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG197d0drG)" class="a760g-wqe"/><defs><linearGradient id="SVG197d0drG" x1="17.638" x2="6.18" y1="5.015" y2="18.565" gradientUnits="userSpaceOnUse"><stop class="fd4p3kd0x"/><stop offset="1" class="tdm9ps87s"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mvi" /></template>
<style>
.a760g-wqe {
  d: path("M16.91 3a1.637 1.637 0 1 0 0 3.274a1.637 1.637 0 0 0 0-3.274M5.334 10.364C5.335 9.616 8.318 9 12 9s6.666.616 6.666 1.364c0 .752-3.339 1.363-6.666 1.363c-3.338 0-6.665-.6-6.665-1.363m-2.062.272s0 2.182 8.727 2.182s8.727-2.182 8.727-2.182c0 2.237-2.061 6.95-3.338 7.757c-.654.414-.845-.317-1.047-1.108c-.191-.741-.398-1.532-1.015-1.494c-.632.043-1.145 1.325-1.658 2.613C13.151 19.702 12.633 21 12 21s-1.146-1.31-1.658-2.607c-.524-1.32-1.037-2.635-1.68-2.597c-.606.044-.818.819-1.004 1.539c-.207.78-.393 1.489-1.058 1.063c-1.26-.807-3.327-5.514-3.327-7.762");
}

.fd4p3kd0x {
  stop-color: var(--svg-color--3afce7, #3afce7);
}

.ft5dv1b6b {
  fill: none;
}

.tdm9ps87s {
  stop-color: var(--svg-color--fc5cdd, #fc5cdd);
}

</style>
