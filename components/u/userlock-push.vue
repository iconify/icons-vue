<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g_kdql1tc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:userlock-push" /></template>
<style>
.g_kdql1tc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.132 44.373C8.625 41.513 2.5 33.472 2.5 24C2.5 12.123 12.123 2.5 24 2.5c11.866 0 21.5 9.623 21.5 21.5c0 9.472-6.125 17.514-14.632 20.373l-4.09-12.122A8.7 8.7 0 0 0 32.716 24c0-4.812-3.905-8.716-8.716-8.716S15.284 19.189 15.284 24c0 3.835 2.487 7.1 5.938 8.251z");
}

</style>
