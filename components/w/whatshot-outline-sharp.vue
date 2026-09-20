<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vjml1-b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:whatshot-outline-sharp" /></template>
<style>
.vjml1-b2x {
  fill: currentColor;
  d: path("M12 21q-1.362 0-2.707-.445t-2.562-1.286l.719-.719q1.05.725 2.2 1.088T12 20q3.344 0 5.672-2.328T20 12t-2.328-5.672T12 4T6.328 6.328T4 12H3q0-1.864.71-3.506q.711-1.642 1.927-2.857Q6.852 4.42 8.494 3.71T12 3t3.503.71t2.858 1.93t1.929 2.857q.71 1.64.71 3.5t-.71 3.503q-.711 1.642-1.93 2.86t-2.857 1.93T12 21m-7.583-4.19l3.595-3.614l3 2.5l5.315-5.315v3.33h1V8.673h-5.039v1h3.293l-4.592 4.63l-3-2.5l-4.102 4.084q.14.267.247.456t.283.467M12 12");
}

</style>
