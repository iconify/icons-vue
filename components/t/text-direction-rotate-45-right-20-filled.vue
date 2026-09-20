<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="chasltphm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-direction-rotate-45-right-20-filled" /></template>
<style>
.chasltphm {
  fill: currentColor;
  d: path("M17.25 8a.75.75 0 0 1 .75.75v2.5a.75.75 0 0 1-.75.75h-2.5a.75.75 0 1 1 0-1.5h.69l-2.22-2.22a.75.75 0 0 1 1.06-1.06l2.22 2.22v-.69a.75.75 0 0 1 .75-.75m-3.83-4.915a.75.75 0 0 0-1.005-1.006l-8 4a.75.75 0 1 0 .671 1.342L7.27 6.329l1.902 1.902l-1.092 2.183a.75.75 0 1 0 1.342.671zM9.879 6.817L8.683 5.622l2.39-1.195zM12 14.749a.75.75 0 0 0-1.5 0v.69L3.28 8.22a.75.75 0 1 0-1.06 1.06l7.22 7.22h-.69a.75.75 0 0 0 0 1.5h2.5a.75.75 0 0 0 .75-.75z");
}

</style>
