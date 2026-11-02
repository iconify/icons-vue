<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khgc5lgty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="khgc5lgty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:map-2-line" /></template>
