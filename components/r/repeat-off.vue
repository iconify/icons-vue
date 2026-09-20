<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ad5lrzy_r"/><path clip-rule="evenodd" class="z9advho8m"/><path clip-rule="evenodd" class="q4m834cow"/><path clip-rule="evenodd" class="r9gopibsy"/><path clip-rule="evenodd" class="ewrdgqbno"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:repeat-off" /></template>
<style>
.ad5lrzy_r {
  fill-rule: evenodd;
  d: path("M14.519 2.749a.75.75 0 0 1 1.052.13l1.547 1.982a.75.75 0 1 1-1.183.923L14.39 3.8a.75.75 0 0 1 .13-1.052");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ewrdgqbno {
  fill-rule: evenodd;
  d: path("M17.527 10.677a5 5 0 0 1-5 5H4.666a1 1 0 1 1 0-2h7.86a3 3 0 0 0 3-3v-1a1 1 0 1 1 2 0z");
}

.q4m834cow {
  fill-rule: evenodd;
  d: path("M2.48 9.323a5 5 0 0 1 5-5h7.86a1 1 0 1 1 0 2H7.48a3 3 0 0 0-3 3v1a1 1 0 1 1-2 0zm3.008 7.928a.75.75 0 0 1-1.053-.13L2.89 15.14a.75.75 0 1 1 1.182-.923L5.619 16.2a.75.75 0 0 1-.13 1.052");
}

.r9gopibsy {
  fill-rule: evenodd;
  d: path("M3.024 15.273a.75.75 0 0 0 1.051-.14l1.547-2.017a.75.75 0 0 0-1.19-.912L2.884 14.22a.75.75 0 0 0 .139 1.052");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

.z9advho8m {
  fill-rule: evenodd;
  d: path("M16.983 4.727a.75.75 0 0 0-1.052.14l-1.546 2.017a.75.75 0 1 0 1.19.912l1.547-2.017a.75.75 0 0 0-.14-1.052");
}

</style>
