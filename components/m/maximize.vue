<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e94gmx3je.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e94gmx3je"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:maximize" /></template>
