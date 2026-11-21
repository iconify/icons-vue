<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nd6yr9bpy"/><path class="nvy5-f21s"/><path class="t-kia8b5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:whistle-broken" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nd6yr9bpy {
  d: path("M3.19939 15.2128C2.33949 13.6993 2.10019 11.8631 2.62899 10.1164C3.45899 7.375 5.98579 5.5 8.85009 5.5H20.2501C21.1501 5.5 21.6501 6.1 21.6501 6.9V8.1C21.6501 8.9 21.0501 9.5 20.0501 9.5H14.8501C15.9518 12.144 15.1928 15.1975 12.9815 17.0181C10.8665 18.7594 7.89979 18.9802 5.56009 17.606");
}

.nvy5-f21s {
  d: path("M10.8496 5.5V8.1");
}

.t-kia8b5d {
  d: path("M11.0504 12C11.0504 13.215 10.0654 14.2 8.85039 14.2C7.63539 14.2 6.65039 13.215 6.65039 12C6.65039 10.785 7.63539 9.80005 8.85039 9.80005C10.0654 9.80005 11.0504 10.785 11.0504 12Z");
}

</style>
