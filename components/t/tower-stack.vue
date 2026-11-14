<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zkzo1iovu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tower-stack" /></template>
<style>
.zkzo1iovu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.467 8.156q.064.322.202.594H7.75q-2.5 0-2.5 2.5v2.5q0 .547.204 1.009q-2.204.144-2.204 2.491v2.5q0 1.036.732 1.768t1.768.732h12.5q1.036 0 1.768-.732t.732-1.768v-2.5q0-2.347-2.204-2.491q.204-.462.204-1.009v-2.5q0-1.036-.732-1.768q-.494-.494-1.126-.654q1.412-.631 1.053-2.426l-.412-2.058q-.184-.923-.971-1.439t-1.706-.319l-4.066.871q-2.171.464-1.735 2.641z");
}

</style>
