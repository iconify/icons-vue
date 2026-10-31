<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8qm1n3wh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8qm1n3wh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:podium-round" /></template>
