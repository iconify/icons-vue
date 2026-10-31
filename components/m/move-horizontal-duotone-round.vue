<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1-uwksly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1-uwksly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:move-horizontal-duotone-round" /></template>
