<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b12aw9bkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:vip-48-regular" /></template>
<style>
.b12aw9bkz {
  fill: currentColor;
  d: path("M37.75 8A6.25 6.25 0 0 1 44 14.25v19.5A6.25 6.25 0 0 1 37.75 40h-27.5A6.25 6.25 0 0 1 4 33.75v-19.5A6.25 6.25 0 0 1 10.25 8zm-27.5 2.5a3.75 3.75 0 0 0-3.75 3.75v19.5a3.75 3.75 0 0 0 3.75 3.75h27.5a3.75 3.75 0 0 0 3.75-3.75v-19.5a3.75 3.75 0 0 0-3.75-3.75zm8.581 6.806a1.25 1.25 0 0 1 2.338.888L16.507 30.46a1.612 1.612 0 0 1-3.014 0L8.831 18.194a1.25 1.25 0 0 1 2.338-.888L15 27.388zm5.919-.806c.69 0 1.25.56 1.25 1.25v12.5a1.25 1.25 0 1 1-2.5 0v-12.5c0-.69.56-1.25 1.25-1.25m9.75 0a5 5 0 0 1 0 10h-3v3.75a1.25 1.25 0 1 1-2.5 0v-12.5a1.25 1.25 0 0 1 1.25-1.25zm-3 7.5h3a2.5 2.5 0 0 0 0-5h-3z");
}

</style>
