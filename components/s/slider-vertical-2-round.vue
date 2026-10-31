<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zymrr9x_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zymrr9x_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:slider-vertical-2-round" /></template>
