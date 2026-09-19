<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbyk9qy4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-play-disabled" /></template>
<style>
.rbyk9qy4o {
  fill: currentColor;
  d: path("M16.45 13.62L19 12L8 5v.17zM2.81 2.81L1.39 4.22L8 10.83V19l4.99-3.18l6.78 6.78l1.41-1.41zM10 15.36v-2.53l1.55 1.55z");
}

</style>
