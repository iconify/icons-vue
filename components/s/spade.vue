<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_50w6wob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_50w6wob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:spade" /></template>
