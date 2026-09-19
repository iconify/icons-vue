<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijmuagale"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-cloud-circle" /></template>
<style>
.ijmuagale {
  fill: currentColor;
  d: path("M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10s10-4.48 10-10S17.52 2 12 2m4.5 14H8c-1.66 0-3-1.34-3-3s1.34-3 3-3h.14c.44-1.73 1.99-3 3.86-3c2.21 0 4 1.79 4 4h.5a2.5 2.5 0 0 1 0 5");
}

</style>
