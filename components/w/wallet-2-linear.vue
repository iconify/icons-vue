<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="nomdrxbld"/><path class="z8j9m1bjy"/><path class="zz8f-y99b"/><path class="t2jvb6bpe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:wallet-2-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nomdrxbld {
  stroke-linejoin: round;
  d: path("M7 15L7 9");
}

.t2jvb6bpe {
  stroke-linejoin: round;
  d: path("M17.9912 12H18.0002");
}

.z8j9m1bjy {
  d: path("M18.2308 9H20.8333C20.9167 9 20.9583 9 20.9935 9.00214C21.5328 9.03496 21.9623 9.43384 21.9977 9.9346C22 9.96726 22 10.006 22 10.0833V13.9167C22 13.994 22 14.0327 21.9977 14.0654C21.9623 14.5662 21.5328 14.965 20.9935 14.9979C20.9583 15 20.9167 15 20.8333 15H18.2308C16.4465 15 15 13.6569 15 12C15 10.3431 16.4465 9 18.2308 9Z");
}

.zz8f-y99b {
  d: path("M20.965 9C20.8873 7.1277 20.6366 5.97975 19.8284 5.17157C18.6569 4 16.7712 4 13 4H10C6.22876 4 4.34315 4 3.17157 5.17157C2 6.34315 2 8.22876 2 12C2 15.7712 2 17.6569 3.17157 18.8284C4.34315 20 6.22876 20 10 20H13C16.7712 20 18.6569 20 19.8284 18.8284C20.6366 18.0203 20.8873 16.8723 20.965 15");
}

</style>
