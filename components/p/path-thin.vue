<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xn_lntb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:path-thin" /></template>
<style>
.xn_lntb0o {
  fill: currentColor;
  d: path("M200 172a28 28 0 0 0-27.71 24H72a36 36 0 0 1 0-72h96a36 36 0 0 0 0-72H72a4 4 0 0 0 0 8h96a28 28 0 0 1 0 56H72a44 44 0 0 0 0 88h100.29A28 28 0 1 0 200 172m0 48a20 20 0 1 1 20-20a20 20 0 0 1-20 20");
}

</style>
