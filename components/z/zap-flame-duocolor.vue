<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n0u3ty-jh"/><path class="sxw57bc9x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zap-flame-duocolor" /></template>
<style>
.n0u3ty-jh {
  stroke-opacity: 0.4;
  d: path("M13.667 15a1.333 1.333 0 1 0 2.666 0c0-1-.333-1.333-.666-2C15 11.667 15.333 10.333 17 9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sxw57bc9x {
  d: path("m9.417 11.333l2.501-3.145a.322.322 0 0 0-.251-.521H9.5A.667.667 0 0 1 8.833 7V3.667a.233.233 0 0 0-.415-.145l-5.003 6.29a.322.322 0 0 0 .252.521h2.166c.369 0 .667.299.667.667v3.333c0 .22.278.318.415.145zM17 9c.333 1.667 1.333 3 2.667 4c1 1 1.333 2.333 1.333 4a4 4 0 1 1-8 0c0-1 .333-1.667.667-2");
}

</style>
