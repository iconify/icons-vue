<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pq3q2hbui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:signal-medium" /></template>
<style>
.pq3q2hbui {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.75 2.75h2q1.036 0 1.768.732t.732 1.768v13.5q0 2.5-2.5 2.5h-2q-2.5 0-2.5-2.5V5.25q0-2.5 2.5-2.5m-7.5 9h-2q-2.5 0-2.5 2.5v4.5q0 2.5 2.5 2.5h2q2.5 0 2.5-2.5v-4.5q0-2.5-2.5-2.5");
}

</style>
