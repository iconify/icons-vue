<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kiqgrp9kq"/><circle class="aucn04utj"/><circle class="p89deovsh"/><circle class="iljorvysz"/><circle class="goi3u9bnw"/><circle class="ub4d63l7m"/><circle class="ge9jc-4ss"/><circle class="smfgmpbti"/><circle class="wk2b4rbah"/><circle class="t7y87xbel"/><circle class="bh08iobnd"/><circle class="w23d_qkzq"/><circle class="ssbqunfwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-deblur" /></template>
<style>
.aucn04utj {
  cx: 6px;
  cy: 14px;
  r: 1px;
  fill: currentColor;
}

.bh08iobnd {
  cx: 10px;
  cy: 14px;
  r: 1.5px;
  fill: currentColor;
}

.ge9jc-4ss {
  cx: 3px;
  cy: 14px;
  r: 0.5px;
  fill: currentColor;
}

.goi3u9bnw {
  cx: 3px;
  cy: 10px;
  r: 0.5px;
  fill: currentColor;
}

.iljorvysz {
  cx: 6px;
  cy: 10px;
  r: 1px;
  fill: currentColor;
}

.kiqgrp9kq {
  fill: currentColor;
  d: path("M12 3v18a9 9 0 0 0 0-18");
}

.p89deovsh {
  cx: 6px;
  cy: 18px;
  r: 1px;
  fill: currentColor;
}

.smfgmpbti {
  cx: 10px;
  cy: 21px;
  r: 0.5px;
  fill: currentColor;
}

.ssbqunfwc {
  cx: 10px;
  cy: 18px;
  r: 1px;
  fill: currentColor;
}

.t7y87xbel {
  cx: 10px;
  cy: 6px;
  r: 1px;
  fill: currentColor;
}

.ub4d63l7m {
  cx: 6px;
  cy: 6px;
  r: 1px;
  fill: currentColor;
}

.w23d_qkzq {
  cx: 10px;
  cy: 10px;
  r: 1.5px;
  fill: currentColor;
}

.wk2b4rbah {
  cx: 10px;
  cy: 3px;
  r: 0.5px;
  fill: currentColor;
}

</style>
