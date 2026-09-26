<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="ujttvybtu"/><path class="qxb6e3bet"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:server-zap-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qxb6e3bet {
  d: path("M20 16L17 19L21 19L18 22");
}

.ujttvybtu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 1L17 1C18.6569 1 20 2.3431 20 4L20 8C20 9.6569 18.6569 11 17 11L5 11C3.3431 11 2 9.6569 2 8L2 4C2 2.3431 3.3431 1 5 1ZM5 13L13 13C13.5523 13 14 13.4477 14 14L14 22C14 22.5523 13.5523 23 13 23L5 23C3.3431 23 2 21.6569 2 20L2 16C2 14.3431 3.3431 13 5 13ZM8 6C8 5.4477 7.5523 5 7 5C6.4477 5 6 5.4477 6 6C6 6.5523 6.4477 7 7 7C7.5523 7 8 6.5523 8 6ZM12 6C12 5.4477 11.5523 5 11 5C10.4477 5 10 5.4477 10 6C10 6.5523 10.4477 7 11 7C11.5523 7 12 6.5523 12 6ZM8 18C8 17.4477 7.5523 17 7 17C6.4477 17 6 17.4477 6 18C6 18.5523 6.4477 19 7 19C7.5523 19 8 18.5523 8 18ZM12 18C12 17.4477 11.5523 17 11 17C10.4477 17 10 17.4477 10 18C10 18.5523 10.4477 19 11 19C11.5523 19 12 18.5523 12 18Z");
  stroke: none;
}

</style>
