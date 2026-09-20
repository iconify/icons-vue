<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="p8wdywsav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-short-multiple-28-regular" /></template>
<style>
.p8wdywsav {
  fill: currentColor;
  d: path("M22.469 5.229a3.74 3.74 0 0 1 1.529 3.021v11.5a6.25 6.25 0 0 1-6.25 6.25h-7.5a3.74 3.74 0 0 1-3.021-1.53q.256.03.521.03h10a4.75 4.75 0 0 0 4.75-4.75v-14q0-.264-.03-.521M17.75 2a3.75 3.75 0 0 1 3.75 3.75v14a3.75 3.75 0 0 1-3.75 3.75h-10A3.75 3.75 0 0 1 4 19.75v-14A3.75 3.75 0 0 1 7.75 2zm-10 1.5A2.25 2.25 0 0 0 5.5 5.75v14A2.25 2.25 0 0 0 7.75 22h10A2.25 2.25 0 0 0 20 19.75v-14a2.25 2.25 0 0 0-2.25-2.25zM10 10.251a1.5 1.5 0 0 1 2.295-1.272l4 2.499a1.5 1.5 0 0 1 0 2.545l-4 2.499A1.5 1.5 0 0 1 10 15.249z");
}

</style>
