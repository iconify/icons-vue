<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yexscu63x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yexscu63x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:skip-forward-round" /></template>
