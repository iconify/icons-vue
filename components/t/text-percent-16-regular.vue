<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x72dz0buv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-percent-16-regular" /></template>
<style>
.x72dz0buv {
  fill: currentColor;
  d: path("M11.989 2.085a.5.5 0 0 1 .134.695L4.706 13.777a.5.5 0 0 1-.829-.559L11.295 2.22a.5.5 0 0 1 .694-.135M4.5 3a1.5 1.5 0 1 0 0 3a1.5 1.5 0 0 0 0-3M2 4.5a2.5 2.5 0 1 1 5 0a2.5 2.5 0 0 1-5 0m8 7a1.5 1.5 0 1 1 3 0a1.5 1.5 0 0 1-3 0M11.5 9a2.5 2.5 0 1 0 0 5a2.5 2.5 0 0 0 0-5");
}

</style>
