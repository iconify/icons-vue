<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3jfks2kf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:more-vertical-24-regular" /></template>
<style>
.a3jfks2kf {
  fill: currentColor;
  d: path("M12 7.75a1.75 1.75 0 1 1 0-3.5a1.75 1.75 0 0 1 0 3.5m0 6a1.75 1.75 0 1 1 0-3.5a1.75 1.75 0 0 1 0 3.5M10.25 18a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 0 0-3.5 0");
}

</style>
