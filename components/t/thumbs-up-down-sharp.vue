<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v7is9gtug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:thumbs-up-down-sharp" /></template>
<style>
.v7is9gtug {
  fill: currentColor;
  d: path("M0 14V5.4L5.4 0l1.225 1.225L5.8 5H12v2.575L9.275 14zm18.6 10l-1.225-1.225L18.2 19H12v-2.575L14.725 10H24v8.6z");
}

</style>
