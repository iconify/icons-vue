<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v7jwvxbfp"/><path class="c08afxeqs"/><path class="mbnxtrb5x"/><path class="b1weiybkx"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:podlisten" /></template>
<style>
.b1weiybkx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.965 7.602a16.397 16.397 0 0 1 16.397 16.397");
}

.c08afxeqs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.17 24.529s.512-3.61-2.815-3.61s-2.772 5.878-5.879 5.878");
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

.mbnxtrb5x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.845 30.604s-1.155.186-1.155 2.001s3.906 1.65 3.906-1.156s-3.166-4.237-1.494-7.082m2.863-11.37a11 11 0 0 1 11.002 11.002");
}

.v7jwvxbfp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.978 23.317a6.775 6.775 0 1 1 12.75 4.267c-.987 3.112-5.153 5.32-5.873 9.154s-7.818 4.031-7.395-1.44");
}

</style>
