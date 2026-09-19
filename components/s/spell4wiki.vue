<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q8xmzyadi"/><path class="n80zzewcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:spell4wiki" /></template>
<style>
.n80zzewcz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.606 37.109a4.483 4.483 0 0 0 8.789 0");
}

.q8xmzyadi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.817 5.25l8.24 21.972L27.295 5.25m-6.592 0l8.24 21.972l8.24-21.972m-29.662 0h6.592m4.394 0h4.394m10.986 0h6.592m-15.38 0h4.394M24 29.968a2.754 2.754 0 0 1 2.747 2.747v3.296a2.747 2.747 0 0 1-5.493 0v-3.296A2.754 2.754 0 0 1 24 29.968m1.099 10.766v3.516H22.9v-3.516");
}

</style>
