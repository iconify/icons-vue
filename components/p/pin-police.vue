<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sl7iq238f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pin-police" /></template>
<style>
.sl7iq238f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 14.215V17.5q0 .049.006.097q.02.148.094.277q.075.13.193.22v.001l.003.002q6.954 5.346 13.908 0l.003-.002l.016-.013q.065-.052.116-.118t.088-.142q.036-.075.055-.157q.018-.081.018-.165v-3.285l2.386-3.818q.114-.182.114-.397q0-2.941-3.198-4.718Q15.794 3.75 12 3.75T5.448 5.282Q2.25 7.059 2.25 10q0 .215.114.397zm5-4.715q0-2.25 2.25-2.25t2.25 2.25T12 11.75T9.75 9.5m-1.673 8.75h7.846q-3.923 1.959-7.846 0");
}

</style>
