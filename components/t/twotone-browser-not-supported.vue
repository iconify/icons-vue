<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3bjaxnym"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-browser-not-supported" /></template>
<style>
.g3bjaxnym {
  fill: currentColor;
  d: path("M19 6v10.5l1.95 1.95c.03-.15.05-.3.05-.45V6c0-1.1-.9-2-2-2H6.5l2 2zM3.22 3.32L1.95 4.59L3 5.64V18c0 1.1.9 2 2 2h12.36l2.06 2.06l1.27-1.27zM15 18H5V7.64L15.36 18z");
}

</style>
