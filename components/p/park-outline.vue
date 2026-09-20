<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3uykdvbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:park-outline" /></template>
<style>
.b3uykdvbp {
  fill: currentColor;
  d: path("M12.989 21H11.01v-4H4.885l4-6H6.922L12 3.73L17.077 11h-1.961l4 6h-6.127zM6.75 16h4h-1.9h6.3h-1.9h4zm0 0h10.5l-4-6h1.9L12 5.5L8.85 10h1.9z");
}

</style>
