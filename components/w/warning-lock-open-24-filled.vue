<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vu4_6qqrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:warning-lock-open-24-filled" /></template>
<style>
.vu4_6qqrs {
  fill: currentColor;
  d: path("M21.5 11.5A2.5 2.5 0 0 1 24 14a.75.75 0 0 1-1.5 0a1 1 0 0 0-2 0v1h1a1.5 1.5 0 0 1 1.5 1.5v5a1.5 1.5 0 0 1-1.5 1.5h-6a1.5 1.5 0 0 1-1.5-1.5v-5a1.5 1.5 0 0 1 1.5-1.5H19v-1a2.5 2.5 0 0 1 2.5-2.5M9.139 3.707c1.227-2.276 4.493-2.276 5.72 0l4.2 7.786A3.5 3.5 0 0 0 18 14h-2.5a2.5 2.5 0 0 0-2.5 2.5v4.502H5.255c-2.46 0-4.028-2.628-2.86-4.793zM18.499 18a1 1 0 1 0 .001 2a1 1 0 0 0 0-2m-6.498-3a1 1 0 1 0 0 2.001a1 1 0 0 0 0-2m0-7.5a.75.75 0 0 0-.75.75v4.5a.75.75 0 0 0 1.5 0v-4.5A.75.75 0 0 0 12 7.5");
}

</style>
