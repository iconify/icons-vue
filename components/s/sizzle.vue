<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g_5v9tb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sizzle" /></template>
<style>
.g_5v9tb0k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.73 20.216c4.886-2.917 2.679-15.478-7.797-14.68c-1.155.089-2.064 1.271-2.608 2.292l-9.911 18.626c-1.576 2.963 1.996 4.699 3.763 3.644zm-3.896 22.211c5.695-.021 10.223-11.947.806-16.592c-1.039-.513-2.426.042-3.415.643L11.17 37.45c-2.871 1.745-.687 5.057 1.372 5.049z");
}

</style>
