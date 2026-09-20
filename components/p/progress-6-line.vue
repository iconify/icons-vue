<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zjailibat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjailibat"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:progress-6-line" /></template>
