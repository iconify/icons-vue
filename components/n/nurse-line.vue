<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vw6fb8b2y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vw6fb8b2y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:nurse-line" /></template>
