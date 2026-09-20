<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbu43julu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbu43julu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:sort-descending" /></template>
