<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="mzuq4x0dn"/><path class="ktz4j74-r"/><path class="w29ath28m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:temperature-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ktz4j74-r {
  d: path("M14.5 16.4999C14.5 17.8806 13.3807 18.9999 12 18.9999C10.6193 18.9999 9.5 17.8806 9.5 16.4999C9.5 15.1192 10.6193 13.9999 12 13.9999C13.3807 13.9999 14.5 15.1192 14.5 16.4999Z");
}

.mzuq4x0dn {
  d: path("M17.5 16.5C17.5 19.5376 15.0376 22 12 22C8.96243 22 6.5 19.5376 6.5 16.5C6.5 14.7636 7.30465 13.2152 8.56141 12.2072C8.82505 11.9957 9 11.6857 9 11.3477V5C9 3.34315 10.3431 2 12 2C13.6569 2 15 3.34315 15 5V11.3477C15 11.6857 15.1749 11.9957 15.4386 12.2072C16.6954 13.2152 17.5 14.7636 17.5 16.5Z");
}

.w29ath28m {
  d: path("M12 14V5");
}

</style>
