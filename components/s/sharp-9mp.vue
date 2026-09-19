<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4n51fjcs"/><path class="nfzgjs8xe"/><path class="lof-rmboq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-9mp" /></template>
<style>
.k4n51fjcs {
  fill: currentColor;
  d: path("M15 14h1.5v1.5H15z");
}

.lof-rmboq {
  fill: currentColor;
  d: path("M11.5 6.5H13V8h-1.5z");
}

.nfzgjs8xe {
  fill: currentColor;
  d: path("M3 3v18h18V3zm7 7h3V9h-3V5.5h4.5v6H10zm2.5 8.5H11V14h-1v3H8.5v-3h-1v4.5H6v-6h6.5zM18 17h-3v1.5h-1.5v-6H18z");
}

</style>
