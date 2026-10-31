<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ymcycuvvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymcycuvvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:upload-round" /></template>
