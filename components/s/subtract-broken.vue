<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="w8dddui9c"/><path class="d7kc_0c3u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:subtract-broken" /></template>
<style>
.d7kc_0c3u {
  d: path("M16 15C16.4354 15 16.8373 15 17.2089 14.997M16 15H14M16 15H17M9.2772 3.913C9.4072 3.494 9.5982 3.159 9.8787 2.879C10.1592 2.598 10.4943 2.407 10.9126 2.277M20.0874 2.277C20.5057 2.407 20.8408 2.598 21.1213 2.879C21.4018 3.159 21.5928 3.494 21.7228 3.913M21.7228 13.087C21.5928 13.506 21.4018 13.841 21.1213 14.121C20.8408 14.402 20.5057 14.593 20.0874 14.723M14 2H17M22 7V10M9.0032 6.791L9 10");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w8dddui9c {
  stroke-linejoin: round;
  d: path("M2.01733 13C2.06413 11.4466 2.23743 10.52 2.87873 9.8787C3.75743 9 5.17163 9 8.00003 9H9.00003C9.00003 11.8284 9.00003 13.2426 9.87873 14.1213C10.7574 15 12.1716 15 15 15V16C15 18.8284 15 20.2426 14.1213 21.1213C13.2427 22 11.8284 22 9.00003 22H8.00003C5.17163 22 3.75743 22 2.87873 21.1213C2.23743 20.48 2.06413 19.5534 2.01733 18");
}

</style>
