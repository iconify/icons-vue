<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fg3t63bhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stacks-outline" /></template>
<style>
.fg3t63bhj {
  fill: currentColor;
  d: path("M12 13.385L2.02 8.192L12 3l10 5.192zm0 3.807l-9.406-4.886l1.043-.573L12 16.052l8.383-4.32l1.042.574zM12 21l-9.406-4.887l1.043-.573L12 19.86l8.383-4.32l1.042.573zm0-8.756l7.921-4.052L12 4.141L4.098 8.192zm.02-4.052");
}

</style>
