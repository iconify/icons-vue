<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m17loqb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m17loqb1y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:noteblock-text-line" /></template>
