<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tg8lbebsq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tg8lbebsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:vibe" /></template>
