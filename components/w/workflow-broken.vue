<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="onvcyacty"/><path class="d6tpb8b8n"/><path class="afekvxh-f"/><path class="jxgmtgbwc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:workflow-broken" /></template>
<style>
.afekvxh-f {
  d: path("M6 10V12.4");
}

.d6tpb8b8n {
  d: path("M14 18V17C14 15.5858 14 14.8787 14.4394 14.4394C14.8787 14 15.5858 14 17 14H19C20.4142 14 21.1213 14 21.5607 14.4394C22 14.8787 22 15.5858 22 17V19C22 20.4142 22 21.1213 21.5607 21.5607C21.1213 22 20.4142 22 19 22H17C15.5858 22 14.8787 22 14.4394 21.5607C14 21.1213 14 20.4142 14 19V18Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jxgmtgbwc {
  d: path("M6.02246 15.5996C6.06616 16.4771 6.19676 17.0246 6.58626 17.4141C7.17206 17.9999 8.11486 17.9999 10.0005 17.9999H14.0005");
}

.onvcyacty {
  d: path("M2 6V5C2 3.5858 2 2.8787 2.4394 2.4394C2.8787 2 3.5858 2 5 2H7C8.4142 2 9.1213 2 9.5606 2.4394C10 2.8787 10 3.5858 10 5V7C10 8.4142 10 9.1213 9.5606 9.5606C9.1213 10 8.4142 10 7 10H5C3.5858 10 2.8787 10 2.4394 9.5606C2 9.1213 2 8.4142 2 7V6Z");
}

</style>
