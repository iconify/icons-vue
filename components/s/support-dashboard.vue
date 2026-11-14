<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddaewnh2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:support-dashboard" /></template>
<style>
.ddaewnh2b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.125 1.75h2.75q3.375 0 3.375 3.375v5.25q0 3.375-3.375 3.375h-2.75q-3.375 0-3.375-3.375v-5.25q0-3.375 3.375-3.375m11 0h2.75q3.375 0 3.375 3.375v2.25q0 3.375-3.375 3.375h-2.75q-3.375 0-3.375-3.375v-2.25q0-3.375 3.375-3.375m-2.346 15.595Q14.092 14 17.75 14q1.657 0 2.828 1.172q.931.93 1.122 2.167q1.05.306 1.05 1.661v1.5q0 1.75-1.75 1.75t-1.75-1.75V19q0-1.274.928-1.621q-.158-.645-.66-1.147q-.732-.732-1.768-.732q-2.162 0-2.454 1.87q.954.338.954 1.63v1.5q0 1.75-1.75 1.75t-1.75-1.75V19q0-1.342 1.029-1.655M7.875 15.25h-2.75q-1.398 0-2.386.989q-.989.988-.989 2.386v.25q0 3.375 3.375 3.375h2.75q3.375 0 3.375-3.375v-.25q0-3.375-3.375-3.375m6.625 3.5q-.25 0-.25.25v1.5q0 .25.25.25t.25-.25V19q0-.25-.25-.25m6.25.25v1.5q0 .25.25.25t.25-.25V19q0-.25-.25-.25t-.25.25");
}

</style>
