<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpu8p3bwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpu8p3bwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:omega-solid" /></template>
