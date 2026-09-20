<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zl_jivbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mountain-flag" /></template>
<style>
.zl_jivbnk {
  fill: currentColor;
  d: path("m7.025 11.825l.825-1.7q.25-.525.738-.825T9.65 9H11V2h7l-1 2l1 2h-5v3h1.275q.575 0 1.038.3t.737.8l.875 1.75l-3 2L12 12.875l-1.925.975zM2 22l4.125-8.375l3.8 2.525L12 15.125l2.075 1.025l3.75-2.475L22 22z");
}

</style>
