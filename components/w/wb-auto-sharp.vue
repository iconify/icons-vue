<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="abzzm0ivv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wb-auto-sharp" /></template>
<style>
.abzzm0ivv {
  fill: currentColor;
  d: path("M5.364 15h.853l.727-1.992h2.8L10.471 15h.893L8.687 8H8.04zm1.853-2.684L8.294 9.3h.1l1.077 3.016zM8.344 18q-2.502 0-4.25-1.749T2.343 12t1.75-4.251T8.343 6q1.972 0 3.53 1.156q1.559 1.156 2.124 3.025L13.437 8h.892l1.277 5.485h.05L17.106 8h.83l1.45 5.485h.062L20.725 8h.93l-1.772 7h-.842l-1.5-5.634h-.05L16.002 15h-.804l-.97-3.977q.5 2.74-1.29 4.859T8.345 18");
}

</style>
