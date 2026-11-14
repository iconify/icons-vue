<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy8hnrv3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:speaker" /></template>
<style>
.wy8hnrv3a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.375 1.75h5.25q2.123 0 3.624 1.501t1.501 3.624v10.25q0 2.123-1.501 3.624t-3.624 1.501h-5.25q-2.123 0-3.624-1.501T4.25 17.125V6.875q0-2.123 1.501-3.624T9.375 1.75M10 7.5q0 2 2 2t2-2t-2-2t-2 2m-2.25 7q0 1.76 1.245 3.005T12 18.75t3.005-1.245T16.25 14.5t-1.245-3.005T12 10.25t-3.005 1.245T7.75 14.5m1.5 0q0 2.75 2.75 2.75q1.139 0 1.945-.805q.805-.806.805-1.945t-.805-1.945q-.806-.805-1.945-.805q-2.75 0-2.75 2.75");
}

</style>
