<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="by0j17bcs"/><path class="ln9az9bih"/><path class="ir-c3ybvu"/><path class="zt2y_nbzo"/><path class="nfickx-pq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:trackball" /></template>
<style>
.by0j17bcs {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M33 17c0 9.389-2.188 19-15 19S3 26.389 3 17S8.611 3 18 3c9.465 0 15 4.701 15 14");
}

.ir-c3ybvu {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M29 12.5c0 5.246-4.925 8.5-11 8.5S7 17.746 7 12.5S11.925 3 18 3s11 4.253 11 9.5");
}

.ln9az9bih {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M32 13.969C32 21.891 30.062 30 18 30S4 21.891 4 13.969S9.237 3 18 3s14 3.047 14 10.969");
}

.nfickx-pq {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M17 23v4.75c0 1-9.672-1-9.672-6c0-1.375.301-1.973 2.315-.984C14.134 22.969 17 22.452 17 23m2 0v4.75c0 1 9.672-1 9.672-6c0-1.375-.301-1.973-2.316-.984C21.865 22.969 19 22.452 19 23");
}

.zt2y_nbzo {
  fill: var(--svg-color--744eaa, #744eaa);
  d: path("M28 10c0 5.523-4.478 8-10 8S8 15.523 8 10S12.477 0 18 0s10 4.477 10 10");
}

</style>
