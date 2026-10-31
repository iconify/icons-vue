<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p179t_bns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p179t_bns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:toggle-right-round" /></template>
