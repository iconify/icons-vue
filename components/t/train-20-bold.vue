<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/whf-7i3fs.css';
import '../../css/m/mfifo7bbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="whf-7i3fs"/><path class="mfifo7bbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:train-20-bold" /></template>
