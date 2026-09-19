<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="m2g2vgbwg"/><circle class="ps4jjyl5g"/><circle class="cf83mw_bq"/><circle class="nayle4ksa"/><path class="bb-mwjxwt"/><path class="b6jwnvzpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:skoob-alt" /></template>
<style>
.b6jwnvzpp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.765 41.266a8.94 8.94 0 0 1-5.498-1.565a4.95 4.95 0 0 1-2.031-3.68c-1.397-.64-3.862-1.768-3.862-5.432v-5.802l3.859 2.077v-.99a8.505 8.505 0 0 1-.99-13.005s-1.385-1.401-1.385-2.23V4.5l11.565 5.777C23.983 11.555 24 12.914 24 12.914s.017-1.359 2.577-2.637L38.143 4.5v6.139c0 .828-1.385 2.23-1.385 2.23a8.505 8.505 0 0 1-.99 13.006v.99l3.858-2.078v5.802c0 3.664-2.464 4.792-3.861 5.432a4.94 4.94 0 0 1-2.032 3.68a8.94 8.94 0 0 1-5.497 1.565c-2.256-.005-4.242 2.234-4.242 2.234s-1.986-2.239-4.241-2.234Z");
}

.bb-mwjxwt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.009 21.618a1.243 1.243 0 0 0-1.187 1.286a8.6 8.6 0 0 0 1.187 2.473a8.5 8.5 0 0 0 1.187-2.473a1.24 1.24 0 0 0-1.187-1.286M12.523 33.282c-.92-.481-1.77-1.032-1.77-2.07v-2.573l11.2 5.799a8.1 8.1 0 0 1 2.054 2.017a8.1 8.1 0 0 1 2.054-2.017l11.199-5.799v2.572c0 1.04-.848 1.59-1.769 2.071l-11.486 6.01Z");
}

.cf83mw_bq {
  cx: 17.084px;
  cy: 18.966px;
  r: 5.244px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.m2g2vgbwg {
  cx: 30.934px;
  cy: 18.966px;
  r: 5.244px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.nayle4ksa {
  cx: 17.084px;
  cy: 21.123px;
  r: 1.583px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ps4jjyl5g {
  cx: 30.934px;
  cy: 21.123px;
  r: 1.583px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
