<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ledxs3bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:speaker-box-24-filled" /></template>
<style>
.ledxs3bao {
  fill: currentColor;
  d: path("M4 5.25A3.25 3.25 0 0 1 7.25 2h9.5A3.25 3.25 0 0 1 20 5.25v13.5A3.25 3.25 0 0 1 16.75 22h-9.5A3.25 3.25 0 0 1 4 18.75zm8 7.25a2 2 0 1 0 0 4a2 2 0 0 0 0-4m-3.5 2a3.5 3.5 0 1 0 7 0a3.5 3.5 0 0 0-7 0M12 9a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

</style>
