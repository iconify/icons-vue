<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0fdbib3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:wifi-calling-bar-2-sharp" /></template>
<style>
.z0fdbib3a {
  fill: currentColor;
  d: path("M15.788 10.713Q15.5 10.425 15.5 10t.288-.712T16.5 9t.713.288t.287.712t-.288.713T16.5 11t-.712-.288M14 8.55L12.95 7.5q.725-.725 1.638-1.112T16.5 6t1.913.388T20.05 7.5L19 8.55q-.5-.5-1.137-.775T16.5 7.5t-1.362.275T14 8.55M19.95 21q-3.125 0-6.187-1.35T8.2 15.8t-3.85-5.55T3 4.05V3h5.9l.925 5.025l-2.85 2.875q.55.975 1.225 1.85t1.45 1.625q.725.725 1.588 1.388T13.1 17l2.9-2.9l5 1.025V21z");
}

</style>
