<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q80umkbqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:warning-24-filled" /></template>
<style>
.q80umkbqf {
  fill: currentColor;
  d: path("M9.138 3.707c1.228-2.276 4.493-2.276 5.721 0l6.743 12.502c1.168 2.165-.4 4.793-2.86 4.793H5.255c-2.46 0-4.028-2.628-2.86-4.793zM12.001 15a1 1 0 1 0 0 2a1 1 0 0 0 0-2m0-7.5a.75.75 0 0 0-.75.75v4.5a.75.75 0 0 0 1.5 0v-4.5A.75.75 0 0 0 12 7.5");
}

</style>
