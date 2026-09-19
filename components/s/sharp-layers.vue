<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wu32xnb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-layers" /></template>
<style>
.wu32xnb_k {
  fill: currentColor;
  d: path("m11.99 18.54l-7.37-5.73L3 14.07l9 7l9-7l-1.63-1.27zM12 16l7.36-5.73L21 9l-9-7l-9 7l1.63 1.27z");
}

</style>
