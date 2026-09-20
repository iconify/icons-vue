<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="age_hvcvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:people-lock-32-filled" /></template>
<style>
.age_hvcvz {
  fill: currentColor;
  d: path("M23 16.5a3.5 3.5 0 0 1 3.5 3.5v.5h.5a2.5 2.5 0 0 1 2.5 2.5v6a2.5 2.5 0 0 1-2.5 2.5h-8a2.5 2.5 0 0 1-2.5-2.5v-6a2.5 2.5 0 0 1 2.5-2.5h.5V20a3.5 3.5 0 0 1 3.5-3.5m0 7.5a2 2 0 1 0 0 4a2 2 0 0 0 0-4m-7-7c.956 0 1.806.45 2.355 1.146a5 5 0 0 0-.275.96A4 4 0 0 0 15 23v2.26c-1.143.45-2.611.74-4.5.74C2.04 26 2 20.205 2 20.15V20a3 3 0 0 1 3-3zm7 1.5a1.5 1.5 0 0 0-1.5 1.5v.5h3V20a1.5 1.5 0 0 0-1.5-1.5M10.5 4a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11M23 7a4 4 0 1 1 0 8a4 4 0 0 1 0-8");
}

</style>
