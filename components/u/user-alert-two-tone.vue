<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zihhuqsua"/><path class="q0awsf50k"/><path clip-rule="evenodd" class="btwd0w9_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-alert-two-tone" /></template>
<style>
.btwd0w9_q {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 9C20 9.5523 19.5523 10 19 10C18.4477 10 18 9.5523 18 9C18 8.4477 18.4477 8 19 8C19.5523 8 20 8.4477 20 9Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q0awsf50k {
  d: path("M11 13H13C16.3137 13 19 15.6863 19 19V20C19 20.5523 18.5523 21 18 21H6C5.44772 21 5 20.5523 5 20V19C5 15.6863 7.68629 13 11 13ZM12 3C13.6569 3 15 4.34315 15 6C15 7.65685 13.6569 9 12 9C10.3431 9 9 7.65685 9 6C9 4.34315 10.3431 3 12 3ZM19 3L19 5");
}

.zihhuqsua {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 12L13 12C16.866 12 20 15.134 20 19V20C20 21.1046 19.1046 22 18 22L6 22C4.8954 22 4 21.1046 4 20V19C4 15.134 7.134 12 11 12ZM16 6C16 8.2091 14.2091 10 12 10C9.7909 10 8 8.2091 8 6C8 3.7909 9.7909 2 12 2C14.2091 2 16 3.7909 16 6Z");
  stroke: none;
}

</style>
