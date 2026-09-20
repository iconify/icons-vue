<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2i3x8k4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y2i3x8k4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:tile" /></template>
