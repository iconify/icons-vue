<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="swbfynbzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-topic-add-20-filled" /></template>
<style>
.swbfynbzv {
  fill: currentColor;
  d: path("M15.5 11a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m0 2a.5.5 0 0 0-.5.5V15h-1.5a.5.5 0 0 0 0 1H15v1.5a.5.5 0 0 0 1 0V16h1.5a.5.5 0 0 0 0-1H16v-1.5a.5.5 0 0 0-.5-.5M15 7a3 3 0 0 1 3 3v.6a5.5 5.5 0 0 0-7.792 6.4H5a3 3 0 0 1-3-3v-4a3 3 0 0 1 3-3zm-9.5 5a.5.5 0 0 0 0 1h4a.5.5 0 0 0 0-1zm0-2a.5.5 0 0 0 0 1h6a.5.5 0 0 0 0-1zm11-7a1.5 1.5 0 0 1 0 3h-13a1.5 1.5 0 1 1 0-3z");
}

</style>
