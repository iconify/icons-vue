<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyfn0ssng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyfn0ssng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:unfold-less-vertical" /></template>
