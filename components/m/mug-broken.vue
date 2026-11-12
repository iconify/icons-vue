<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="f_18xcbpp"/><path class="ab9oag7th"/><path class="n5gy6sdjs"/><path class="jlzv4qbob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:mug-broken" /></template>
<style>
.ab9oag7th {
  d: path("M16.9999 13H17.9999C20.2091 13 21.9999 11.2091 21.9999 9C21.9999 6.79086 20.2091 5 17.9999 5H16.9493");
}

.f_18xcbpp {
  d: path("M3 7C3 5.11438 3 4.17157 3.58579 3.58579C4.17157 3 5.11438 3 7 3H13C14.8856 3 15.8284 3 16.4142 3.58579C17 4.17157 17 5.11438 17 7V12C17 14.8284 17 16.2426 16.1213 17.1213C15.2426 18 13.8284 18 11 18H9C6.17157 18 4.75736 18 3.87868 17.1213C3 16.2426 3 14.8284 3 12V11");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jlzv4qbob {
  d: path("M22 21L2 21");
}

.n5gy6sdjs {
  d: path("M10.0002 13H3.00195M16.9985 13H14.0002");
}

</style>
