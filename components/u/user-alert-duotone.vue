<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sluw2pmtp"/><path class="qj8gmox4v"/><path clip-rule="evenodd" class="btwd0w9_q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-alert-duotone" /></template>
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

.qj8gmox4v {
  d: path("M19 3L19 5");
}

.sluw2pmtp {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 13L13 13C16.866 13 20 16.134 20 20C20 21.1046 19.1046 22 18 22L6 22C4.8954 22 4 21.1046 4 20C4 16.134 7.134 13 11 13ZM16 7C16 9.2091 14.2091 11 12 11C9.7909 11 8 9.2091 8 7C8 4.7909 9.7909 3 12 3C14.2091 3 16 4.7909 16 7Z");
  stroke: none;
}

</style>
