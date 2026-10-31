<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff3xd_gyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ff3xd_gyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tiktok-round" /></template>
