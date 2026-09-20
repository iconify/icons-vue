<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t75d38blk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-cell-add-16-filled" /></template>
<style>
.t75d38blk {
  fill: currentColor;
  d: path("M11.5 7a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m-5.477 5a5.47 5.47 0 0 0 1.235 3H6.5A1.5 1.5 0 0 1 5 13.5V12zM11.5 9a.5.5 0 0 0-.5.5V11H9.5a.5.5 0 0 0 0 1H11v1.5a.5.5 0 0 0 1 0V12h1.5a.5.5 0 0 0 0-1H12V9.5a.5.5 0 0 0-.5-.5M4 11H2.5A1.5 1.5 0 0 1 1 9.5v-3A1.5 1.5 0 0 1 2.5 5H4zm7-4.977A5.5 5.5 0 0 0 6.023 11H5V5h6zM13.5 5A1.5 1.5 0 0 1 15 6.5v.757a5.47 5.47 0 0 0-3-1.234V5zm-4-4A1.5 1.5 0 0 1 11 2.5V4H5V2.5A1.5 1.5 0 0 1 6.5 1z");
}

</style>
