<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c45qpo8sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:swipe-right-alt-outline-rounded" /></template>
<style>
.c45qpo8sb {
  fill: currentColor;
  d: path("M9.5 16.5q-1.864 0-3.182-1.318T5 12t1.318-3.182T9.5 7.5q1.748 0 3.005 1.138t1.472 2.862h5.102l-1.746-1.746q-.14-.14-.15-.341q-.01-.202.156-.367q.159-.16.353-.16t.354.16l2.389 2.388q.13.132.183.268q.053.137.053.298t-.053.298q-.052.137-.183.268l-2.389 2.388q-.14.14-.341.15t-.366-.15q-.166-.166-.166-.357t.166-.357l1.74-1.74h-5.102q-.215 1.725-1.472 2.863T9.5 16.5m2.48-2.02Q13 13.463 13 12t-1.02-2.48T9.5 8.5T7.02 9.52T6 12t1.02 2.48T9.5 15.5t2.48-1.02M9.5 12");
}

</style>
