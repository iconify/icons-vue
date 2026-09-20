<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="isv6rdb8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-distributed-vertical-24-filled" /></template>
<style>
.isv6rdb8o {
  fill: currentColor;
  d: path("M19 5.414V21a1 1 0 1 1-2 0V5.414l-.293.293a1 1 0 1 1-1.414-1.414l2-2a1 1 0 0 1 1.414 0l2 2a1 1 0 0 1-1.414 1.414zM5 18.586l-.293-.293a1 1 0 0 0-1.414 1.414l2 2a1 1 0 0 0 1.414 0l2-2a1 1 0 1 0-1.414-1.414L7 18.586V3a1 1 0 1 0-2 0zM13 3a1 1 0 1 0-2 0v18a1 1 0 1 0 2 0z");
}

</style>
