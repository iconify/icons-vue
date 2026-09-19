<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wi1156b9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-open-in-browser" /></template>
<style>
.wi1156b9i {
  fill: currentColor;
  d: path("M3 4v16h6v-2H5V8h14v10h-4v2h6V4zm9 6l-4 4h3v6h2v-6h3z");
}

</style>
