<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6r1jbnmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-splitscreen" /></template>
<style>
.x6r1jbnmo {
  fill: currentColor;
  d: path("M18 4v5H6V4zm2-2H4v9h16zm-2 13v5H6v-5zm2-2H4v9h16z");
}

</style>
