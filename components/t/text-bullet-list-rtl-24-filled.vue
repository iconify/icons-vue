<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewm-8ebfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-bullet-list-rtl-24-filled" /></template>
<style>
.ewm-8ebfh {
  fill: currentColor;
  d: path("M20.504 16.5a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3m-4 .5H3a1 1 0 0 0-.117 1.993L3 19h13.503a1 1 0 0 0 .117-1.993zm4-6.5a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3m-4 .5H3a1 1 0 0 0-.117 1.993L3 13h13.503a1 1 0 0 0 .117-1.993zm4-6.492a1.5 1.5 0 1 0 0 2.999a1.5 1.5 0 0 0 0-3m-4 .493H3a1 1 0 0 0-.117 1.993L3 7.001h13.503a1 1 0 0 0 .117-1.993z");
}

</style>
