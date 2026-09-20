<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k9ca-tbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:nest-wifi-mistral-outline" /></template>
<style>
.k9ca-tbul {
  fill: currentColor;
  d: path("M9 21q-2.5 0-4.25-1.75T3 15V9q0-2.5 1.75-4.25T9 3h6q2.5 0 4.25 1.75T21 9v6q0 2.5-1.75 4.25T15 21zm-4-6h14V9q0-1.65-1.175-2.825T15 5H9Q7.35 5 6.175 6.175T5 9zm.55 2q.525.9 1.425 1.45T9 19h6q1.125 0 2.025-.55T18.45 17zM12 15");
}

</style>
