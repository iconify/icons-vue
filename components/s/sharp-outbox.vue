<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjbh-w5vd"/><path class="c12gq0bqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-outbox" /></template>
<style>
.bjbh-w5vd {
  fill: currentColor;
  d: path("M11 14h2v-3h3l-4-4l-4 4h3z");
}

.c12gq0bqz {
  fill: currentColor;
  d: path("M3 3v18h18V3zm16 11h-4.18c-.41 1.16-1.51 2-2.82 2s-2.4-.84-2.82-2H5V5h14z");
}

</style>
