<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q--43hbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:ribbon-16-filled" /></template>
<style>
.q--43hbti {
  fill: currentColor;
  d: path("M8 1a5 5 0 1 0 0 10A5 5 0 0 0 8 1M5 14.5v-3.303c.883.51 1.907.803 3 .803a6 6 0 0 0 3-.803V14.5a.5.5 0 0 1-.757.429L8 13.583L5.757 14.93A.5.5 0 0 1 5 14.5");
}

</style>
