<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rkcjm9blu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rkcjm9blu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rss-fill-round" /></template>
