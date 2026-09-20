<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1fmylgku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:swipe-left-alt-outline-sharp" /></template>
<style>
.p1fmylgku {
  fill: currentColor;
  d: path("M14.5 16.5q-1.748 0-3.005-1.137T10.023 12.5H4.921l2.095 2.1l-.708.708L3 12l3.308-3.308l.713.708l-2.1 2.1h5.102q.216-1.725 1.472-2.863T14.5 7.5q1.864 0 3.182 1.318T19 12t-1.318 3.182T14.5 16.5m2.48-2.02Q18 13.463 18 12t-1.02-2.48T14.5 8.5t-2.48 1.02T11 12t1.02 2.48t2.48 1.02t2.48-1.02M14.5 12");
}

</style>
