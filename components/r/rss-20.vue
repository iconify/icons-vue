<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czrtizfuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="czrtizfuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:rss-20" /></template>
