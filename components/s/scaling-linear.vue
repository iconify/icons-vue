<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="p-zmx2i0x"/><path class="k_eyoabrm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:scaling-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k_eyoabrm {
  stroke-linejoin: round;
  d: path("M22 2L21 3L13 11L12 12M22 7.34375V2H16.6562M12 8V12H16");
}

.p-zmx2i0x {
  d: path("M11.0002 2C6.94512 2.0073 4.82168 2.10686 3.46465 3.46389C2.00018 4.92835 2.00018 7.28538 2.00018 11.9994C2.00018 16.7135 2.00018 19.0705 3.46465 20.535C4.92912 21.9994 7.28614 21.9994 12.0002 21.9994C16.7142 21.9994 19.0713 21.9994 20.5357 20.535C21.8927 19.1779 21.9923 17.0545 21.9996 12.9994");
}

</style>
