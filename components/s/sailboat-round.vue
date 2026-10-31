<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wm2m2btlp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm2m2btlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sailboat-round" /></template>
