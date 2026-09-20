<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5sbu5b3g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:speaker-0-24-filled" /></template>
<style>
.i5sbu5b3g {
  fill: currentColor;
  d: path("M14.704 3.44c.191.226.296.512.296.808V19.75a1.25 1.25 0 0 1-2.058.954l-4.967-4.206H4.25A2.25 2.25 0 0 1 2 14.248v-4.5a2.25 2.25 0 0 1 2.25-2.25h3.725l4.968-4.204a1.25 1.25 0 0 1 1.761.147");
}

</style>
