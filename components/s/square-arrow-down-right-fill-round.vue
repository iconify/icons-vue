<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o4h-flc5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o4h-flc5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-arrow-down-right-fill-round" /></template>
