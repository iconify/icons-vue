<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="l0669ac1a"/><path class="huzmj8beb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:star-and-crescent" /></template>
<style>
.huzmj8beb {
  fill: currentColor;
  d: path("m49.813 37.972l7.533 5.278l-2.846-8.583l7.5-5.322l-9.291-.027l-2.896-8.567l-2.897 8.567l-9.291.027l7.502 5.322l-2.848 8.583z");
}

.l0669ac1a {
  fill: currentColor;
  d: path("M40.593 58.25c-14.207 0-25.728-11.753-25.728-26.249c0-14.498 11.521-26.251 25.728-26.251c2.212 0 4.358.286 6.407.821A28.83 28.83 0 0 0 31.405 2C15.165 2 2 15.432 2 32.001C2 48.569 15.165 62 31.405 62c5.73 0 11.075-1.678 15.595-4.57c-2.049.535-4.195.82-6.407.82");
}

</style>
