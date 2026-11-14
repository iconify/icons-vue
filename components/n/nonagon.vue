<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oynqwl5ip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:nonagon" /></template>
<style>
.oynqwl5ip {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m8.278 22.083l-5.25-4.25q-.109-.089-.179-.211q-.07-.123-.091-.262l-1-6.75q-.018-.124.005-.247q.022-.123.084-.232l3.25-5.75q.066-.117.169-.204t.23-.133l6.25-2.25q.121-.043.251-.044q.129-.001.251.042l.006.002l6.25 2.25q.127.046.23.133t.169.204l3.25 5.75q.062.109.084.232t.005.247l-1 6.75q-.021.139-.091.262q-.07.122-.179.211l-5.25 4.25q-.1.081-.222.124q-.121.043-.25.043h-6.5q-.129 0-.25-.043q-.122-.043-.222-.124M6.266 5.361L3.28 10.645l.919 6.206l4.817 3.899h5.968l4.817-3.899l.919-6.206l-2.986-5.284L12 3.297z");
}

</style>
