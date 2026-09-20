<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ashr88bcx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:wifi-calling-bar-1-sharp" /></template>
<style>
.ashr88bcx {
  fill: currentColor;
  d: path("M19.95 21q-3.125 0-6.187-1.35T8.2 15.8t-3.85-5.55T3 4.05V3h5.9l.925 5.025l-2.85 2.875q.55.975 1.225 1.85t1.45 1.625q.725.725 1.588 1.388T13.1 17l2.9-2.9l5 1.025V21zm-4.162-10.287Q15.5 10.425 15.5 10t.288-.712T16.5 9t.713.288t.287.712t-.288.713T16.5 11t-.712-.288");
}

</style>
