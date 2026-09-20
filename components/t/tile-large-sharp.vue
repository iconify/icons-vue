<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r_fn6mq7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tile-large-sharp" /></template>
<style>
.r_fn6mq7v {
  fill: currentColor;
  d: path("M3 21v-6h8v6zm10 0v-6h8v6zM3 13V3h18v10z");
}

</style>
