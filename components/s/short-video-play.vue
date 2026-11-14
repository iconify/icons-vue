<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dchgzacaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:short-video-play" /></template>
<style>
.dchgzacaa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.625 1.75h-3.25q-2.123 0-3.624 1.501T5.25 6.875v10.25q0 2.123 1.501 3.624t3.624 1.501h3.25q2.123 0 3.624-1.501t1.501-3.624V6.875q0-2.123-1.501-3.624T13.625 1.75m-1.167 7.584l1.206.768q1.041.664 1.041 1.898t-1.041 1.898l-1.206.768q-1.124.714-2.291.073T9 12.767v-1.534q0-1.331 1.167-1.972t2.29.073z");
}

</style>
