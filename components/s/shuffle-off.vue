<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="cp0ig_xbt"/><path clip-rule="evenodd" class="l9peisbld"/><path clip-rule="evenodd" class="l000dmdex"/><path clip-rule="evenodd" class="eas572bou"/><path clip-rule="evenodd" class="pe9xcjijx"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:shuffle-off" /></template>
<style>
.cp0ig_xbt {
  fill-rule: evenodd;
  d: path("M3 5.75a1 1 0 0 1 1-1c3.335 0 6.5 2.126 6.5 5.25S7.335 15.25 4 15.25a1 1 0 1 1 0-2c2.74 0 4.5-1.68 4.5-3.25S6.74 6.75 4 6.75a1 1 0 0 1-1-1");
}

.cuyn6tgcc {
  fill: currentColor;
}

.eas572bou {
  fill-rule: evenodd;
  d: path("M14.05 16.786a.75.75 0 0 1-.15-1.05l1.5-2a.75.75 0 1 1 1.2.9l-1.5 2a.75.75 0 0 1-1.05.15m2.41-11.564a.75.75 0 0 0-1.053.133l-1.5 1.936a.75.75 0 0 0 1.186.918l1.5-1.935a.75.75 0 0 0-.134-1.052");
}

.l000dmdex {
  fill-rule: evenodd;
  d: path("M16.46 14.778a.75.75 0 0 1-1.053-.133l-1.5-1.936a.75.75 0 0 1 1.186-.918l1.5 1.935a.75.75 0 0 1-.134 1.052");
}

.l9peisbld {
  fill-rule: evenodd;
  d: path("M16 5.75a1 1 0 0 0-1-1c-3.335 0-6.5 2.126-6.5 5.25s3.165 5.25 6.5 5.25a1 1 0 1 0 0-2c-2.74 0-4.5-1.68-4.5-3.25s1.76-3.25 4.5-3.25a1 1 0 0 0 1-1");
}

.pe9xcjijx {
  fill-rule: evenodd;
  d: path("M14.05 3.15a.75.75 0 0 0-.15 1.05l1.5 2a.75.75 0 1 0 1.2-.9l-1.5-2a.75.75 0 0 0-1.05-.15");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
