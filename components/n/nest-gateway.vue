<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv26jgn9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yv26jgn9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:nest-gateway" /></template>
