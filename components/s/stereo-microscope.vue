<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf4vmiihz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:stereo-microscope" /></template>
<style>
.yf4vmiihz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.248 6.25H9.252L7.694 2.464q-.029-.068-.07-.129q-.04-.062-.093-.114q-.052-.053-.113-.094t-.13-.069t-.14-.043Q7.075 2 7.002 2q-.074 0-.147.014q-.072.014-.141.042q-.138.057-.243.163q-.106.105-.163.243q-.058.137-.058.286q0 .15.056.288l1.459 3.543Q6.75 7.157 6.75 8.75v2q0 1.036.732 1.768t1.768.732h3q1.036 0 1.768-.732t.732-1.768v-.5h2v7.5H5q-2.25 0-2.25 2.25T5 22.25h14q2.25 0 2.25-2.25T19 17.75h-.75V9.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-2.75q0-1.593-1.015-2.171l1.459-3.543q.056-.138.056-.288t-.058-.286q-.057-.138-.163-.243q-.105-.106-.243-.163q-.069-.028-.141-.042Q14.572 2 14.498 2q-.073 0-.146.015q-.072.014-.14.043t-.13.069t-.113.094q-.053.052-.093.114q-.041.061-.07.129z");
}

</style>
