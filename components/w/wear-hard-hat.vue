<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cx1a2vbqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cx1a2vbqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:wear-hard-hat" /></template>
