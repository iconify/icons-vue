<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yig1kjy8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yig1kjy8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:picture-in-picture" /></template>
