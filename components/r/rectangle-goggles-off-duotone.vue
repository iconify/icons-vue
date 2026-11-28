<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s28rwqp-a"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:rectangle-goggles-off-duotone" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s28rwqp-a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.88 19H16.9612C16.0499 19 15.188 18.5857 14.6187 17.8742L11.9999 14.6009L9.3814 17.8741C8.812 18.5857 7.9501 19 7.0388 19H4C2.3432 19 1 17.6569 1 16V8C1 6.3431 2.3431 5 4 5H4.88L18.88 19ZM21.2678 17.0251L10.9498 6.7071C10.7688 6.5262 10.6569 6.2762 10.6569 6C10.6569 5.4477 11.1046 5 11.6569 5H12H20C21.6569 5 23 6.3432 23 8V16C23 16.1661 22.9865 16.329 22.9605 16.4878C22.8799 16.9592 22.4693 17.318 21.9749 17.318C21.6988 17.318 21.4488 17.2061 21.2678 17.0251Z");
  stroke: none;
}

</style>
