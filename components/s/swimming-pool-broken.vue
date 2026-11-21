<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k8g767bxr"/><path class="s4ae-ybvv"/><path class="b6s5hxb5q"/><path class="e9rza7b1p"/><path class="b5916xbbx"/><path class="eyuipqjtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:swimming-pool-broken" /></template>
<style>
.b5916xbbx {
  d: path("M21.9991 20.043C20.4114 19.6912 19.5946 18.8268 18.919 17.8653C18.4956 17.263 17.5646 17.2995 17.1046 17.8778C16.5062 18.6303 15.7398 19.2969 14.7324 19.7317");
}

.b6s5hxb5q {
  d: path("M6.5 10.043H15.5");
}

.e9rza7b1p {
  d: path("M6.5 14.043H15.5");
}

.eyuipqjtv {
  d: path("M12.0028 20.257C12.0019 20.257 12.0009 20.257 12 20.257C9.4934 20.257 7.9181 18.9118 6.8665 17.6458C6.4272 17.1169 5.5862 17.1241 5.2017 17.6894C4.5008 18.72 3.684 19.6698 2 20.043");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k8g767bxr {
  d: path("M6.5 17.3615V5.74304C6.5 4.63844 7.3954 3.74304 8.5 3.74304C9.6046 3.74304 10.5 4.63844 10.5 5.74304");
}

.s4ae-ybvv {
  d: path("M15.5 19.3304V5.74304C15.5 4.63844 16.3954 3.74304 17.5 3.74304C18.6046 3.74304 19.5 4.63844 19.5 5.74304");
}

</style>
