<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jqp-ikb0k"/><path class="bcwmhe6sp"/><path class="c2xrbabwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ntv" /></template>
<style>
.bcwmhe6sp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m22.812 19.023l5.507.004l5.09 13.927L38.5 19.027");
}

.c2xrbabwq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 19.6v18.9a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4h-29a4 4 0 0 0-4 4z");
}

.jqp-ikb0k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.812 14.803v15.766c0 1.577 1.018 2.628 2.545 2.628h.764m-6.441 0v-8.672c0-2.89-2.29-5.255-5.09-5.255S9.5 21.635 9.5 24.526v8.671m0-8.671v-5.255");
}

</style>
