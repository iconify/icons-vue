<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x1wiarbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:open-office" /></template>
<style>
.x1wiarbvd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.75 2.25h4.5q2.5 0 2.5 2.5v14.5q0 1.036-.732 1.768t-1.768.732h-4.5q-1.036 0-1.768-.732T7.25 19.25V4.75q0-2.5 2.5-2.5M5.414 4.586Q4.828 4 4 4t-1.414.586T2 6v1q0 2 2 2q.828 0 1.414-.586T6 7V6q0-.828-.586-1.414M20 4q2 0 2 2v1q0 2-2 2t-2-2V6q0-2 2-2M4 9.5q.828 0 1.414.586T6 11.5v1q0 .828-.586 1.414T4 14.5q-2 0-2-2v-1q0-.828.586-1.414T4 9.5m18 2q0-2-2-2t-2 2v1q0 2 2 2t2-2zM5.414 15.586Q4.828 15 4 15t-1.414.586T2 17v1q0 2 2 2q.828 0 1.414-.586T6 18v-1q0-.828-.586-1.414M20 15q2 0 2 2v1q0 2-2 2t-2-2v-1q0-2 2-2");
}

</style>
