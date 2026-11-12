<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c80kiybsf"/><path class="ib6qaybse"/><path class="efa1bkb1o"/><path class="dntz9tmey"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:reorder-outline" /></template>
<style>
.c80kiybsf {
  fill: currentColor;
  d: path("M19 17.25C19.4142 17.25 19.75 17.5858 19.75 18C19.75 18.4142 19.4142 18.75 19 18.75H5C4.58579 18.75 4.25 18.4142 4.25 18C4.25 17.5858 4.58579 17.25 5 17.25H19Z");
}

.dntz9tmey {
  fill: currentColor;
  d: path("M19 5.25C19.4142 5.25 19.75 5.58579 19.75 6C19.75 6.41421 19.4142 6.75 19 6.75H5C4.58579 6.75 4.25 6.41421 4.25 6C4.25 5.58579 4.58579 5.25 5 5.25H19Z");
}

.efa1bkb1o {
  fill: currentColor;
  d: path("M19 9.25C19.4142 9.25 19.75 9.58579 19.75 10C19.75 10.4142 19.4142 10.75 19 10.75H5C4.58579 10.75 4.25 10.4142 4.25 10C4.25 9.58579 4.58579 9.25 5 9.25H19Z");
}

.ib6qaybse {
  fill: currentColor;
  d: path("M19 13.25C19.4142 13.25 19.75 13.5858 19.75 14C19.75 14.4142 19.4142 14.75 19 14.75H5C4.58579 14.75 4.25 14.4142 4.25 14C4.25 13.5858 4.58579 13.25 5 13.25H19Z");
}

</style>
