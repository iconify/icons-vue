<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mdkhoxb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="mdkhoxb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:owm-day-906" /></template>
