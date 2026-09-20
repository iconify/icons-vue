<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zila6obrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zila6obrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:microphone-1-bold" /></template>
