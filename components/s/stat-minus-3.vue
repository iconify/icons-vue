<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7aj_op-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stat-minus-3" /></template>
<style>
.t7aj_op-h {
  fill: currentColor;
  d: path("m12 21.925l-6-6l1.4-1.4L12 19.1l4.6-4.575l1.4 1.4zm0-5.95l-6-6l1.4-1.4L12 13.15l4.6-4.575l1.4 1.4zm0-5.95l-6-6l1.4-1.4L12 7.2l4.6-4.575l1.4 1.4z");
}

</style>
