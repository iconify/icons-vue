<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k4n51fjcs"/><path class="nqydppbzr"/><path class="ece932bmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-6mp" /></template>
<style>
.ece932bmi {
  fill: currentColor;
  d: path("M11.5 9H13v1.5h-1.5z");
}

.k4n51fjcs {
  fill: currentColor;
  d: path("M15 14h1.5v1.5H15z");
}

.nqydppbzr {
  fill: currentColor;
  d: path("M19 3H5c-1.1 0-2 .9-2 2v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2m-9 3.5c0-.55.45-1 1-1h2.75c.41 0 .75.34.75.75s-.34.75-.75.75H11.5v1h2c.55 0 1 .45 1 1v1.5c0 .55-.45 1-1 1H11c-.55 0-1-.45-1-1zm2.5 11.25c0 .41-.34.75-.75.75s-.75-.34-.75-.75V14h-1v2.25c0 .41-.34.75-.75.75s-.75-.34-.75-.75V14h-1v3.75c0 .41-.34.75-.75.75S6 18.16 6 17.75V13.5c0-.55.45-1 1-1h4.5c.55 0 1 .45 1 1zM18 16c0 .55-.45 1-1 1h-2v.75c0 .41-.34.75-.75.75s-.75-.34-.75-.75V13.5c0-.55.45-1 1-1H17c.55 0 1 .45 1 1z");
}

</style>
