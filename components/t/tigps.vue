<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o8fchtbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tigps" /></template>
<style>
.o8fchtbie {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.242 4.094a34.48 34.48 0 0 1-16.366 14.293h4.92c.898 6.414-9.895 17.887 8.685 16.61l-2.008 8.458l7.42.451l5.232-21.99l-7.43-.451s-1.627 8.375-2.16 8.987c-1.468 1.686-4.327.04-3.664-3.59l2-8.475l4.54.066l.942-3.97l-4.53-.133Z");
}

</style>
