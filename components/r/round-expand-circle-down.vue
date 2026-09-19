<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ma46656gz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-expand-circle-down" /></template>
<style>
.ma46656gz {
  fill: currentColor;
  d: path("M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10s10-4.48 10-10S17.52 2 12 2m3.79 9.71l-3.08 3.08c-.39.39-1.02.39-1.42 0l-3.08-3.08c-.39-.39-.39-1.03 0-1.42a.996.996 0 0 1 1.41 0L12 12.67l2.38-2.38a.996.996 0 0 1 1.41 0c.39.39.39 1.03 0 1.42");
}

</style>
