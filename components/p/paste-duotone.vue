<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="z4gzximgz"/><path clip-rule="evenodd" class="m6sezjejw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:paste-duotone" /></template>
<style>
.m6sezjejw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 10C18.2652 10 18.5196 10.1054 18.7071 10.2929L22.7071 14.2929C22.8946 14.4804 23 14.7348 23 15L23 20C23 21.6569 21.6569 23 20 23L14 23C12.3431 23 11 21.6569 11 20L11 13C11 11.3431 12.3431 10 14 10L18 10ZM20.5858 15L18 12.4142L18 13C18 14.1046 18.8954 15 20 15L20.5858 15Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.z4gzximgz {
  stroke-opacity: 0.4;
  d: path("M5 4C3.3431 4 2 5.3431 2 7L2 18C2 19.6569 3.3431 21 5 21L8 21M13 4C14.6569 4 16 5.3431 16 7M5 4C5 2.8954 5.8954 2 7 2L11 2C12.1046 2 13 2.8954 13 4L13 5C13 6.1046 12.1046 7 11 7L7 7C5.8954 7 5 6.1046 5 5L5 4Z");
}

</style>
