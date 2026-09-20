<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dul6jbcze.css';
import '../../css/w/w2alchb6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path fill-opacity="0" class="dul6jbcze"><animate fill="freeze" attributeName="fill-opacity" begin="0.5s" dur="0.5s" values="0;1"/></path><path stroke-dashoffset="36" class="w2alchb6j"><animate fill="freeze" attributeName="stroke-dashoffset" dur="0.5s" values="36;0"/></path>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:star-filled-half" /></template>
