<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r_89zyhos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:triangle-16-regular" /></template>
<style>
.r_89zyhos {
  fill: currentColor;
  d: path("M6.687 1.777a1.5 1.5 0 0 1 2.629 0l5.499 9.999a1.5 1.5 0 0 1-1.314 2.223H2.502a1.5 1.5 0 0 1-1.314-2.223zm1.752.482a.5.5 0 0 0-.876 0l-5.499 9.999a.5.5 0 0 0 .438.74h10.999a.5.5 0 0 0 .438-.74z");
}

</style>
