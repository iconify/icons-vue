<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="uw4d6ambd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rename-28-filled" /></template>
<style>
.uw4d6ambd {
  fill: currentColor;
  d: path("M16.251 2a.75.75 0 0 1 0 1.5h-1.499v21h1.499a.75.75 0 0 1 0 1.5h-4.497a.75.75 0 0 1 0-1.5h1.498v-21h-1.498a.75.75 0 0 1 0-1.5zm-3.999 21H5.75A3.75 3.75 0 0 1 2 19.25V8.75A3.75 3.75 0 0 1 5.75 5h6.502zM22.25 5A3.75 3.75 0 0 1 26 8.75v10.5A3.75 3.75 0 0 1 22.25 23h-6.498V5z");
}

</style>
