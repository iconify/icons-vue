<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mh8qyk3wx"/><path class="laiy2jm3n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shuffle-broken" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.laiy2jm3n {
  d: path("M2 7H6.66762C7.28299 7 7.59068 7 7.8746 7.05526C8.51417 7.17975 9.09582 7.50908 9.53163 7.99346C9.72509 8.20848 9.88339 8.47232 10.2 9M22 17H17.3324C16.717 17 16.4093 17 16.1254 16.9447C15.4858 16.8202 14.9042 16.4909 14.4684 16.0065C14.2749 15.7915 14.1166 15.5277 13.8 15M20 19L22 17L20 15");
}

.mh8qyk3wx {
  d: path("M2 17H5.60286M22 7H18.3971C16.7379 7 15.9082 7 15.2205 7.3894C14.5327 7.7788 14.1059 8.49021 13.2522 9.91303L10.7478 14.087L10.7478 14.087C10.0958 15.1737 9.69278 15.8454 9.23234 16.2756M20 5L22 7L20 9");
}

</style>
