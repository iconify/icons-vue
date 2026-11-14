<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sirk2tbqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:save-edit-20-regular" /></template>
<style>
.sirk2tbqd {
  fill: currentColor;
  d: path("M15.81 10.548a1.87 1.87 0 1 1 2.644 2.644l-4.829 4.83a2.2 2.2 0 0 1-1.021.578l-1.498.375a.89.89 0 0 1-1.079-1.08l.374-1.497c.097-.387.297-.74.579-1.021zM13.379 3a2 2 0 0 1 1.414.586l1.621 1.621A2 2 0 0 1 17 6.621v2.385c-.342.016-.68.091-1 .228V6.621a1 1 0 0 0-.293-.707l-1.621-1.621A1 1 0 0 0 13.379 4H13v2.5A1.5 1.5 0 0 1 11.5 8h-4A1.5 1.5 0 0 1 6 6.5V4H5a1 1 0 0 0-1 1v10a1 1 0 0 0 1 1v-4.5A1.5 1.5 0 0 1 6.5 10h7c.4 0 .761.157 1.03.412l-.708.708A.5.5 0 0 0 13.5 11h-7a.5.5 0 0 0-.5.5V16h3.478q-.025.078-.045.155L9.222 17H5a2 2 0 0 1-2-2V5a2 2 0 0 1 2-2zM7 6.5a.5.5 0 0 0 .5.5h4a.5.5 0 0 0 .5-.5V4H7z");
}

</style>
