<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_3256sln.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_3256sln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:queue-first-in-last-out" /></template>
