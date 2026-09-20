<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydc38ybbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pinch-sharp" /></template>
<style>
.ydc38ybbx {
  fill: currentColor;
  d: path("M9.5 6V3.55L3.55 9.5H6V11H1V6h1.5v2.45L8.45 2.5H6V1h5v5zm4.075 17L7.6 17l1.575-1.625l2.825.8V7h2v8h1v-4h2v4h1v-3h2v3h1v-1h2v9z");
}

</style>
