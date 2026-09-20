<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="duzmehb-v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:speaker-0-20-filled" /></template>
<style>
.duzmehb-v {
  fill: currentColor;
  d: path("M12 3.006c0-.873-1.04-1.327-1.68-.733L6.448 5.866a.5.5 0 0 1-.34.134H3.5A1.5 1.5 0 0 0 2 7.5v5A1.5 1.5 0 0 0 3.5 14h2.607a.5.5 0 0 1 .34.133l3.873 3.594c.64.593 1.68.14 1.68-.733z");
}

</style>
