<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ns_bg4bvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:merge-outline-rounded" /></template>
<style>
.ns_bg4bvh {
  fill: currentColor;
  d: path("m12 14.4l-5.265 5.266q-.14.14-.332.133q-.191-.007-.337-.153q-.141-.14-.141-.344t.14-.344l4.337-4.342q.633-.633.865-1.166t.233-1.429V5.883L9.716 7.667q-.141.14-.332.14t-.338-.145q-.14-.14-.14-.345q0-.203.14-.344l2.389-2.407q.242-.243.565-.243t.566.243l2.407 2.407q.14.14.143.332q.003.191-.143.337q-.14.14-.344.14t-.344-.14L12.5 5.882v6.14q0 .895.252 1.447t.885 1.185l4.317 4.323q.14.14.143.332q.003.191-.143.337q-.14.14-.344.14t-.344-.14z");
}

</style>
