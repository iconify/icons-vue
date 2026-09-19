<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a2pjctt9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-no-crash" /></template>
<style>
.a2pjctt9y {
  fill: currentColor;
  d: path("M18.57 8H5.43L3 15v9h3v-2h12v2h3v-9zM6.85 10h10.29l1.04 3H5.81zM6 17.5c0-.83.67-1.5 1.5-1.5s1.5.67 1.5 1.5S8.33 19 7.5 19S6 18.33 6 17.5m9 0c0-.83.67-1.5 1.5-1.5s1.5.67 1.5 1.5s-.67 1.5-1.5 1.5s-1.5-.67-1.5-1.5M12 6.36L9.17 3.54l1.41-1.41L12 3.54L15.54 0l1.41 1.41z");
}

</style>
