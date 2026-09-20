<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sogv6dscv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sogv6dscv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:vectors-anchor-rectangle" /></template>
