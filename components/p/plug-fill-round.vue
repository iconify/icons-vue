<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgbug4bwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgbug4bwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plug-fill-round" /></template>
