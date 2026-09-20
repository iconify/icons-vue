<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yeom7qppr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yeom7qppr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:numbers-line" /></template>
