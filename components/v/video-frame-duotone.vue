<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uy8f95uof"/><path clip-rule="evenodd" class="m81w5cbqn"/><path class="tdk3h3bel"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:video-frame-duotone" /></template>
<style>
.m81w5cbqn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.6774 8.069L15.3322 9.728C15.8015 10.021 16.0372 10.517 16.0372 11C16.0372 11.483 15.8015 11.979 15.3322 12.272L10.0226 15.59C9.3575 16.006 8.585 15.972 7.9931 15.644C7.4012 15.316 6.9626 14.679 6.9626 13.894V8.105C6.9626 7.321 7.4012 6.684 7.9931 6.356C8.585 6.028 9.3575 5.994 10.0226 6.409L12.6774 8.069Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tdk3h3bel {
  d: path("M18 15V21M21 18L18 21L15 18");
}

.uy8f95uof {
  stroke-opacity: 0.4;
  d: path("M3 8V6C3 4.343 4.3432 3 6 3H8M16 3H18C19.6569 3 21 4.343 21 6V8M8 21H6C4.3432 21 3 19.657 3 18V16");
}

</style>
