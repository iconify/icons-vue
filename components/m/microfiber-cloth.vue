<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iddun-mvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:microfiber-cloth" /></template>
<style>
.iddun-mvq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 2.25H5Q2.25 2.25 2.25 5v14q0 2.75 2.75 2.75h8q.126 0 .246-.041l.006-.003q7.407-2.645 8.485-8.57l.001-.001v-.001q.012-.066.012-.134V5q0-2.75-2.75-2.75m1.024 11.593q-3.323.646-5.651 5.789q4.508-2.087 5.651-5.789");
}

</style>
