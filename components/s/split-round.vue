<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mulepgbpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mulepgbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:split-round" /></template>
