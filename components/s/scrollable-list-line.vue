<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yr8ax0b3z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yr8ax0b3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:scrollable-list-line" /></template>
