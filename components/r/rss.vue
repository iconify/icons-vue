<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4ug2vk3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w4ug2vk3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:rss" /></template>
