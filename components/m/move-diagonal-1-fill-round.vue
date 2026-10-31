<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qmossdbfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmossdbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:move-diagonal-1-fill-round" /></template>
