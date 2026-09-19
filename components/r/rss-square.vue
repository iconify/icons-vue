<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4j6sacdj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1536};
const content = `<path class="t4j6sacdj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:rss-square" /></template>
