<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="fd1-y-r9o"/><path class="dn3p22tcu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pants-sharp-two-tone" /></template>
<style>
.dn3p22tcu {
  d: path("M18.602 7.06L20.995 21.08L15.902 22L12.049 10.27L8.003 22L3.004 20.99L5.397 7.06L5.594 6.05L6.382 2H17.617L18.405 6.05L18.602 7.06ZM5.397 7.06H18.602");
}

.fd1-y-r9o {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.616 1C18.095 1 18.507 1.34 18.599 1.81L19.586 6.88L21.98 20.91C22.073 21.45 21.712 21.97 21.172 22.07L16.079 22.98C15.588 23.07 15.107 22.78 14.951 22.31L12.025 13.4L8.948 22.32C8.785 22.8 8.296 23.08 7.806 22.98L2.807 21.97C2.276 21.87 1.927 21.36 2.018 20.82L4.411 6.89C4.412 6.89 4.414 6.88 4.415 6.87L5.407 1.77C5.529 1.35 5.934 1 6.383 1H17.616Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
