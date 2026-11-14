<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v81fa5noo"/><path class="hyiitqbus"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:release-paused" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hyiitqbus {
  d: path("m3.5 7l8.5 4.5L20.5 7M12 11.5v10m4.75-5.75v5.75m3.5-5.75v5.75");
}

.v81fa5noo {
  d: path("m13.949 20.469l-1.13.598q-.189.1-.397.152T12 21.27q-.214 0-.422-.051q-.208-.052-.397-.152l-6.75-3.574q-.105-.056-.201-.125t-.183-.151q-.086-.081-.161-.174q-.074-.092-.135-.194t-.109-.211q-.046-.109-.078-.223q-.032-.115-.048-.233q-.016-.117-.016-.236V8.054q0-.119.016-.236q.016-.118.048-.233q.032-.114.078-.223q.047-.109.109-.211q.061-.102.135-.194t.161-.174t.183-.151t.201-.125l6.75-3.574q.189-.1.397-.152T12 2.73t.422.051q.208.052.397.152l6.75 3.574q.105.056.201.125t.183.151q.086.081.161.174q.074.092.135.194t.109.211q.046.109.078.223q.032.115.048.233q.016.117.016.236v4.957");
}

</style>
