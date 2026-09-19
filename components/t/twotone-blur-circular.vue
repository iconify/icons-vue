<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jjdxbxb-a"/><circle class="fh7l_pbbp"/><circle class="bq7_jnb-d"/><path class="qz4mqgcgp"/><circle class="rk2z91bkc"/><path class="lyg3h_c2b"/><circle class="tffiggcyh"/><path class="rccw5fb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-blur-circular" /></template>
<style>
.bq7_jnb-d {
  cx: 14px;
  cy: 14px;
  r: 1px;
  fill: currentColor;
}

.fh7l_pbbp {
  cx: 14px;
  cy: 10px;
  r: 1px;
  fill: currentColor;
}

.jjdxbxb-a {
  fill: currentColor;
  d: path("M14 7.5c.28 0 .5-.22.5-.5s-.22-.5-.5-.5s-.5.22-.5.5s.22.5.5.5");
}

.lyg3h_c2b {
  fill: currentColor;
  d: path("M7 13.5c-.28 0-.5.22-.5.5s.22.5.5.5s.5-.22.5-.5s-.22-.5-.5-.5M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10s10-4.48 10-10S17.52 2 12 2m0 18c-4.42 0-8-3.58-8-8s3.58-8 8-8s8 3.58 8 8s-3.58 8-8 8M7 9.5c-.28 0-.5.22-.5.5s.22.5.5.5s.5-.22.5-.5s-.22-.5-.5-.5");
}

.qz4mqgcgp {
  fill: currentColor;
  d: path("M10 16.5c-.28 0-.5.22-.5.5s.22.5.5.5s.5-.22.5-.5s-.22-.5-.5-.5");
}

.rccw5fb3e {
  fill: currentColor;
  d: path("M10 7.5c.28 0 .5-.22.5-.5s-.22-.5-.5-.5s-.5.22-.5.5s.22.5.5.5m4 9c-.28 0-.5.22-.5.5s.22.5.5.5s.5-.22.5-.5s-.22-.5-.5-.5m3-7c-.28 0-.5.22-.5.5s.22.5.5.5s.5-.22.5-.5s-.22-.5-.5-.5m0 4c-.28 0-.5.22-.5.5s.22.5.5.5s.5-.22.5-.5s-.22-.5-.5-.5");
}

.rk2z91bkc {
  cx: 10px;
  cy: 10px;
  r: 1px;
  fill: currentColor;
}

.tffiggcyh {
  cx: 10px;
  cy: 14px;
  r: 1px;
  fill: currentColor;
}

</style>
