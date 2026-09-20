<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v7-_jbbvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="v7-_jbbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:night-storm-showers" /></template>
