<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="a-bf3ab0h"/><path class="ct6i7jvyq"/><path class="o4gjwlb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:page-facing-up" /></template>
<style>
.a-bf3ab0h {
  fill: var(--svg-color--fff, #fff);
  d: path("M87.85 6.19H16.8v115.45h94.62V28.8z");
}

.ct6i7jvyq {
  fill: none;
  stroke: var(--svg-color--b0bec5, #b0bec5);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  stroke-width: var(--svg-stroke-width--3-865px, 3.865px);
  d: path("M33.34 41.05H94.5M33.34 55.68H94.5M33.34 70.3H94.5M33.34 84.93H94.5M33.34 99.56h26.15");
}

.o4gjwlb9i {
  fill: var(--svg-color--6fbff0, #6fbff0);
  d: path("M109.45 23.59L92.79 6.88A10.56 10.56 0 0 0 85.54 4h-68.5c-1.55 0-2.81 1.26-2.81 2.81v114.38c0 1.55 1.26 2.81 2.81 2.81h93.93c1.55 0 2.81-1.26 2.81-2.81V31.28c-.01-2.91-2.21-5.69-4.33-7.69m.32 96.41H18.23V8h64.66c2.12 0 3.85 1.72 3.85 3.85v17.88h17.34c3.14 0 5.69 1.73 5.69 5.69z");
}

</style>
