<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhtcfkb7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-turn-slight-right" /></template>
<style>
.uhtcfkb7i {
  fill: currentColor;
  d: path("M12.34 6V4H18v5.66h-2V7.41l-5 5V20H9v-7.58c0-.53.21-1.04.59-1.41l5-5h-2.25z");
}

</style>
