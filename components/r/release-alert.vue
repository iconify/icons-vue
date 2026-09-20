<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mbqk2qb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:release-alert" /></template>
<style>
.mbqk2qb8k {
  fill: currentColor;
  d: path("m9.023 21.23l-1.67-2.814l-3.176-.685l.312-3.277L2.346 12L4.49 9.546L4.177 6.27l3.177-.685L9.023 2.77L12 4.027l2.977-1.258l1.67 2.816l3.176.684l-.312 3.277L21.655 12l-2.142 2.454l.311 3.277l-3.177.684l-1.669 2.816L12 19.973zm3.41-4.95q.183-.182.183-.434t-.182-.434t-.434-.181t-.434.182t-.182.433t.182.434t.434.181t.434-.181m-.934-3.126h1v-6h-1z");
}

</style>
