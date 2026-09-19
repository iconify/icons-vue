<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d6fbn9bfn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-manage-search" /></template>
<style>
.d6fbn9bfn {
  fill: currentColor;
  d: path("M7 9H2V7h5zm0 3H2v2h5zm13.59 7l-3.83-3.83c-.8.52-1.74.83-2.76.83c-2.76 0-5-2.24-5-5s2.24-5 5-5s5 2.24 5 5c0 1.02-.31 1.96-.83 2.75L22 17.59zM17 11c0-1.65-1.35-3-3-3s-3 1.35-3 3s1.35 3 3 3s3-1.35 3-3M2 19h10v-2H2z");
}

</style>
