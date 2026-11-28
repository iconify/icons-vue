<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="z_eptqokc"/><path class="he7q03bah"/><path clip-rule="evenodd" class="qdd8qlbto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:star-half-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.he7q03bah {
  d: path("M11.535 2.316C11.61 2.125 11.795 2 12 2C12.205 2 12.39 2.125 12.465 2.316L14.973 8.676L21.542 9.231C21.801 9.253 22 9.47 22 9.73C22 9.871 21.94 10.006 21.835 10.101L16.81 14.641L18.337 21.39C18.345 21.426 18.349 21.463 18.349 21.5C18.349 21.776 18.125 22 17.849 22C17.753 22 17.659 21.972 17.578 21.92L12 18.327L6.422 21.92C6.341 21.972 6.247 22 6.151 22C5.875 22 5.651 21.776 5.651 21.5C5.651 21.463 5.655 21.426 5.663 21.39L7.19 14.641L2.165 10.101C2.06 10.006 2 9.871 2 9.73C2 9.47 2.199 9.253 2.458 9.231L9.027 8.676L11.535 2.316Z");
}

.qdd8qlbto {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2C12.205 2 12.39 2.125 12.465 2.316L14.973 8.676L21.542 9.231C21.801 9.253 22 9.47 22 9.73C22 9.871 21.94 10.006 21.835 10.101L16.81 14.641L18.337 21.39C18.345 21.426 18.349 21.463 18.349 21.5C18.349 21.776 18.125 22 17.849 22C17.753 22 17.659 21.972 17.578 21.92L12 18.327V2Z");
  stroke: none;
}

.z_eptqokc {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M10.605 1.95C10.831 1.377 11.384 1 12 1C12.616 1 13.169 1.377 13.395 1.95L15.676 7.732L21.626 8.235C22.403 8.3 23 8.95 23 9.73C23 10.154 22.82 10.558 22.506 10.843L17.915 14.99L19.312 21.169C19.337 21.278 19.349 21.389 19.349 21.5C19.349 22.329 18.678 23 17.849 23C17.561 23 17.279 22.917 17.037 22.761L12 19.516L6.963 22.761C6.721 22.917 6.439 23 6.151 23C5.322 23 4.651 22.329 4.651 21.5C4.651 21.389 4.663 21.278 4.688 21.169L6.085 14.99L1.494 10.843C1.179 10.558 1 10.154 1 9.73C1 8.95 1.597 8.3 2.374 8.235L8.324 7.732L10.605 1.95Z");
  stroke: none;
}

</style>
