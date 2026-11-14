<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h2uswbcfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ski-touring" /></template>
<style>
.h2uswbcfl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.164 5.25H9q-1.968 0-3.359 1.391T4.25 10v11.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h14q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V10q0-1.968-1.391-3.359q-.956-.955-2.183-1.254l.552-2.205q.036-.145.014-.292q-.022-.148-.099-.276t-.197-.217t-.264-.125q-.072-.018-.146-.021q-.073-.004-.146.007t-.143.036t-.133.063t-.118.088t-.099.109t-.075.126t-.05.138l-.608 2.432h-1.953l.517-2.068q.036-.145.014-.292q-.022-.148-.099-.276t-.197-.217t-.264-.125q-.072-.018-.146-.021q-.073-.004-.146.007t-.143.036t-.133.063t-.118.088t-.099.109t-.075.126t-.05.138z");
}

</style>
