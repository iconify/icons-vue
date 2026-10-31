<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy2b_qbqy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fy2b_qbqy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-check-corner-fill-round" /></template>
