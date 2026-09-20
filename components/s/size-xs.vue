<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d3spyu8-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3spyu8-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:size-xs" /></template>
