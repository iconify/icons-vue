<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hnvnn0bgl"/><path class="y395y153b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-shield" /></template>
<style>
.hnvnn0bgl {
  d: path("m12 2.75l7.5 2.75v6c0 4.7-3.1 8-7.5 9.75c-4.4-1.75-7.5-5.05-7.5-9.75v-6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y395y153b {
  d: path("M12 18.75c-1.5 0-2.5-.75-2.5-1.75s1.25-1.5 2.5-1.5s2.5.5 2.5 1.5s-1 1.75-2.5 1.75ZM8.75 14h.01m1.99-1.5h.01m2.49 0h.01m1.99 1.5h.01");
}

</style>
