<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="a5aa8opar"/><path class="t_aznob1v"/><path class="y94091a_r"/><path class="i4zzprb-l"/><path class="uxgpkm7fp"/><path class="unnk4bcsi"/><path class="rxt3g_bgx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:shock-absorber-line-duotone" /></template>
<style>
.a5aa8opar {
  d: path("M14 15V6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.i4zzprb-l {
  d: path("M8 6H16C16.9428 6 17.4142 6 17.7071 5.70711C18 5.41421 18 4.94281 18 4C18 3.05719 18 2.58579 17.7071 2.29289C17.4142 2 16.9428 2 16 2H8C7.05719 2 6.58579 2 6.29289 2.29289C6 2.58579 6 3.05719 6 4C6 4.94281 6 5.41421 6.29289 5.70711C6.58579 6 7.05719 6 8 6Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rxt3g_bgx {
  d: path("M20 11.4995L22 11.4995M4 11.5004H2M19.0713 14.3L19.7784 14.9999M4.92871 14.3L4.2216 14.9999M19.0713 8.6999L19.7784 7.99994M4.92871 8.6999L4.2216 7.99994");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.t_aznob1v {
  d: path("M10 15V6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.unnk4bcsi {
  d: path("M8 8.00003L16 10M8 11.5L16 13.5");
}

.uxgpkm7fp {
  d: path("M10 18H14C14.8284 18 15.5 17.3284 15.5 16.5C15.5 15.6716 14.8284 15 14 15H10C9.17157 15 8.5 15.6716 8.5 16.5C8.5 17.3284 9.17157 18 10 18Z");
}

.y94091a_r {
  d: path("M14 20C14 21.1046 13.1046 22 12 22C10.8954 22 10 21.1046 10 20C10 18.8954 10.8954 18 12 18C13.1046 18 14 18.8954 14 20Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
