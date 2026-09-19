<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px6thzdhd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="px6thzdhd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:view-toc" /></template>
