<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="j_nyaz5fz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-indent-increase-20-filled" /></template>
<style>
.j_nyaz5fz {
  fill: currentColor;
  d: path("M6 4.75A.75.75 0 0 1 6.75 4h7.5a.75.75 0 0 1 0 1.5h-7.5A.75.75 0 0 1 6 4.75M6.75 9a.75.75 0 0 0 0 1.5h10.5a.75.75 0 0 0 0-1.5zm0 5a.75.75 0 0 0 0 1.5h5.5a.75.75 0 0 0 0-1.5zM3.03 7.72a.75.75 0 0 0-1.06 1.06l.97.97l-.97.97a.75.75 0 1 0 1.06 1.06l1.5-1.5a.75.75 0 0 0 0-1.06z");
}

</style>
