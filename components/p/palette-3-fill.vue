<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y1jh9or0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y1jh9or0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:palette-3-fill" /></template>
