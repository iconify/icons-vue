<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="plpeinwhx"/><path class="p1ao_2b3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:portu" /></template>
<style>
.p1ao_2b3h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.984 28.956L6.396 33.34l17.932 10.415l17.93-10.415l-8.068-4.638");
}

.plpeinwhx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24.005 34.189l18.495-10.5l-.03-8.436l-18.409 10.558zm-.01 0L5.5 23.689l.03-8.436l18.409 10.558zM5.526 15.232L24.117 4.244l18.304 10.935");
}

</style>
