<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnnk2pxpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnnk2pxpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:user-star-corner-fill-round" /></template>
