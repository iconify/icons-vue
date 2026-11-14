<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iw3rwoc5c"/><path class="fhgyskb1s"/><path class="jnlbp6bts"/><path class="zad87zbci"/><path class="bxnbedcrs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:tree-linear" /></template>
<style>
.bxnbedcrs {
  d: path("M7.5 21.8H16.5");
}

.fhgyskb1s {
  d: path("M12 21.8V9.59998");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iw3rwoc5c {
  d: path("M12.0005 16H7.20047C4.40047 16 2.80047 14 3.20047 11.4C3.50047 9.40001 5.20047 8.20001 6.50047 7.80001C6.40047 4.40001 8.80047 2.20001 12.0005 2.20001C15.2005 2.20001 17.6005 4.40001 17.5005 7.80001C18.8005 8.20001 20.5005 9.40001 20.8005 11.4C21.2005 14 19.6005 16 16.8005 16H12.0005Z");
}

.jnlbp6bts {
  d: path("M12 13.6L15 10.6");
}

.zad87zbci {
  d: path("M12 13.6L9 10.6");
}

</style>
