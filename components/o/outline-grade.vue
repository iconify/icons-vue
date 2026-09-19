<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ccsde4bvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-grade" /></template>
<style>
.ccsde4bvn {
  fill: currentColor;
  d: path("m12 7.13l.97 2.29l.47 1.11l1.2.1l2.47.21l-1.88 1.63l-.91.79l.27 1.18l.56 2.41l-2.12-1.28l-1.03-.64l-1.03.62l-2.12 1.28l.56-2.41l.27-1.18l-.91-.79l-1.88-1.63l2.47-.21l1.2-.1l.47-1.11zM12 2L9.19 8.63L2 9.24l5.46 4.73L5.82 21L12 17.27L18.18 21l-1.64-7.03L22 9.24l-7.19-.61z");
}

</style>
