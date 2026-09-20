<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tfh5rdb5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-mail-48-regular" /></template>
<style>
.tfh5rdb5r {
  fill: currentColor;
  d: path("M46 42.001a4 4 0 0 1-4 4H28a4 4 0 0 1-4-4v-8.138l10.25 5.918a1.5 1.5 0 0 0 1.5 0L46 33.863zM23.53 28a6 6 0 0 0-1.341 2.5H10.25a1.75 1.75 0 0 0-1.75 1.749V33c0 2.744 1.36 4.808 3.72 6.245c2.259 1.375 5.422 2.154 9.049 2.246L22 41.5v.5c0 .7.12 1.37.34 1.995L22 44c-4.214 0-8.151-.837-11.08-2.62C7.942 39.567 6 36.755 6 33v-.751A4.25 4.25 0 0 1 10.25 28zm18.47.001a4 4 0 0 1 3.976 3.565L35 37.904l-10.977-6.338A4 4 0 0 1 28 28.001zM22 4c5.523 0 10 4.477 10 10s-4.477 10-10 10s-10-4.477-10-10S16.477 4 22 4m0 2.5a7.5 7.5 0 1 0 0 15a7.5 7.5 0 0 0 0-15");
}

</style>
