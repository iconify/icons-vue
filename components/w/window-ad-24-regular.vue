<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0o9zbwlh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:window-ad-24-regular" /></template>
<style>
.f0o9zbwlh {
  fill: currentColor;
  d: path("M3 6.25A3.25 3.25 0 0 1 6.25 3h11.5A3.25 3.25 0 0 1 21 6.25v11.5A3.25 3.25 0 0 1 17.75 21H6.25A3.25 3.25 0 0 1 3 17.75zM4.5 7h15v-.75a1.75 1.75 0 0 0-1.75-1.75H6.25A1.75 1.75 0 0 0 4.5 6.25zm15 1.5h-15v9.25c0 .966.784 1.75 1.75 1.75h11.5a1.75 1.75 0 0 0 1.75-1.75zM6.75 10a.75.75 0 0 0-.75.75v5c0 .414.336.75.75.75h5a.75.75 0 0 0 .75-.75v-5a.75.75 0 0 0-.75-.75zm.75 5v-3.5H11V15z");
}

</style>
