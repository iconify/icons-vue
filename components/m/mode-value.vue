<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyicjubfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:mode-value" /></template>
<style>
.lyicjubfb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 1.5q-2 0-2 2t2 2q-2 0-2 2t2 2q-2 0-2 2t2 2t2-2t-2-2q2 0 2-2t-2-2q2 0 2-2t-2-2m-6.75 10q0-1.75 1.75-1.75t1.75 1.75T9 13.25T7.25 11.5m4.75 4q0-2 2-2t2 2t-2 2t-2-2m2 2q2 0 2 2t-2 2t-2-2t2-2M4 13.75q-1.75 0-1.75 1.75T4 17.25t1.75-1.75T4 13.75m5 0q-1.75 0-1.75 1.75T9 17.25t1.75-1.75T9 13.75m8.75 1.75q0-1.75 1.75-1.75t1.75 1.75t-1.75 1.75t-1.75-1.75m-15.5 4q0-1.75 1.75-1.75t1.75 1.75T4 21.25T2.25 19.5m5 0q0-1.75 1.75-1.75t1.75 1.75T9 21.25T7.25 19.5m12.25-1.75q-1.75 0-1.75 1.75t1.75 1.75t1.75-1.75t-1.75-1.75");
}

</style>
