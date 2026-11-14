<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oyh-m6bif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:theta" /></template>
<style>
.oyh-m6bif {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.764 11.288q.115-.038.236-.038h12q.121 0 .236.038q-.144-3.485-1.707-6.043Q14.699 2.25 12 2.25T7.471 5.245q-1.563 2.558-1.707 6.043m12.472 1.424q-.115.038-.236.038H6q-.121 0-.236-.038q.144 3.485 1.707 6.043Q9.301 21.75 12 21.75t4.529-2.995q1.563-2.558 1.707-6.043");
}

</style>
