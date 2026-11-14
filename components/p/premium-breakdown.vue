<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0w1wbc3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:premium-breakdown" /></template>
<style>
.l0w1wbc3a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146V12q0 .098.025.192t.073.179t.117.154q.068.07.152.12h.001l7.999 4.75q.064.038.133.062q.07.025.143.035t.147.007t.145-.022t.138-.05t.126-.076t.109-.1t.087-.118q.038-.064.062-.133q.025-.07.035-.143t.007-.147t-.022-.145t-.05-.138t-.076-.126t-.1-.109t-.118-.087l-7.633-4.532V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q12.074 1.75 12 1.75q4.246 0 7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12");
}

</style>
