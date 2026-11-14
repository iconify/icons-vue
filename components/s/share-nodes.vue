<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qt912bcbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:share-nodes" /></template>
<style>
.qt912bcbz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.75 5.501v-.002q-.001-1.346.951-2.298q.952-.953 2.299-.953t2.299.953t.951 2.298q.001 1.347-.951 2.3T18 8.752t-2.299-.953q-.062-.062-.12-.126l-6.9 3.45q.069.404.069.877t-.069.877l6.9 3.45q.058-.064.12-.126q.952-.953 2.299-.953t2.299.953t.951 2.298q.001 1.347-.951 2.3T18 21.752t-2.299-.953t-.951-2.298v-.002q0-.45.106-.857l-6.76-3.38q-.804.988-2.596.988q-3.25 0-3.25-3.25T5.5 8.75q1.792 0 2.596.988l6.76-3.38q-.106-.407-.106-.857");
}

</style>
