<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz4e8gbjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wz4e8gbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-off-fill-round" /></template>
