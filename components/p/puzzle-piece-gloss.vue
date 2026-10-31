<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yghrc8bqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-k yghrc8bqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:puzzle-piece-gloss" /></template>
