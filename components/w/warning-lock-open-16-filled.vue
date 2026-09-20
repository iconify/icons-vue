<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x316omb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:warning-lock-open-16-filled" /></template>
<style>
.x316omb_a {
  fill: currentColor;
  d: path("M14 7a2 2 0 0 1 2 2a.5.5 0 1 1-1 0a1 1 0 1 0-2 0v1h1a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1h3V9a2 2 0 0 1 2-2m-2.5 5.25a.75.75 0 1 0 0 1.5a.75.75 0 0 0 0-1.5M4.82 1.275c.956-1.7 3.404-1.7 4.36 0l3 5.342A3 3 0 0 0 11 9H9c-.49 0-.94.177-1.288.47a.7.7 0 0 0 .038-.22A.751.751 0 1 0 7 10a.75.75 0 0 0 .311-.07C7.115 10.24 7 10.606 7 11v2.004H2.503c-1.911 0-3.115-2.058-2.179-3.725zM7 4a.5.5 0 0 0-.5.5V7a.5.5 0 0 0 1 0V4.5A.5.5 0 0 0 7 4");
}

</style>
