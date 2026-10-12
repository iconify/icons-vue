<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjnbawuub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trekking-poles" /></template>
<style>
.kjnbawuub {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6 5.75c-1.75-.75-2.5-3-.75-3s1.5 1.75.75 3m12 0c1.75-.75 2.5-3 .75-3s-1.5 1.75-.75 3M7.77 6.76l.56 2.01q.33 1.16-.83 1.48l-.56.16q-1.16.32-1.49-.84l-.56-2.01q-.33-1.16.83-1.48l.56-.16q1.16-.32 1.49.84m9.95-.84l.56.16q1.16.32.83 1.48l-.56 2.01q-.33 1.16-1.49.84l-.56-.16q-1.16-.32-.83-1.48l.56-2.01q.33-1.16 1.49-.84m-10.5 4.41L10 20.25m6.78-9.92L14 20.25m-11.25 0h18.5");
}

</style>
