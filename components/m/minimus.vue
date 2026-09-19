<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sat3ipbyn"/><path class="o17d2hbgv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:minimus" /></template>
<style>
.o17d2hbgv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.25 10.147a4.5 4.5 0 0 1 2.25 3.896v19.914a4.5 4.5 0 0 1-6.75 3.897l-17.246-9.957a4.5 4.5 0 0 1 0-7.793l17.246-9.957a4.5 4.5 0 0 1 4.5 0");
}

.sat3ipbyn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 17.508l-12.75-7.361a4.5 4.5 0 0 0-4.5 0h0a4.5 4.5 0 0 0-2.25 3.896v19.914a4.5 4.5 0 0 0 6.75 3.896L24 30.493");
}

</style>
