<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="q5oyw5bwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:textbox-align-20-filled" /></template>
<style>
.q5oyw5bwq {
  fill: currentColor;
  d: path("M14.5 3A2.5 2.5 0 0 1 17 5.5v9a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 3 14.5v-9A2.5 2.5 0 0 1 5.5 3zm-8 5a.5.5 0 0 0 0 1h7a.5.5 0 0 0 0-1zm1 3a.5.5 0 0 0 0 1h5a.5.5 0 0 0 0-1z");
}

</style>
