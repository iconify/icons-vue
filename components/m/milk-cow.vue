<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxx7ykbso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:milk-cow" /></template>
<style>
.mxx7ykbso {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 3.5c0 2.5 1 4 3.25 4h8.5c2.25 0 3.25-1.5 3.25-4m-11.75 4l.5 7.75m8-7.75l-.418 6.487m-.654.889q-.314-.209-.682-.372q-.368-.164-.777-.276t-.843-.171Q11.442 14 11 14q-.221 0-.441.014t-.437.044q-.217.028-.428.071q-.212.043-.416.099t-.399.126t-.379.152q-.184.081-.355.175t-.327.198t-.297.218q-.14.114-.263.236q-.122.123-.227.253q-.104.13-.188.266q-.085.136-.149.277t-.108.286t-.064.291Q6.5 16.853 6.5 17t.022.294t.064.291q.044.145.108.286t.149.277q.084.136.188.266q.105.13.227.253q.123.122.263.236t.297.218q.156.105.327.198t.355.175t.379.152q.195.069.399.126t.416.099t.428.071q.217.029.437.044T11 20q.944 0 1.808-.253M7 9.5L3.5 11M15 9.5l3.5 1.5m0 2.75c1.5 2 3 3.5 3 5a3 3 0 0 1-6 0c0-1.5 1.5-3 3-5");
}

</style>
