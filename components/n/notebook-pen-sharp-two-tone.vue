<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qb5o5mz7d"/><path class="cv08j1bxd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:notebook-pen-sharp-two-tone" /></template>
<style>
.cv08j1bxd {
  d: path("M20 11.1317L20 22L4 22L4 2L14.8683 2M1 7L7 7M1 12L7 12M1 17L7 17M11.5 12.5L15.6248 10.8501L21.4874 4.9874C22.1709 4.304 22.1709 3.196 21.4874 2.5126C20.804 1.8291 19.696 1.8291 19.0126 2.5126L13.1499 8.3752L11.5 12.5Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qb5o5mz7d {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.8714 13.4285L15.9962 11.7786C16.1219 11.7283 16.2361 11.653 16.3319 11.5572L22.1945 5.6945C23.2685 4.6206 23.2685 2.8794 22.1945 1.8055C21.1206 0.7315 19.3794 0.7315 18.3055 1.8055L12.4428 7.6681C12.347 7.7639 12.2717 7.8781 12.2214 8.0038L10.5715 12.1286C10.423 12.5 10.51 12.9242 10.7929 13.2071C11.0758 13.49 11.5 13.577 11.8714 13.4285Z");
  stroke: none;
}

</style>
