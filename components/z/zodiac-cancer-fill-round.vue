<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ss2l69fuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ss2l69fuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-cancer-fill-round" /></template>
