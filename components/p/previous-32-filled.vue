<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w9bi1-01t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:previous-32-filled" /></template>
<style>
.w9bi1-01t {
  fill: currentColor;
  d: path("M6 5a1 1 0 0 0-2 0v22a1 1 0 1 0 2 0zm22.003 1.504c0-2.002-2.236-3.192-3.897-2.073l-14.003 9.432A2.5 2.5 0 0 0 10.09 18l14.003 9.56c1.66 1.132 3.91-.056 3.91-2.065z");
}

</style>
