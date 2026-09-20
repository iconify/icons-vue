<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7tjhqv5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:sports-baseball-outline-rounded" /></template>
<style>
.c7tjhqv5w {
  fill: currentColor;
  d: path("M5.908 17.223q1.24-.913 1.916-2.298T8.5 12t-.676-2.925t-1.916-2.298q-.93 1.107-1.419 2.438T4 12t.49 2.785t1.418 2.438m8.956 2.253q1.374-.524 2.482-1.534q-1.348-1.111-2.097-2.653Q14.5 13.748 14.5 12t.749-3.29q.749-1.54 2.097-2.652q-1.107-1.01-2.481-1.534T12 4t-2.864.524t-2.482 1.534Q8.002 7.169 8.75 8.71q.75 1.542.75 3.29t-.749 3.29q-.749 1.54-2.097 2.652q1.107 1.01 2.481 1.534T12 20t2.865-.524m3.227-2.253q.93-1.107 1.419-2.439Q20 13.454 20 12t-.49-2.784t-1.418-2.439q-1.24.914-1.916 2.298T15.5 12t.676 2.925t1.916 2.298M8.494 20.29q-1.642-.711-2.858-1.926q-1.215-1.216-1.926-2.858T3 12t.71-3.506q.711-1.642 1.927-2.857Q6.852 4.42 8.494 3.71T12 3t3.506.71q1.642.711 2.857 1.927q1.216 1.215 1.926 2.857Q21 10.137 21 12t-.71 3.506q-.711 1.642-1.926 2.857q-1.216 1.216-2.858 1.926Q13.864 21 12 21t-3.506-.71");
}

</style>
