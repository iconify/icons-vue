<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmo0v4bgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:monitor-heart-outline-sharp" /></template>
<style>
.jmo0v4bgs {
  fill: currentColor;
  d: path("M2 9V4h20v5h-2V6H4v3zm0 11v-5h2v3h16v-3h2v5zm5.375-7l1.95 3.9h1.35L14 10.25L15.375 13H22v-2h-5.375l-1.95-3.9h-1.35L10 13.75L8.625 11H2v2zM12 12");
}

</style>
