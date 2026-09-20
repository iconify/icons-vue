<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="ahdx6dw6n"/><path class="dg0ux6bsc"/><path class="e-687bsnr"/></g><path class="vvsjhf_vz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:thpcod" /></template>
<style>
.ahdx6dw6n {
  d: path("m41.28 23.234l1.785 5.992a3.137 3.137 0 0 1-2.105 3.911l-26.415 7.917a3.126 3.126 0 0 1-3.9-2.111L4.631 18.775a3.137 3.137 0 0 1 2.105-3.912l26.415-7.916a3.126 3.126 0 0 1 3.9 2.11l1.787 5.992");
}

.dg0ux6bsc {
  d: path("m34.166 16.448l6.255-1.875a.893.893 0 0 1 1.114.604l1.928 6.467a.896.896 0 0 1-.601 1.118l-6.255 1.874");
}

.e-687bsnr {
  d: path("M36.588 20.182c1.246 4.181-1.124 8.584-5.294 9.834s-8.561-1.127-9.808-5.308s1.124-8.584 5.294-9.834s8.561 1.127 9.808 5.308");
}

.vvsjhf_vz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.955 22.355c1.161-.033 2.13.92 2.165 2.128s-.879 2.215-2.04 2.248l-3.47.1l-.25-8.752l3.47-.1c1.161-.033 2.13.92 2.165 2.128s-.879 2.215-2.04 2.248m-1.911-5.771l.333 11.654m1.676-11.726l.333 11.654m-.431-5.811l-3.47.1");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
