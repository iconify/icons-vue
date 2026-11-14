<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t9sxlta2n"/><path class="uim_zsn6w"/><path class="ejqfcpbbw"/><path class="hkpkpybts"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rupee-broken" /></template>
<style>
.ejqfcpbbw {
  d: path("M9 7H15.25");
}

.hkpkpybts {
  d: path("M9 9.75H15.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t9sxlta2n {
  d: path("M6.99975 3.33969C11.3457 0.830591 16.8783 1.93109 19.9332 5.91239C22.9882 9.89369 22.6192 15.5226 19.0708 19.0711C15.5223 22.6195 9.89345 22.9885 5.91215 19.9335C1.93085 16.8786 0.830347 11.346 3.33945 6.99999");
}

.uim_zsn6w {
  d: path("M9 7H11.25C12.7688 7 14 8.2312 14 9.75C14 11.2688 12.7688 12.5 11.25 12.5H9L13.75 17.25");
}

</style>
