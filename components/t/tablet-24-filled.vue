<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_hrtttrr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tablet-24-filled" /></template>
<style>
.a_hrtttrr {
  fill: currentColor;
  d: path("M19.749 4a2.25 2.25 0 0 1 2.25 2.25v11.502a2.25 2.25 0 0 1-2.25 2.25H4.25A2.25 2.25 0 0 1 2 17.752V6.25A2.25 2.25 0 0 1 4.25 4zM13.75 15.5h-3.5a.75.75 0 0 0 0 1.5h3.5a.75.75 0 1 0 0-1.5");
}

</style>
