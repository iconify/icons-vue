<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jp3_oxbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:map-drive-16-regular" /></template>
<style>
.jp3_oxbhy {
  fill: currentColor;
  d: path("M12.5 5a.5.5 0 1 0 0-1a.5.5 0 0 0 0 1m-10-3A1.5 1.5 0 0 0 1 3.5v2.996a.5.5 0 0 0 .5.5h6.011V8H6.5a.5.5 0 0 0-.5.5V10H5a.5.5 0 0 0-.5.5v1h-3a.5.5 0 0 0 0 1h3v1a.5.5 0 0 0 .5.5h6a.5.5 0 0 0 .5-.5v-1h3a.5.5 0 0 0 0-1h-3v-1a.5.5 0 0 0-.5-.5h-1V8.5a.5.5 0 0 0-.5-.5h-.989V6.996H14.5a.5.5 0 0 0 .5-.5V3.5A1.5 1.5 0 0 0 13.5 2zM2 3.5a.5.5 0 0 1 .5-.5h11a.5.5 0 0 1 .5.5v2.496H2zM7 9h2v1.5a.5.5 0 0 0 .5.5h1v2h-5v-2h1a.5.5 0 0 0 .5-.5z");
}

</style>
