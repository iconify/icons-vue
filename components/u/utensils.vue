<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydug6fb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydug6fb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:utensils" /></template>
