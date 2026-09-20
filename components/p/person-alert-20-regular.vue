<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iy37e3zyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-alert-20-regular" /></template>
<style>
.iy37e3zyz {
  fill: currentColor;
  d: path("M9 2a4 4 0 1 0 0 8a4 4 0 0 0 0-8M6 6a3 3 0 1 1 6 0a3 3 0 0 1-6 0m-1.991 5A2 2 0 0 0 2 13c0 1.691.833 2.966 2.135 3.797C5.417 17.614 7.145 18 9 18a13 13 0 0 0 1.113-.048A1.48 1.48 0 0 1 9.089 17H9c-1.735 0-3.257-.364-4.327-1.047C3.623 15.283 3 14.31 3 13c0-.553.448-1 1.009-1h6.616q.138-.534.41-1zm7.49 2a3 3 0 0 1 6 0v2l1.32 1.119a.5.5 0 0 1-.323.881h-7.993a.5.5 0 0 1-.323-.881L11.5 15zm3 6a1.5 1.5 0 0 1-1.414-1h2.829a1.5 1.5 0 0 1-1.415 1");
}

</style>
