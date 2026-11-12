<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xlqalnq-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-pause-corner-fill-sharp" /></template>
<style>
.xlqalnq-f {
  fill: currentColor;
  d: path("M4 7a5 5 0 1 1 10.001.001A5 5 0 0 1 4 7m12 6v8a1 1 0 0 1-2 0v-8a1 1 0 0 1 2 0m4 0v8a1 1 0 0 1-2 0v-8a1 1 0 0 1 2 0m-10 2v6a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1c0-1.862.731-3.636 2.05-4.95a6.9 6.9 0 0 1 2.225-1.499A6.9 6.9 0 0 1 9 14a1 1 0 0 1 1 1");
}

</style>
