<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ysm4joo5m"/><path class="ny532p57y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ruppu" /></template>
<style>
.ny532p57y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.696 34.536a3.69 3.69 0 0 1-3.199-1.845l-7.905-13.693a3.69 3.69 0 0 1 6.39-3.689l7.906 13.693a3.69 3.69 0 0 1-3.192 5.534m8.52 0a3.69 3.69 0 0 1-3.198-1.845l-7.906-13.693a3.69 3.69 0 0 1 6.39-3.689l7.906 13.693a3.69 3.69 0 0 1-3.192 5.534");
}

.ysm4joo5m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.388 20.31h9.423c2.034 0 3.689 1.656 3.689 3.69s-1.655 3.69-3.69 3.69h-5.164m-21.292-7.38H8.19c-2.035 0-3.69 1.657-3.69 3.69s1.655 3.69 3.69 3.69h9.422");
}

</style>
