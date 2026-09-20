<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsph4ybax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsph4ybax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:order-alphabetical-ascending" /></template>
