<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pfp_v5kne"/><path class="ow6-kpbfs"/><path class="qcydym7-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:streets-bold-duotone" /></template>
<style>
.ow6-kpbfs {
  fill: currentColor;
  d: path("M11.9995 13.0607L4.04785 21.0123C5.54419 22 7.86553 22 11.9995 22C16.1335 22 18.4549 22 19.9512 21.0123L11.9995 13.0607Z");
}

.pfp_v5kne {
  fill: currentColor;
  d: path("M21.0119 4.04834L13.0602 12L21.0119 19.9517C21.9995 18.4554 21.9995 16.134 21.9995 12C21.9995 7.86602 21.9995 5.54468 21.0119 4.04834Z");
}

.qcydym7-o {
  fill: currentColor;
  d: path("M3.46447 3.46447C2 4.92893 2 7.28596 2 12C2 16.134 2 18.4553 2.98767 19.9517L19.9517 2.98766C18.4553 2 16.134 2 12 2C7.28595 2 4.92893 2 3.46447 3.46447Z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
