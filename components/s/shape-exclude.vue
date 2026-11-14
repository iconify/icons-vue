<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jxrtz9b6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:shape-exclude" /></template>
<style>
.jxrtz9b6m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.375 2.25h3.25q2.123 0 3.624 1.501t1.501 3.624v.875h.875q2.123 0 3.624 1.501t1.501 3.624v3.25q0 2.123-1.501 3.624t-3.624 1.501h-3.25q-2.123 0-3.624-1.501T8.25 16.625v-.875h-.875q-2.123 0-3.624-1.501T2.25 10.625v-3.25q0-2.123 1.501-3.624T7.375 2.25m3.125 6q-2.25 0-2.25 2.25v3q0 2.25 2.25 2.25h3q2.25 0 2.25-2.25v-3q0-2.25-2.25-2.25z");
}

</style>
