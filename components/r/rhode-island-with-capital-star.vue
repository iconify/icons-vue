<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/salf2bcen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="salf2bcen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:rhode-island-with-capital-star" /></template>
