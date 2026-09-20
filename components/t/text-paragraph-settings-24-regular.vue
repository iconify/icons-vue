<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ed_v5-bsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-paragraph-settings-24-regular" /></template>
<style>
.ed_v5-bsa {
  fill: currentColor;
  d: path("M16.5 8a4.25 4.25 0 0 0 0 8.5h.5v4.75a.75.75 0 0 0 1.5 0V9.5h1v11.75a.75.75 0 0 0 1.5 0V9.5h.25a.75.75 0 0 0 0-1.5zm0 1.5h.5V15h-.5a2.75 2.75 0 1 1 0-5.5M2.75 5a.75.75 0 0 0 0 1.5h18.5a.75.75 0 0 0 0-1.5zm0 5a.75.75 0 0 0 0 1.5h8.553c.076-.53.23-1.034.452-1.5zm9.277 5H2.75a.75.75 0 0 0 0 1.5h10.667a5.3 5.3 0 0 1-1.39-1.5");
}

</style>
