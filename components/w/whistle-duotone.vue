<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n-rz4cc5m"/><path class="s9eg1rylf"/><path class="uziu1mb-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:whistle-duotone" /></template>
<style>
.n-rz4cc5m {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.3431 6.3431C1.8965 7.7898 1 9.7911 1 12C1 16.4183 4.5817 20 9 20C13.3624 20 16.9092 16.5084 16.9983 12.1673L21.7692 10.1795C22.5146 9.8689 23 9.1407 23 8.3333L23 6C23 4.8954 22.1046 4 21 4L15 4L9 4C6.7911 4 4.7898 4.8965 3.3431 6.3431Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s9eg1rylf {
  d: path("M9 9.5C10.3807 9.5 11.5 10.6193 11.5 12C11.5 13.3807 10.3807 14.5 9 14.5C7.61929 14.5 6.5 13.3807 6.5 12C6.5 10.6193 7.61929 9.5 9 9.5Z");
}

.uziu1mb-c {
  fill: currentColor;
  d: path("M16 4L16 7C16 7.5523 15.5523 8 15 8C14.4477 8 14 7.5523 14 7L14 4L15 4Z");
  stroke: none;
}

</style>
