<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/repvixbuj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="repvixbuj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:unhappy-line" /></template>
