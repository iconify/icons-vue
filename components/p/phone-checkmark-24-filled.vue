<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="le0j9mb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-checkmark-24-filled" /></template>
<style>
.le0j9mb_b {
  fill: currentColor;
  d: path("M12.348 2A6.5 6.5 0 0 0 18 13.323v6.427A2.25 2.25 0 0 1 15.75 22h-7.5A2.25 2.25 0 0 1 6 19.75V4.25A2.25 2.25 0 0 1 8.25 2zM10.75 18a.75.75 0 0 0 0 1.5h2.5a.75.75 0 0 0 0-1.5zM16.5 1.5a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m3.354 3.146a.5.5 0 0 0-.707 0L15.5 8.293l-1.646-1.647a.5.5 0 1 0-.707.708l2 2a.5.5 0 0 0 .707 0l4-4a.5.5 0 0 0 0-.708");
}

</style>
