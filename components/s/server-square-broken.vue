<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="fg2liobao"/><path class="d0ygbxurg"/><path class="k8xp4x4he"/><path class="irzxfpvcc"/><path class="gdeocxngl"/><path class="uc4n94bsq"/><path class="dwp-m7jgx"/><path class="ikcp8fb2i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:server-square-broken" /></template>
<style>
.d0ygbxurg {
  d: path("M2 12H14M22 12H18");
}

.dwp-m7jgx {
  d: path("M9 17.5L9 15.5");
}

.fg2liobao {
  d: path("M14 3C17.7712 3 19.6569 3 20.8284 4.17157C22 5.34315 22 7.22876 22 11V13C22 16.7712 22 18.6569 20.8284 19.8284C19.6569 21 17.7712 21 14 21H10C6.22876 21 4.34315 21 3.17157 19.8284C2 18.6569 2 16.7712 2 13V11C2 7.22876 2 5.34315 3.17157 4.17157C4.34315 3 6.22876 3 10 3");
}

.gdeocxngl {
  d: path("M6 17.5L6 15.5");
}

.ikcp8fb2i {
  d: path("M9 8.5L9 6.5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.irzxfpvcc {
  d: path("M13.5 7.5L18 7.5");
}

.k8xp4x4he {
  d: path("M13.5 16.5H18");
}

.uc4n94bsq {
  d: path("M6 8.5L6 6.5");
}

</style>
