<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvp7d5bux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:streetball" /></template>
<style>
.lvp7d5bux {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.875 1.75H6.125q-3.375 0-3.375 3.375v3.25q0 1.398.989 2.386q.988.989 2.386.989h11.75q1.398 0 2.386-.989q.989-.988.989-2.386v-3.25q0-3.375-3.375-3.375M11 4.5h2q2.25 0 2.25 2.25T13 9h-2Q8.75 9 8.75 6.75T11 4.5M6.25 14.748Q6.253 13 12 13q5.75 0 5.75 1.75q0 .232-.101.434l-1.935 6.045q-.018.056-.044.109q-.027.053-.062.101q-.034.048-.076.09t-.09.077t-.1.062q-.053.027-.109.045q-.057.018-.115.028q-.059.009-.118.009H9q-.059 0-.118-.009q-.058-.01-.115-.028q-.056-.018-.109-.045q-.052-.027-.1-.062t-.09-.077t-.076-.09t-.062-.101q-.026-.053-.044-.109l-1.935-6.045q-.101-.201-.101-.432zm2.003 1.458l1.294 4.044h4.906l1.294-4.044Q14.356 16.5 12 16.5t-3.747-.294");
}

</style>
