<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vu7d_iy0q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vu7d_iy0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:slides" /></template>
