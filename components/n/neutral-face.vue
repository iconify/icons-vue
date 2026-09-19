<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="wpkg-bb-u"/><g class="n1mjunbsu"><ellipse class="b6mkypc2s"/><ellipse class="wlq0dccxs"/></g><g class="mrjy-p0fq"><ellipse class="q4yxjac7o"/><ellipse class="fz0y70tqi"/></g><path class="kbg05qcvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:neutral-face" /></template>
<style>
.b6mkypc2s {
  cx: 20.865px;
  cy: 28.481px;
  rx: 6.5px;
  ry: 9.737px;
}

.fz0y70tqi {
  cx: 42.858px;
  cy: 28.481px;
  rx: 4.206px;
  ry: 5.099px;
}

.kbg05qcvv {
  fill: var(--svg-color--633c17, #633c17);
  d: path("M39.06 52.876a2.02 2.02 0 0 1-2.02 2.02H26.928a2.02 2.02 0 1 1 0-4.04h10.111c1.118 0 2.023.906 2.023 2.02");
}

.mrjy-p0fq {
  fill: var(--svg-color--25333a, #25333a);
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.q4yxjac7o {
  cx: 20.866px;
  cy: 28.481px;
  rx: 4.206px;
  ry: 5.099px;
}

.wlq0dccxs {
  cx: 42.858px;
  cy: 28.481px;
  rx: 6.5px;
  ry: 9.737px;
}

.wpkg-bb-u {
  fill: var(--svg-color--fbbf67, #fbbf67);
  d: path("M63.957 31.98c0 17.66-14.316 31.979-31.979 31.979C14.314 63.959 0 49.641 0 31.98C0 14.316 14.314 0 31.979 0c17.662 0 31.978 14.316 31.978 31.98");
}

</style>
