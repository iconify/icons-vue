<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m8k5ulbua"/><path class="hc7yyybut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:midea-smart-home" /></template>
<style>
.hc7yyybut {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.209 39.676L37.11 22.454c.082 10.036-3.937 17.975-12.451 20.517c-8.642 2.58-17.74-2.34-20.318-10.989");
}

.m8k5ulbua {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.765 9.707c2.795.54 4.968 2.523 5.41 5.587m-5.41-10.952c5.752.692 10.046 4.312 10.894 10.952M4.783 28.547c-.79-7.438 3.9-14.566 11.351-16.607c6.747-1.848 13.673 1.043 17.236 6.654M15.303 39.857c8.598-1.42 11.655-7.575 12.31-17.393l3.096 17.222");
}

</style>
