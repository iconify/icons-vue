<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sch4mtahn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tag-percent-16-filled" /></template>
<style>
.sch4mtahn {
  fill: currentColor;
  d: path("M1.587 6.314a1.99 1.99 0 0 0 0 2.822l3.296 3.28a2 2 0 0 0 .64.428a5.5 5.5 0 0 1 7.458-7.254L13 3.01A2 2 0 0 0 10.987 1l-3.25.014a2 2 0 0 0-1.41.584zM10 5a1 1 0 1 1 0-2a1 1 0 0 1 0 2m5 5.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0M7.5 9a1 1 0 1 0 2 0a1 1 0 0 0-2 0m5.348-.853a.5.5 0 0 0-.707 0l-3.996 3.996a.5.5 0 0 0 .707.707l3.996-3.996a.5.5 0 0 0 0-.707M12.5 11a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

</style>
