<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t9sxlta2n"/><path class="y8xknhx_a"/><path class="bxmaetxyp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:pound-broken" /></template>
<style>
.bxmaetxyp {
  d: path("M8.75 12.5H13.25");
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

.y8xknhx_a {
  d: path("M15 9.25C15 8.0074 13.9926 7 12.75 7C11.5074 7 10.5 8.0074 10.5 9.25V14.5C10.5 16 9.8 17 8.75 17H15.25");
}

</style>
