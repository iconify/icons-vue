<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i7xu6bmii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i7xu6bmii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:water-bold" /></template>
