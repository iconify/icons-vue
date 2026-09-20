<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zeakjwbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:unfold-less-rounded" /></template>
<style>
.zeakjwbdz {
  fill: currentColor;
  d: path("m12 16.208l-2.746 2.746q-.14.14-.344.15t-.364-.15t-.16-.354t.16-.354l2.888-2.888q.132-.131.268-.184q.137-.053.298-.053t.298.053t.268.184l2.888 2.888q.14.14.15.344t-.15.364t-.354.16t-.354-.16zm0-8.416l2.746-2.746q.14-.14.344-.15t.364.15t.16.354t-.16.354l-2.889 2.888q-.13.131-.267.184q-.136.053-.298.053t-.298-.053t-.267-.184L8.546 5.754q-.14-.14-.15-.344t.15-.364t.354-.16t.354.16z");
}

</style>
