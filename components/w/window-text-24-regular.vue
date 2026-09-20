<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-o8v_b9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:window-text-24-regular" /></template>
<style>
.r-o8v_b9o {
  fill: currentColor;
  d: path("M3 6.25A3.25 3.25 0 0 1 6.25 3h11.5A3.25 3.25 0 0 1 21 6.25v11.5A3.25 3.25 0 0 1 17.75 21H6.25A3.25 3.25 0 0 1 3 17.75zM4.5 7h15v-.75a1.75 1.75 0 0 0-1.75-1.75H6.25A1.75 1.75 0 0 0 4.5 6.25zm15 1.5h-15v9.25c0 .966.784 1.75 1.75 1.75h11.5a1.75 1.75 0 0 0 1.75-1.75zm-12.75 2a.75.75 0 0 0 0 1.5h10.5a.75.75 0 0 0 0-1.5zm0 2.75a.75.75 0 0 0 0 1.5h6a.75.75 0 0 0 0-1.5zm9 0a.75.75 0 0 0 0 1.5h1.5a.75.75 0 0 0 0-1.5zm-9 2.75a.75.75 0 0 0 0 1.5h1.5a.75.75 0 0 0 0-1.5zm4.5 0a.75.75 0 0 0 0 1.5h6a.75.75 0 0 0 0-1.5z");
}

</style>
