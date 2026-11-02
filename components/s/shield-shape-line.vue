<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc6tizw8s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sc6tizw8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:shield-shape-line" /></template>
