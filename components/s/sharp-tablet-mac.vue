<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9n1rdb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-tablet-mac" /></template>
<style>
.n9n1rdb8t {
  fill: currentColor;
  d: path("M21 0H2v24h19zm-9.5 23c-.83 0-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5s1.5.67 1.5 1.5s-.67 1.5-1.5 1.5m7.5-4H4V3h15z");
}

</style>
