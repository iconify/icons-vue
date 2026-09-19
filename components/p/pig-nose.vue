<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="zxb0ipbma"/><path class="yzxgy-1cx"/><ellipse class="l904654gm"/><path class="qfiqlacqh"/><ellipse class="t9_3_71bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:pig-nose" /></template>
<style>
.l904654gm {
  cx: 19.9px;
  cy: 33.6px;
  fill: var(--svg-color--bf7b90, #bf7b90);
  rx: 6.1px;
  ry: 12.8px;
}

.qfiqlacqh {
  fill: var(--svg-color--a5627a, #a5627a);
  d: path("M52.7 33.6c0 7.4-3.3 13.4-7.3 13.4c-4.1 0-7.3-6-7.3-13.4s3.3-13.4 7.3-13.4c4 .1 7.3 6 7.3 13.4");
}

.t9_3_71bv {
  cx: 46.7px;
  cy: 33.6px;
  fill: var(--svg-color--bf7b90, #bf7b90);
  rx: 6.1px;
  ry: 12.8px;
}

.yzxgy-1cx {
  fill: var(--svg-color--a5627a, #a5627a);
  d: path("M25.9 33.6c0 7.4-3.3 13.4-7.3 13.4c-4.1 0-7.3-6-7.3-13.4s3.3-13.4 7.3-13.4c4.1.1 7.3 6 7.3 13.4");
}

.zxb0ipbma {
  fill: var(--svg-color--fc97b2, #fc97b2);
  d: path("M62 37.3c0 17.3-13.4 15.3-30 15.3s-30 2-30-15.3s13.4-25.9 30-25.9S62 20 62 37.3");
}

</style>
