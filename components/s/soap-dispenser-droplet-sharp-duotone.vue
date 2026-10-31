<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="khdgct0uo"/><path clip-rule="evenodd" class="om376ac_x"/><path class="a6_d06b7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:soap-dispenser-droplet-sharp-duotone" /></template>
<style>
.a6_d06b7r {
  d: path("M10 2L10 7M6 2L11.1716 2C12.9826 2 14.7194 2.7194 16 4L16.7071 4.7071");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.khdgct0uo {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.1674 23L4 23C3.4477 23 3 22.5523 3 22L3 11C3 10.4477 3.4477 10 4 10L16 10C16.2846 9.9997 16.5558 10.121 16.7453 10.3333C15.8027 10.3348 14.9156 10.7792 14.35 11.5333L11.75 15C10.9386 16.0818 10.4999 17.3977 10.4999 18.75C10.4999 20.3263 11.0955 21.8443 12.1674 23Z");
  stroke: none;
}

.om376ac_x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 11L6 7C6 6.4477 6.4477 6 7 6L13 6C13.5523 6 14 6.4477 14 7L14 11C14 11.5523 13.5523 12 13 12L7 12C6.4477 12 6 11.5523 6 11ZM20.15 16.2C20.7018 16.9357 21 17.8304 21 18.75C21 21.0972 19.0972 23 16.75 23C14.4028 23 12.5 21.0972 12.5 18.75C12.5 17.8304 12.7983 16.9357 13.35 16.2L15.95 12.7333C16.1389 12.4815 16.4352 12.3333 16.75 12.3333C17.0648 12.3333 17.3611 12.4815 17.55 12.7333L20.15 16.2Z");
  stroke: none;
}

</style>
