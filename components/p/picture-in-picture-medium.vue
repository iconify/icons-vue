<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opjb4nsqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:picture-in-picture-medium" /></template>
<style>
.opjb4nsqm {
  fill: currentColor;
  d: path("M3 19v-1h16.385q.23 0 .307-.192q.077-.193.077-.424V5H21v12.385q0 .69-.462 1.153T19.385 19zm4.923-3.384V7.923h9.693v7.693z");
}

</style>
