<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rgy7dkbtt"/><circle class="rgxifwx2i"/><circle class="mf3qirbgi"/><rect class="gzk9sbnmb"/><rect class="uojoxm5mu"/><rect class="un3m2qbrw"/><circle class="v5uemzbuq"/><path class="h4tmo1q1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:memento-database" /></template>
<style>
.gzk9sbnmb {
  width: 11.108px;
  height: 37.596px;
  x: 18.446px;
  y: 5.202px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.019px;
}

.h4tmo1q1x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.153 24.436h3.703m-5.274-3.014h6.836v13.102h-6.836z");
}

.mf3qirbgi {
  cx: 24px;
  cy: 14.486px;
  r: 2.962px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rgxifwx2i {
  cx: 36.946px;
  cy: 14.486px;
  r: 2.962px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.rgy7dkbtt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.094 31.734h3.704m-3.704-3.649h3.704m-3.704-3.649h3.704m-5.27-3.014h6.836v13.102h-6.836zM9.202 31.734h3.704m-3.704-3.649h3.704m-3.704-3.649h3.704m-5.27-3.014h6.836v13.102H7.636zm14.517 10.312h3.703m-3.703-3.649h3.703");
}

.un3m2qbrw {
  width: 11.108px;
  height: 37.596px;
  x: 5.5px;
  y: 5.202px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.019px;
}

.uojoxm5mu {
  width: 11.108px;
  height: 37.596px;
  x: 31.392px;
  y: 5.202px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 1.019px;
}

.v5uemzbuq {
  cx: 11.054px;
  cy: 14.486px;
  r: 2.962px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
