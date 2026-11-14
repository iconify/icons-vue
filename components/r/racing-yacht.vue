<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="in2f7kb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:racing-yacht" /></template>
<style>
.in2f7kb_l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 8.81v4.44q0 .932-.659 1.591T9 15.5H6.544q-1.285 0-1.938-1.107t-.031-2.232l2.456-4.44q.843-1.526 2.531-1.09T11.25 8.81m5.263-.11l-.001-.001q-.88-1.375-2.446-.916q-1.568.46-1.566 2.092v3.375q0 .932.659 1.591t1.591.659h2.007q1.334 0 1.974-1.17t-.08-2.294zM3 17h18q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .227-.126.416q-2.389 3.584-7.124 3.584H6q-2.773 0-3.728-3.818q-.018-.072-.021-.146q-.004-.073.007-.146t.036-.143t.063-.133t.088-.118t.109-.099t.126-.075t.138-.05Q2.908 17 3 17");
}

</style>
