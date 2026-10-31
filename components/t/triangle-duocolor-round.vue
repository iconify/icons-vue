<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y4ox4acgd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y4ox4acgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:triangle-duocolor-round" /></template>
