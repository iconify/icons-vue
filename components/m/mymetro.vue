<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jcsug0erx"/><path class="sqi4m_svd"/><path class="nw8kjksmg"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mymetro" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.jcsug0erx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.959 32.032a1.3 1.3 0 0 1-1.132.646a1.293 1.293 0 0 1-1.3-1.284v-.836c0-.71.583-1.285 1.3-1.285s1.3.576 1.3 1.285v.418h-2.6m4.138-1.703h1.367m-.682-1.063v3.826c0 .355.288.642.647.642h.197m-10.093-2.12c0-.71.58-1.285 1.3-1.285c.714 0 1.297.576 1.297 1.285v2.12M9.5 29.273v3.405m0-2.12c0-.71.583-1.285 1.3-1.285s1.301.576 1.301 1.285v2.12m11.839-3.405v3.405m0-2.12c0-.71.583-1.285 1.3-1.285m2.558 0c.722 0 1.3.572 1.3 1.285v.836c0 .709-.578 1.284-1.3 1.284s-1.3-.571-1.3-1.284v-.836c0-.71.58-1.285 1.3-1.285m-9.581-9.767a4.184 4.184 0 1 1 8.37 0v6.906M9.848 15.325v11.087");
}

.nw8kjksmg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 22.227v5.653a4.184 4.184 0 0 1-4.185 4.18a4.17 4.17 0 0 1-2.96-1.224");
}

.sqi4m_svd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.848 19.506a4.184 4.184 0 1 1 8.37 0v6.906M38.5 15.325v6.902a4.185 4.185 0 0 1-8.37.004v-6.91");
}

</style>
