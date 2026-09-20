<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fwk7bvdji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tornado-rounded" /></template>
<style>
.fwk7bvdji {
  fill: currentColor;
  d: path("M2.75 6L3.9 8h16.2l1.15-2q.575-1 .013-2t-1.738-1H4.475Q3.3 3 2.738 4t.012 2m2.3 4l1.75 3h10.4l1.75-3zm2.9 5l2.325 4q.575 1 1.725 1t1.725-1l2.325-4z");
}

</style>
