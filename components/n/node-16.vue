<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/prz566bot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="prz566bot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:node-16" /></template>
