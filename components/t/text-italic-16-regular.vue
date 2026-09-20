<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sftiv9bio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-italic-16-regular" /></template>
<style>
.sftiv9bio {
  fill: currentColor;
  d: path("M13 2H7a.5.5 0 0 0 0 1h2.474L5.656 13H3a.5.5 0 0 0 0 1h6a.5.5 0 0 0 0-1H6.726l3.818-10H13a.5.5 0 0 0 0-1");
}

</style>
