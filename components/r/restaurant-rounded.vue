<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_9ymhaus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:restaurant-rounded" /></template>
<style>
.f_9ymhaus {
  fill: currentColor;
  d: path("M7.5 9.23V3q0-.213.144-.356t.357-.144t.356.144T8.5 3v6.23h1.77V3q0-.213.143-.356q.144-.144.357-.144t.356.144t.143.356v6.23q0 1.286-.805 2.172T8.5 12.466V21q0 .213-.144.356t-.357.144t-.356-.144T7.5 21v-8.534q-1.16-.177-1.965-1.064q-.804-.886-.804-2.171V3q0-.213.144-.356t.357-.144t.356.144T5.73 3v6.23zm9.23 4.27h-1.65q-.351 0-.581-.232t-.23-.576V7q0-2.02.893-3.26q.894-1.24 1.769-1.24q.392 0 .596.254t.204.69V21q0 .213-.144.356q-.144.144-.357.144t-.356-.144t-.143-.356z");
}

</style>
