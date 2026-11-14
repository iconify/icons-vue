<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q81pux7tg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:optical-disc" /></template>
<style>
.q81pux7tg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m7.941-6.343Q6.734 6.734 5.657 9.691q-.025.07-.036.143q-.012.073-.008.147q.003.074.02.145q.018.072.049.139t.075.126q.044.06.098.11t.118.088t.132.064q.07.025.143.036q.073.012.147.008q.074-.003.145-.02q.072-.018.139-.049t.126-.075t.11-.098t.088-.118q.039-.063.064-.132q.837-2.301 3.138-3.138q.069-.025.132-.064q.063-.038.118-.088t.098-.11q.044-.059.075-.126t.049-.139q.017-.071.02-.145q.004-.074-.008-.147q-.011-.073-.036-.143t-.064-.132t-.088-.118q-.05-.054-.11-.098q-.059-.044-.126-.075t-.139-.049t-.145-.02q-.074-.004-.147.008q-.073.011-.143.036M15 12q0-3-3-3t-3 3t3 3t3-3");
}

</style>
