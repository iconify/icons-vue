<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xibd44bxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xibd44bxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dot-fill-round" /></template>
