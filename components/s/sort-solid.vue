<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm4qh8gpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cm4qh8gpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sort-solid" /></template>
