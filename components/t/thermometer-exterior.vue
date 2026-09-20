<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v82socb4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":30};
const content = `<path class="v82socb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wi:thermometer-exterior" /></template>
