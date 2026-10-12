<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pxyop0bkq"/><path class="abo3rrb5l"/><path class="x_ptlgq7r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pet-carrier" /></template>
<style>
.abo3rrb5l {
  d: path("M2.75 19.5v-7c0-4 4.25-6.25 9.25-6.25s9.25 2.25 9.25 6.25v7A1.25 1.25 0 0 1 20 20.75H4a1.25 1.25 0 0 1-1.25-1.25");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pxyop0bkq {
  d: path("M10 6.4V5a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v1.4");
}

.x_ptlgq7r {
  d: path("M5.75 17.75V14a3.75 3.75 0 0 1 7.5 0v3.75Zm2.5-7.25v7.25m2.5-7.25v7.25m5.5-5.25h2m-2 3h2");
}

</style>
