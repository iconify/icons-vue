<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0y--7bqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-media-bluetooth-off" /></template>
<style>
.o0y--7bqh {
  fill: currentColor;
  d: path("M9 6.17V3h6v4h-4v1.17zM19.42 15L22 17.57l-.8.8l-6.78-6.78l.8-.8l2.75 2.75V9h.6L22 12.43zm-.25-1.45l1.13-1.13l-1.13-1.13zm-1.96 3.66l3.98 3.98l-1.41 1.41l-3.98-3.98l-.58.58l-.85-.85l.58-.58L11 13.83V17c0 2.21-1.78 4-3.99 4S3 19.21 3 17s1.79-4 4.01-4c.73 0 1.41.21 2 .55v-1.72L1.39 4.22L2.8 2.81l13.56 13.56z");
}

</style>
