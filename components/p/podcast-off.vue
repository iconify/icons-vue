<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wh9dy1eza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wh9dy1eza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:podcast-off" /></template>
