<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="z5f2lj36f"/><path class="h_u-lh--u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mountains-linear" /></template>
<style>
.h_u-lh--u {
  d: path("M5.80762 8.21249C7.30762 9.71249 8.50762 9.61249 9.40762 8.61249C10.3076 7.61249 11.4076 8.51249 12.5076 8.11249");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z5f2lj36f {
  d: path("M12.0074 19.7125H5.80736C2.80736 19.7125 1.90736 18.2125 3.00736 15.4125L6.10736 7.21248C7.60736 3.31248 10.7074 3.31248 12.2074 7.21248L13.0074 9.31248C13.6074 10.8125 14.6074 10.8125 15.3074 9.41248C16.4074 7.31248 18.5074 7.41248 19.5074 10.1125L21.1074 15.5125C22.0074 18.2125 21.1074 19.7125 18.2074 19.7125H12.0074Z");
}

</style>
