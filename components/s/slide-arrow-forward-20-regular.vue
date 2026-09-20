<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="cmqr70svd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-arrow-forward-20-regular" /></template>
<style>
.cmqr70svd {
  fill: currentColor;
  d: path("M14.5 10a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m1.604 1.896a.5.5 0 1 0-.707.707l.896.897H14.75A2.75 2.75 0 0 0 12 16.25v.25a.5.5 0 0 0 1 0v-.25c0-.966.784-1.75 1.75-1.75h1.543l-.896.896a.5.5 0 1 0 .707.707l1.752-1.751A.5.5 0 0 0 18 14a.5.5 0 0 0-.146-.354zM15.5 4A2.5 2.5 0 0 1 18 6.5v3.757a5.5 5.5 0 0 0-1-.656V6.5A1.5 1.5 0 0 0 15.5 5h-11A1.5 1.5 0 0 0 3 6.5v7A1.5 1.5 0 0 0 4.5 15h4.523q.047.517.185 1H4.5A2.5 2.5 0 0 1 2 13.5v-7A2.5 2.5 0 0 1 4.5 4zm-5.898 8a5.5 5.5 0 0 0-.394 1H5.5a.5.5 0 0 1 0-1zm2.607-2.5a5.5 5.5 0 0 0-1.482 1H5.5a.5.5 0 0 1 0-1zM9.5 7a.5.5 0 0 1 0 1h-4a.5.5 0 0 1 0-1z");
}

</style>
