<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n7ecw9v1f"/><path class="sl8psrprs"/><path class="bwiuyxb4j"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mymetro" /></template>
<style>
.bwiuyxb4j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 22.227v5.653a4.184 4.184 0 0 1-4.185 4.18h0a4.17 4.17 0 0 1-2.96-1.224");
}

.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.n7ecw9v1f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.959 32.032a1.3 1.3 0 0 1-1.132.646h0a1.293 1.293 0 0 1-1.3-1.284h0v-.836c0-.71.583-1.285 1.3-1.285h0c.718 0 1.3.576 1.3 1.285v.418h-2.6m4.138-1.703h1.367m-.682-1.063v3.826c0 .355.288.642.647.642h.197m-10.093-2.12c0-.71.58-1.285 1.3-1.285h0c.714 0 1.297.576 1.297 1.285v2.12M9.5 29.273v3.405m0-2.12c0-.71.583-1.285 1.3-1.285h0c.718 0 1.301.576 1.301 1.285v2.12m11.839-3.405v3.405m0-2.12c0-.71.583-1.285 1.3-1.285h0m2.558 0c.722 0 1.3.572 1.3 1.285v.836c0 .709-.578 1.284-1.3 1.284s-1.3-.571-1.3-1.284v-.836c0-.71.58-1.285 1.3-1.285m-9.581-9.767a4.184 4.184 0 0 1 4.185-4.184h0a4.184 4.184 0 0 1 4.185 4.184v6.906M9.848 15.325v11.087");
}

.sl8psrprs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.848 19.506a4.184 4.184 0 0 1 4.185-4.184h0a4.184 4.184 0 0 1 4.184 4.184v6.906M38.5 15.325v6.902a4.184 4.184 0 0 1-4.185 4.185h0a4.185 4.185 0 0 1-4.185-4.181v-6.91");
}

</style>
