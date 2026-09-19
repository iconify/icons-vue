<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3k7jj86s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-view-compact-alt" /></template>
<style>
.f3k7jj86s {
  fill: currentColor;
  d: path("M22 4H2v16h20zM11.5 16.5h-4v-4h4zm0-5h-4v-4h4zm5 5h-4v-4h4zm0-5h-4v-4h4z");
}

</style>
