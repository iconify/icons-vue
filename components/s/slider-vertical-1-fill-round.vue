<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yahzeibjy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yahzeibjy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slider-vertical-1-fill-round" /></template>
