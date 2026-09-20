<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="uzetvobtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:more-horizontal-28-regular" /></template>
<style>
.uzetvobtu {
  fill: currentColor;
  d: path("M8.25 14a2.25 2.25 0 1 1-4.5 0a2.25 2.25 0 0 1 4.5 0m8 0a2.25 2.25 0 1 1-4.5 0a2.25 2.25 0 0 1 4.5 0M22 16.25a2.25 2.25 0 1 0 0-4.5a2.25 2.25 0 0 0 0 4.5");
}

</style>
