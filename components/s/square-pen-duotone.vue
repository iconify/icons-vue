<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zp531bggp"/><path class="ugvjznb6m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-pen-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ugvjznb6m {
  fill: currentColor;
  d: path("M10.8714 14.4285L14.9962 12.7786C15.1219 12.7283 15.2361 12.653 15.3319 12.5572L21.1945 6.6945C22.2685 5.6206 22.2685 3.8794 21.1945 2.8055C20.1206 1.7315 18.3794 1.7315 17.3055 2.8055L11.4428 8.6681C11.347 8.7639 11.2717 8.8781 11.2214 9.0038L9.5715 13.1286C9.423 13.5 9.51 13.9242 9.7929 14.2071C10.0758 14.49 10.5 14.577 10.8714 14.4285Z");
  stroke: none;
}

.zp531bggp {
  stroke-opacity: 0.4;
  d: path("M12 3L6 3C4.3431 3 3 4.3431 3 6L3 18C3 19.6569 4.3431 21 6 21L18 21C19.6569 21 21 19.6569 21 18L21 12");
}

</style>
