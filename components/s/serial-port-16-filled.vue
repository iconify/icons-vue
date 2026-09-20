<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x9noqo-yf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:serial-port-16-filled" /></template>
<style>
.x9noqo-yf {
  fill: currentColor;
  d: path("M1.078 7.47A2 2 0 0 1 3.022 5h9.97a2 2 0 0 1 1.944 2.47l-.726 3A2 2 0 0 1 12.266 12h-8.52a2 2 0 0 1-1.943-1.53zM5 8a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1m1.5 1.5a.5.5 0 1 0-1 0a.5.5 0 0 0 1 0M8 10a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1m2.5-.5a.5.5 0 1 0-1 0a.5.5 0 0 0 1 0M7 8a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1m2.5-.5a.5.5 0 1 0-1 0a.5.5 0 0 0 1 0M11 8a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1");
}

</style>
