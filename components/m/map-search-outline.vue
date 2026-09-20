<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gljqf7bmj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gljqf7bmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:map-search-outline" /></template>
