<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="c6lafhbvk"/><path class="w6ca74b2j"/><path class="smls78shz"/><path class="nau4w8dar"/><path class="n787bfb7v"/><path class="f89c2ypeq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:radio-broken" /></template>
<style>
.c6lafhbvk {
  d: path("M12 9H17C18.1046 9 19 9.89543 19 11C19 12.1046 18.1046 13 17 13H7C5.89543 13 5 12.1046 5 11C5 9.89543 5.89543 9 7 9H8");
}

.f89c2ypeq {
  d: path("M22 14V14C22 17.7712 22 19.6569 20.8284 20.8284C19.6569 22 17.7712 22 14 22H10C6.22876 22 4.34315 22 3.17157 20.8284C2 19.6569 2 17.7712 2 14C2 10.2288 2 8.34315 3.17157 7.17157C4.34315 6 6.22876 6 10 6H14C17.7712 6 19.6569 6 20.8284 7.17157C21.4816 7.82475 21.7706 8.69989 21.8985 10");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n787bfb7v {
  d: path("M6.5 6L15 2");
}

.nau4w8dar {
  d: path("M13 17H18");
}

.smls78shz {
  d: path("M15 11.5V13");
}

.w6ca74b2j {
  d: path("M9 17C9 17.8284 8.32843 18.5 7.5 18.5C6.67157 18.5 6 17.8284 6 17C6 16.1716 6.67157 15.5 7.5 15.5C8.32843 15.5 9 16.1716 9 17Z");
}

</style>
