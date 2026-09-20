<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="ux8gj5aux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sparkle-off-12-regular" /></template>
<style>
.ux8gj5aux {
  fill: currentColor;
  d: path("M7.904 6.332a.7.7 0 0 1 1.193 0l.051.102l.255.62a1 1 0 0 0 .544.545l.62.255a.7.7 0 0 1 0 1.294l-.62.255a1 1 0 0 0-.544.545l-.255.62a.7.7 0 0 1-1.294 0l-.255-.62a1 1 0 0 0-.545-.545l-.62-.255a.7.7 0 0 1 0-1.294l.62-.255a1 1 0 0 0 .545-.545l.255-.62zm2.242-5.186a.5.5 0 1 1 .707.708l-9 9a.5.5 0 0 1-.707-.707zM8.5 7.481a2 2 0 0 1-1.02 1.02c.456.201.819.564 1.02 1.019A2 2 0 0 1 9.52 8.5A2 2 0 0 1 8.5 7.48m-4.682-6.1c.328-.542 1.166-.503 1.421.116l.501 1.219c.102.247.298.443.545.545l.236.096l-.76.76a2 2 0 0 1-.946-1.02l-.315-.77l-.315.769a2 2 0 0 1-1.09 1.089l-.768.315l.769.316a2 2 0 0 1 1.02.946l-.76.76l-.096-.236a1 1 0 0 0-.545-.545l-1.219-.5a.8.8 0 0 1 0-1.48l1.219-.501a1 1 0 0 0 .545-.545l.5-1.219z");
}

</style>
