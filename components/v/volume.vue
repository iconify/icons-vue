<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t7al2kfrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7al2kfrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:volume" /></template>
