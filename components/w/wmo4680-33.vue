<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy7btdbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="wy7btdbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:wmo4680-33" /></template>
