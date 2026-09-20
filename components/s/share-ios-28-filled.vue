<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="x9kjgha6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:share-ios-28-filled" /></template>
<style>
.x9kjgha6y {
  fill: currentColor;
  d: path("M14.707 2.293a1 1 0 0 0-1.414 0l-6.75 6.75a1 1 0 0 0 1.414 1.414L13 5.414V18a1 1 0 1 0 2 0V5.414l5.043 5.043a1 1 0 0 0 1.414-1.414zM4 13a1 1 0 0 1 1 1v7a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2v-7a1 1 0 1 1 2 0v7a4 4 0 0 1-4 4H7a4 4 0 0 1-4-4v-7a1 1 0 0 1 1-1");
}

</style>
