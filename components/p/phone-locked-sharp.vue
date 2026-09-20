<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqqxkabmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:phone-locked-sharp" /></template>
<style>
.eqqxkabmo {
  fill: currentColor;
  d: path("M15 10V5h1V4q0-.825.588-1.412T18 2t1.413.588T20 4v1h1v5zm2-5h2V4q0-.425-.288-.712T18 3t-.712.288T17 4zm2.95 16q-3.125 0-6.187-1.35T8.2 15.8t-3.85-5.55T3 4.05V3h5.9l.925 5.025l-2.85 2.875q.55.975 1.225 1.85t1.45 1.625q.725.725 1.588 1.388T13.1 17l2.9-2.9l5 1.025V21z");
}

</style>
