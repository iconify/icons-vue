<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wiq-y9bxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:save-clock-sharp" /></template>
<style>
.wiq-y9bxv {
  fill: currentColor;
  d: path("M15.549 19.836Q14.385 18.67 14.385 17t1.164-2.835T18.384 13q1.672 0 2.836 1.165q1.165 1.164 1.165 2.835t-1.165 2.836T18.385 21t-2.836-1.164m4.492-.634l.546-.546l-1.818-1.818v-2.722H18v3.046zM6.769 9.769h7.423v-3H6.77zM4 20V4h12.577L20 7.423v3.444q-.412-.138-.84-.195q-.43-.056-.858-.056q-1.558 0-2.864.68t-2.161 1.835q-.225-.267-.559-.43T12 12.539q-.827 0-1.413.586T10 14.538q0 .77.517 1.333q.518.563 1.264.633h.125q.067 0 .125-.02q-.067.966.117 1.804q.185.839.627 1.712z");
}

</style>
