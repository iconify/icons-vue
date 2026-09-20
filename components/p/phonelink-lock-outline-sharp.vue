<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3lih32dp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:phonelink-lock-outline-sharp" /></template>
<style>
.n3lih32dp {
  fill: currentColor;
  d: path("M15 16v-5h1v-1q0-.825.588-1.412T18 8t1.413.588T20 10v1h1v5zm2-5h2v-1q0-.425-.288-.712T18 9t-.712.288T17 10zM5 23V1h14v6h-2V6H7v12h10v-1h2v6zm2-3v1h10v-1zM7 4h10V3H7zm0 0V3zm0 16v1z");
}

</style>
