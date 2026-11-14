<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tq8yv6btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:razor-blade" /></template>
<style>
.tq8yv6btx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.875 6.25H6.125q-3.375 0-3.375 3.375v4.75q0 3.375 3.375 3.375h11.75q3.375 0 3.375-3.375v-4.75q0-3.375-3.375-3.375M7 10.25q1.323 0 1.646 1h6.708q.323-1 1.646-1q1.75 0 1.75 1.75T17 13.75q-1.323 0-1.646-1H8.646q-.323 1-1.646 1q-1.75 0-1.75-1.75T7 10.25");
}

</style>
