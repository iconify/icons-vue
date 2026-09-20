<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="lpvog_7ml"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sparkle-off-12-filled" /></template>
<style>
.lpvog_7ml {
  fill: currentColor;
  d: path("M7.904 6.332a.7.7 0 0 1 1.193 0l.051.102l.255.62c.102.246.298.443.544.545l.62.254a.7.7 0 0 1 0 1.295l-.62.255a1 1 0 0 0-.544.545l-.255.62a.7.7 0 0 1-1.294 0l-.255-.62a1 1 0 0 0-.545-.545l-.62-.255a.7.7 0 0 1 0-1.295l.62-.254c.247-.102.443-.299.545-.545l.255-.62zm2.242-5.186a.5.5 0 1 1 .707.707l-9 9a.5.5 0 0 1-.707-.707zm-6.328.233c.328-.542 1.166-.503 1.421.116l.501 1.219c.102.247.298.443.545.545l.235.096L3.355 6.52l-.096-.235a1 1 0 0 0-.545-.545l-1.219-.5a.8.8 0 0 1 0-1.48l1.219-.501c.247-.102.443-.298.545-.545l.5-1.219z");
}

</style>
