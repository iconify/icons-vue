<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0btk2rbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e0btk2rbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:view-grid-plus-outline" /></template>
