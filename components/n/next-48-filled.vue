<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t0p_mxb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:next-48-filled" /></template>
<style>
.t0p_mxb3m {
  fill: currentColor;
  d: path("M40.75 6c-.69 0-1.25.56-1.25 1.25v33.5a1.25 1.25 0 0 0 2.5 0V7.25C42 6.56 41.44 6 40.75 6M6 9.256c0-2.615 2.931-4.16 5.088-2.68l21.504 14.743c1.883 1.29 1.883 4.07 0 5.36L11.088 41.424C8.93 42.9 6 41.357 6 38.743z");
}

</style>
