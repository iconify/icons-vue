<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt3wtssut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt3wtssut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mars-fill-round" /></template>
