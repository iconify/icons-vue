<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke5g8vb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:page-control" /></template>
<style>
.ke5g8vb9v {
  fill: currentColor;
  d: path("M2.722 13.278q-.53-.53-.53-1.278t.53-1.278T4 10.192t1.278.53t.53 1.278t-.53 1.278t-1.278.53t-1.278-.53m1.952-.604q.284-.284.284-.674t-.284-.674T4 11.042t-.674.284t-.284.674t.284.674t.674.284t.674-.284m3.36.604q-.53-.53-.53-1.278t.53-1.278t1.277-.53t1.278.53t.53 1.278t-.53 1.278t-1.278.53t-1.277-.53m1.951-.604q.284-.284.284-.674t-.284-.674t-.674-.284t-.674.284t-.283.674t.284.674t.673.284t.674-.284m3.387.604q-.53-.53-.53-1.278t.53-1.278t1.278-.53t1.278.53t.53 1.278t-.53 1.278t-1.278.53t-1.278-.53m1.952-.604q.284-.284.284-.674t-.284-.674t-.674-.284t-.674.284t-.284.674t.284.674t.674.284t.674-.284m3.398.604q-.53-.53-.53-1.278t.53-1.278t1.278-.53t1.278.53t.53 1.278t-.53 1.278t-1.278.53t-1.278-.53");
}

</style>
