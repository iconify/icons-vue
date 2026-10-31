<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp8z4moyz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp8z4moyz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shower-round" /></template>
