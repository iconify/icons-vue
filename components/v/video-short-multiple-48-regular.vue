<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ia5lmvp6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-short-multiple-48-regular" /></template>
<style>
.ia5lmvp6z {
  fill: currentColor;
  d: path("M37.48 9.736a6.24 6.24 0 0 1 2.518 5.014v18.5c0 5.937-4.813 10.75-10.75 10.75h-10.5a6.24 6.24 0 0 1-5.014-2.518q.255.016.514.018h15a8.25 8.25 0 0 0 8.25-8.25v-23a8 8 0 0 0-.017-.514M29.25 4a6.25 6.25 0 0 1 6.25 6.25v23a6.25 6.25 0 0 1-6.25 6.25h-15A6.25 6.25 0 0 1 8 33.25v-23A6.25 6.25 0 0 1 14.25 4zm-15 2.5a3.75 3.75 0 0 0-3.75 3.75v23A3.75 3.75 0 0 0 14.25 37h15A3.75 3.75 0 0 0 33 33.25v-23a3.75 3.75 0 0 0-3.75-3.75zM17 18.265c0-1.927 2.088-3.13 3.755-2.163l6.005 3.486c1.66.963 1.66 3.36 0 4.324l-6.005 3.486c-1.667.967-3.755-.236-3.755-2.163z");
}

</style>
