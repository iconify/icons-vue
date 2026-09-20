<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fal75iy6t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:waterfall-chart-outline-rounded" /></template>
<style>
.fal75iy6t {
  fill: currentColor;
  d: path("M4.274 18.726Q4 18.452 4 18.039V15.25q0-.413.274-.687t.688-.275t.687.274t.274.688v2.789q0 .413-.274.687T4.962 19t-.688-.274m4.683-5.587q-.284-.283-.284-.697v-1.846q0-.413.274-.687t.688-.275t.697.284t.284.697v1.846q0 .414-.275.688q-.274.274-.687.274t-.697-.284m4.692-4.654q-.283-.283-.283-.697V5.961q0-.413.274-.687T14.327 5t.697.284t.284.697v1.827q0 .413-.274.687t-.688.274t-.697-.284m4.692 10.241q-.283-.274-.283-.687V5.961q0-.414.274-.688T19.019 5t.697.274t.284.688v12.077q0 .413-.274.687t-.687.274t-.698-.274");
}

</style>
