<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie9yf-1hu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ie9yf-1hu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:plane" /></template>
