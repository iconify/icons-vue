<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pg8zitz7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pg8zitz7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:report-box-outline" /></template>
