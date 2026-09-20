<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ijahkv6mo"/><circle class="scrdwlw5p"/><circle class="p4tdmogie"/><path class="t3-aekbwm"/><path class="wytuf1bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:obb-scotty" /></template>
<style>
.ijahkv6mo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.933 32.077h2.541v2.371h-2.541zm14.026 0H43.5v2.371h-2.541zm-5.742-18.525c-2.953 0-8.284.459-8.284 1.66v16.865H43.5V15.211c0-1.2-5.37-1.659-8.283-1.659m.012 2.778a22.4 22.4 0 0 1 6.087.61a.48.48 0 0 1 .333.463v8.493a.487.487 0 0 1-.487.486H29.296a.487.487 0 0 1-.486-.486v-8.493a.48.48 0 0 1 .332-.462a22.4 22.4 0 0 1 6.087-.611m-5.207 11.363a1.248 1.248 0 0 1 0 2.496a1.23 1.23 0 0 1-1.212-1.248a1.23 1.23 0 0 1 1.212-1.248m10.415 0a1.248 1.248 0 0 1 0 2.496a1.23 1.23 0 0 1-1.212-1.248a1.23 1.23 0 0 1 1.212-1.248");
}

.p4tdmogie {
  cx: 18.332px;
  cy: 27.187px;
  r: 1.324px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.scrdwlw5p {
  cx: 9.144px;
  cy: 27.187px;
  r: 1.324px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.t3-aekbwm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.617 16.433v12.119a2.887 2.887 0 0 0 2.88 2.88H18.98a2.887 2.887 0 0 0 2.88-2.88v-12.12a2.887 2.887 0 0 0-2.88-2.88H8.498a2.887 2.887 0 0 0-2.88 2.88m2.88 15.028L4.5 34.448m14.479-2.988l3.997 2.988");
}

.wytuf1bju {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.776 16.248H19.7v6.276H7.776z");
}

</style>
