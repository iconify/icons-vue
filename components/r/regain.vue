<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mdhmqyy-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:regain" /></template>
<style>
.mdhmqyy-m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.314 24c6.008-2.571 10.399-8.195 11.185-14.933c.14-1.196-.79-2.182-1.995-2.182H7.496c-1.205 0-2.134.986-1.995 2.182c.787 6.738 5.177 12.362 11.185 14.933c-6.008 2.571-10.398 8.195-11.185 14.933c-.14 1.196.79 2.182 1.995 2.182h33.008c1.205 0 2.134-.986 1.995-2.182c-.786-6.738-5.177-12.362-11.185-14.933");
}

</style>
