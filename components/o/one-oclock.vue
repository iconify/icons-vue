<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="fcq8r33rh"/><g class="n1mjunbsu"><path class="k2w4k3b6j"/><path class="h1ttcibhe"/><circle class="xq6jaeb2t"/></g><circle class="uzm2mooko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:one-oclock" /></template>
<style>
.fcq8r33rh {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--62727a, #62727a);
}

.h1ttcibhe {
  d: path("M30.6 38L27 36.1L39.4 16l3.6 1.9z");
}

.k2w4k3b6j {
  d: path("M30 6h4v32h-4z");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.uzm2mooko {
  cx: 32px;
  cy: 32px;
  r: 3px;
  fill: var(--svg-color--62727a, #62727a);
}

.xq6jaeb2t {
  cx: 32px;
  cy: 32px;
  r: 4px;
}

</style>
