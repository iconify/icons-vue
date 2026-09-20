<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/umx9k2iuy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umx9k2iuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:map-marker-plus-line" /></template>
