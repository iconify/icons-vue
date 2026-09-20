<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gg7p-xn8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sentiment-excited" /></template>
<style>
.gg7p-xn8f {
  fill: currentColor;
  d: path("M8.308 12.308V14q0 1.535 1.079 2.614T12 17.692t2.614-1.078q1.078-1.08 1.078-2.614v-1.692zm3.692 4.5q-1.165 0-1.986-.822q-.822-.82-.822-1.986v-.808h5.616V14q0 1.166-.822 1.987q-.82.82-1.986.82M7.091 7.852q-.632.543-.932 1.493l.854.216q.208-.612.606-.98t.881-.388q.483.02.88.388t.606.98l.854-.216q-.3-.95-.931-1.493T8.5 7.308t-1.409.543m7 0q-.632.543-.932 1.493l.854.216q.208-.631.596-1q.389-.368.891-.368t.89.368t.596 1l.854-.216q-.3-.95-.931-1.493T15.5 7.308t-1.409.543M8.494 20.29q-1.642-.711-2.858-1.926q-1.215-1.216-1.926-2.858T3 12t.71-3.506q.711-1.642 1.927-2.857Q6.852 4.42 8.494 3.71T12 3t3.506.71q1.642.711 2.857 1.927q1.216 1.215 1.926 2.857Q21 10.137 21 12t-.71 3.506q-.711 1.642-1.926 2.857q-1.216 1.216-2.858 1.926Q13.864 21 12 21t-3.506-.71");
}

</style>
