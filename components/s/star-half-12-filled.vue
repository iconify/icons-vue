<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="yjvaxu6yp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:star-half-12-filled" /></template>
<style>
.yjvaxu6yp {
  fill: currentColor;
  d: path("M6 1.1a.79.79 0 0 0-.717.446L4.172 3.798l-2.486.361a.8.8 0 0 0-.444 1.365l1.8 1.753l-.425 2.476a.8.8 0 0 0 1.16.844L6 9.428z");
}

</style>
