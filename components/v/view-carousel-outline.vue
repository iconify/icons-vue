<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gtdrn6hty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gtdrn6hty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:view-carousel-outline" /></template>
