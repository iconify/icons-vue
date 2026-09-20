<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hbdza66_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:square-arrow-forward-32-light" /></template>
<style>
.hbdza66_l {
  fill: currentColor;
  d: path("M3 7.5A4.5 4.5 0 0 1 7.5 3h17A4.5 4.5 0 0 1 29 7.5v8.775a9 9 0 0 0-1-.9V7.5A3.5 3.5 0 0 0 24.5 4h-17A3.5 3.5 0 0 0 4 7.5v17A3.5 3.5 0 0 0 7.5 28h7.876q.412.534.899 1H7.5A4.5 4.5 0 0 1 3 24.5zM22.5 30a7.5 7.5 0 1 1 0-15a7.5 7.5 0 0 1 0 15m1.22-10.22L24.94 21h-2.69A4.25 4.25 0 0 0 18 25.25v.5a.75.75 0 0 0 1.5 0v-.5a2.75 2.75 0 0 1 2.75-2.75h2.69l-1.22 1.22a.75.75 0 1 0 1.06 1.06l2.5-2.5a.75.75 0 0 0 0-1.06l-2.5-2.5a.75.75 0 1 0-1.06 1.06");
}

</style>
