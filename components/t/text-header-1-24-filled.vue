<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubv_zfm9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-header-1-24-filled" /></template>
<style>
.ubv_zfm9a {
  fill: currentColor;
  d: path("M20.182 5.017q.134.024.253.082c.36.174.578.544.565.934V18a1 1 0 1 1-2 0V9.611a5.7 5.7 0 0 1-2.183 1.338a1 1 0 0 1-.633-1.897c1.129-.377 2.182-1.333 2.858-3.339a1 1 0 0 1 .278-.446a1 1 0 0 1 .862-.25M3 5a1 1 0 0 1 1 1v5h6V6a1 1 0 1 1 2 0v12a1 1 0 1 1-2 0v-5H4v5a1 1 0 1 1-2 0V6a1 1 0 0 1 1-1");
}

</style>
