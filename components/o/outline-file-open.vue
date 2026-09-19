<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5wv7ob-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-file-open" /></template>
<style>
.o5wv7ob-z {
  fill: currentColor;
  d: path("M15 22H6c-1.1 0-2-.9-2-2V4c0-1.1.9-2 2-2h8l6 6v6h-2V9h-5V4H6v16h9zm4-.34v-2.24l2.95 2.95l1.41-1.41L20.41 18h2.24v-2H17v5.66z");
}

</style>
