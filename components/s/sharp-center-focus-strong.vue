<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iv5juyb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-center-focus-strong" /></template>
<style>
.iv5juyb3u {
  fill: currentColor;
  d: path("M12 8c-2.21 0-4 1.79-4 4s1.79 4 4 4s4-1.79 4-4s-1.79-4-4-4m-7 7H3v6h6v-2H5zM5 5h4V3H3v6h2zm16-2h-6v2h4v4h2zm-2 16h-4v2h6v-6h-2z");
}

</style>
