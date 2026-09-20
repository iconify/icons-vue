<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yv0jcz66r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:temperature-degree-celsius-16-filled" /></template>
<style>
.yv0jcz66r {
  fill: currentColor;
  d: path("M2.5 5.5a1 1 0 1 1 2 0a1 1 0 0 1-2 0m1-2.5a2.5 2.5 0 1 0 0 5a2.5 2.5 0 0 0 0-5M11 4.5C9.401 4.5 8 5.76 8 8s1.401 3.5 3 3.5c.882 0 1.703-.382 2.263-1.101c.181-.233.446-.399.741-.399c.564 0 .954.565.644 1.036A4.3 4.3 0 0 1 11 13c-2.544 0-4.5-2.053-4.5-5S8.456 3 11 3c1.525 0 2.84.738 3.648 1.964c.31.471-.08 1.036-.644 1.036c-.295 0-.56-.166-.741-.399A2.83 2.83 0 0 0 11 4.5");
}

</style>
