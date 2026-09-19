<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qy4iinbsy"/><path class="ltgnblbty"/><path class="zgefe1_jv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tremotesf" /></template>
<style>
.ltgnblbty {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.687 5.5h6.626v23.746h4.97L24 36.978l-8.284-7.732h4.97Z");
}

.qy4iinbsy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.687 7.709H9.09a2.485 2.485 0 0 0-2.209 2.209v4.97a2.485 2.485 0 0 0 2.209 2.209h11.597m6.626 0H38.91a2.485 2.485 0 0 0 2.209-2.209v-4.97A2.485 2.485 0 0 0 38.91 7.71H27.313");
}

.zgefe1_jv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.687 22.62h-9.94a2.485 2.485 0 0 0-2.21 2.208v15.463a2.485 2.485 0 0 0 2.21 2.209h26.507a2.485 2.485 0 0 0 2.209-2.209V24.828a2.485 2.485 0 0 0-2.21-2.209h-9.94");
}

</style>
