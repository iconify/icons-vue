<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i0lxp-s-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shopping-bag-32-filled" /></template>
<style>
.i0lxp-s-n {
  fill: currentColor;
  d: path("M9 6.5a4.5 4.5 0 0 1 7-3.743A4.5 4.5 0 0 1 23 6.5V10h2a2 2 0 0 1 2 2v14.5a3.5 3.5 0 1 1-7 0V10h.998V6.5A2.5 2.5 0 0 0 17.4 4.254c.382.66.6 1.428.6 2.246v20c0 1.33.472 2.55 1.257 3.5H9.5A4.5 4.5 0 0 1 5 25.5V12a2 2 0 0 1 2-2h2zm2 3.5h5V6.5a2.5 2.5 0 0 0-5 0z");
}

</style>
