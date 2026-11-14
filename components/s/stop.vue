<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_0-jgvxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:stop" /></template>
<style>
.t_0-jgvxk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.875 3.75h6.25q2.123 0 3.624 1.501t1.501 3.624v6.25q0 2.123-1.501 3.624t-3.624 1.501h-6.25q-2.123 0-3.624-1.501T3.75 15.125v-6.25q0-2.123 1.501-3.624T8.875 3.75");
}

</style>
