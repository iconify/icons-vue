<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4awcy7bh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:turn-sharp-right" /></template>
<style>
.c4awcy7bh {
  fill: currentColor;
  d: path("M6 21v-6q0-.825.588-1.412T8 13h8V6.8l-1.6 1.6L13 7l4-4l4 4l-1.4 1.4L18 6.8V13q0 .825-.587 1.413T16 15H8v6z");
}

</style>
