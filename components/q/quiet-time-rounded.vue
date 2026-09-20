<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jk43jxbqc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:quiet-time-rounded" /></template>
<style>
.jk43jxbqc {
  fill: currentColor;
  d: path("M13.1 23q-2.1 0-3.937-.8t-3.2-2.163Q4.6 18.675 3.8 16.837T3 12.9q0-3.2 1.8-5.8t4.825-3.65q.55-.2 1.025.137t.45.913q-.075 2.125.675 4.05t2.25 3.425q1.5 1.5 3.425 2.25t4.05.675q.575-.025.938.388t.187.912q-1.05 3.075-3.663 4.938T13.1 23Z");
}

</style>
