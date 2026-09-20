<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="so7-fdbno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:things-to-do-sharp" /></template>
<style>
.so7-fdbno {
  fill: currentColor;
  d: path("M4.077 20v-1H7v-4.5H5.539v-1h1.484q.07-1.798 1.365-3.055T11.5 9.023V4.846h5.077v2.846H12.5v1.331q1.817.166 3.113 1.422t1.364 3.055h1.485v1H17V19h2.923v1zM8 19h3.5v-4.5H8zm4.5 0H16v-4.5h-3.5z");
}

</style>
