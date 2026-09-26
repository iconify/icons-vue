<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="rqna20z_n"/><path class="xexl16bfr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:search-x-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rqna20z_n {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 10C18 14.4183 14.4183 18 10 18C5.5817 18 2 14.4183 2 10C2 5.5817 5.5817 2 10 2C14.4183 2 18 5.5817 18 10ZM11.4142 10L12.8284 11.4142C13.016 11.6017 13.1213 11.8561 13.1213 12.1213C13.1213 12.6736 12.6736 13.1213 12.1213 13.1213C11.8561 13.1213 11.6017 13.016 11.4142 12.8284L10 11.4142L8.5858 12.8284C8.3983 13.016 8.1439 13.1213 7.8787 13.1213C7.3264 13.1213 6.8787 12.6736 6.8787 12.1213C6.8787 11.8561 6.984 11.6017 7.1716 11.4142L8.5858 10L7.1716 8.5858C6.984 8.3983 6.8787 8.1439 6.8787 7.8787C6.8787 7.3264 7.3264 6.8787 7.8787 6.8787C8.1439 6.8787 8.3983 6.984 8.5858 7.1716L10 8.5858L11.4142 7.1716C11.6017 6.984 11.8561 6.8787 12.1213 6.8787C12.6736 6.8787 13.1213 7.3264 13.1213 7.8787C13.1213 8.1439 13.016 8.3983 12.8284 8.5858L11.4142 10Z");
  stroke: none;
}

.xexl16bfr {
  d: path("M15 15L21 21");
}

</style>
