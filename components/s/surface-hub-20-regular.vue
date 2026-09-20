<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gcmka3uav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:surface-hub-20-regular" /></template>
<style>
.gcmka3uav {
  fill: currentColor;
  d: path("M4.76 2.453A.5.5 0 0 1 5.26 2H15.5a.5.5 0 0 1 .498.547l-.759 8a.5.5 0 0 1-.498.453h-.665l.919 6.43a.5.5 0 0 1-.99.14L13.638 15h-2.276l-.367 2.57a.5.5 0 0 1-.99-.14l.347-2.43h-2.99l-.367 2.57a.5.5 0 0 1-.99-.14L6.923 11H4.5a.5.5 0 0 1-.498-.547zM7.506 14h2.99l.429-3h-2.99zm4 0h1.99l-.429-3h-1.132zm2.782-4l.663-7H5.713l-.663 7z");
}

</style>
