<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="t90ki9j1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sparkle-12-regular" /></template>
<style>
.t90ki9j1a {
  fill: currentColor;
  d: path("M7.904 6.332a.7.7 0 0 1 1.193 0l.051.102l.255.62a1 1 0 0 0 .544.545l.62.255a.7.7 0 0 1 0 1.294l-.62.255a1 1 0 0 0-.544.545l-.255.62a.7.7 0 0 1-1.294 0l-.255-.62a1 1 0 0 0-.545-.545l-.62-.255a.7.7 0 0 1 0-1.294l.62-.255a1 1 0 0 0 .545-.545l.255-.62zm.596 1.15A2 2 0 0 1 7.48 8.5c.456.201.819.564 1.02 1.019A2 2 0 0 1 9.52 8.5A2 2 0 0 1 8.5 7.48M3.818 1.378c.328-.542 1.166-.503 1.421.116l.501 1.219c.102.247.298.443.545.545l1.219.5a.8.8 0 0 1 0 1.48l-1.219.501a1 1 0 0 0-.545.545l-.5 1.219a.8.8 0 0 1-1.48 0l-.501-1.219a1 1 0 0 0-.545-.545l-1.219-.5a.8.8 0 0 1 0-1.48l1.219-.501a1 1 0 0 0 .545-.545l.5-1.219zm.366 1.716a2 2 0 0 1-1.09 1.089l-.768.315l.769.316a2 2 0 0 1 1.089 1.09l.315.768l.316-.768a2 2 0 0 1 1.09-1.09l.768-.316l-.768-.315a2 2 0 0 1-1.09-1.09L4.5 2.327z");
}

</style>
