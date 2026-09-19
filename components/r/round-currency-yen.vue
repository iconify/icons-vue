<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r0thr3h_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-currency-yen" /></template>
<style>
.r0thr3h_c {
  fill: currentColor;
  d: path("M6.82 3c.34 0 .66.17.84.46L12 10.29l4.34-6.83c.18-.29.5-.46.84-.46c.79 0 1.27.87.84 1.54L13.92 11H17c.55 0 1 .45 1 1s-.45 1-1 1h-4v2h4c.55 0 1 .45 1 1s-.45 1-1 1h-4v3c0 .55-.45 1-1 1s-1-.45-1-1v-3H7c-.55 0-1-.45-1-1s.45-1 1-1h4v-2H7c-.55 0-1-.45-1-1s.45-1 1-1h3.08l-4.1-6.46A.998.998 0 0 1 6.82 3");
}

</style>
